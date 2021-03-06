# Physics Events

The __physics event system__ in __Cocos Creator 3D__ includes *trigger events* and *collision events*.

## Triggers And Colliders

When colliding, the `collider` will produce physical a behavior, however the `trigger` will not. Therefore, the `trigger` is a `collider` that only performs collision detection. The `collider` is a `collider` that performs both collision detection and physical simulation. The difference between them:

- Triggers will not perform more detailed detection with other triggers or colliders.
- Colliders will do more detailed detection with other colliders and will generate collision data, such as collision points, normals, etc.

> **Note**: the `isTrigger` property determines whether the `Collider` component is a trigger or not.

## Trigger Events And Collision Events

### Trigger Events

__Trigger events__ are generated by `triggers`, which are currently divided into three types `onTriggerEnter`, `onTriggerStay`, and `onTriggerExit`. These represent the *trigger start*, *trigger stay*, and *trigger end* events. In order to add listeners to the trigger event, you need to add the corresponding callback by registering the event:

1. Get `ColliderComponent` through `this.getComponent(ColliderComponent)`
2. Register the callback of the corresponding event through the `on` or `once` method of `ColliderComponent`

Code example:

```ts
public start () {
    let Collider = this.getComponent(ColliderComponent);
    Collider.on('onTriggerStay', this.onTrigger, this);
}

private onTrigger (event: ITriggerEvent) {
    console.log(event.type, event);
}
```

### Collision Events

__Collision events__ are generated based on collision data. Collision data only affects dynamic rigid bodies. Therefore, a dynamic rigid body is required to generate collision events.

Collision events are divided into three types: `onCollisionEnter`, `onCollisionStay`, and `onCollisionExit`, which respectively represent the *start of the collision*, *collision hold*, and the *end of the collision*. In order to add a listener to the collision event, you need to add the corresponding callback by registering the event:

1. Get `ColliderComponent` through `this.getComponent(ColliderComponent)`
2. Register the callback of the corresponding event through the `on` or `once` method of `ColliderComponent`

Code example:

```ts
public start () {
    let Collider = this.getComponent(ColliderComponent);
    Collider.on('onCollisionStay', this.onCollision, this);
}

private onCollision (event: ICollisionEvent) {
    console.log(event.type, event);
}
```

> **Note**: `ColliderComponen`t is the parent class of all collision components.

> **Note**: Collision events are in physical elements, and all collider components on this element will receive collision events.

The difference between them:

- Trigger events are generated by triggers, and collision events are generated based on collision data.
- The trigger event can be generated by the trigger with another trigger or another collider.
- Collision events need to be generated by two colliders and at least one dynamic rigid body.

---

Continue to the [Group and Mask](physics-group-mask.md) documentation.
