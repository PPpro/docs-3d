# Summary

## Beginners Guide

[Introduction](index.md)

- [Getting Started](getting-started/index.md)
  - [Dashboard](getting-started/dashboard/index.md)
  - [Hello world!](getting-started/helloworld/index.md)
  - [Quick Start: First Game](getting-started/first-game/index.md)
  - [Caution!](getting-started/attention/index.md)

## Editor Manual

- [Editor Introduction](editor/index.md)
  - [Scene Editor](editor/scene/index.md)
  - [Hierarchy Manager](editor/hierarchy/index.md)
  - [Assets](editor/assets/index.md)
  - [Inspector](editor/inspector/index.md)
  - [Console](editor/console/index.md)
  - [Animation](editor/animation/index.md)
  - [Preferences](editor/preferences/index.md)
  - [Project Settings](editor/project/index.md)
  - [Engine Customization Workflow](editor/engine-customization/engine-customization.md)

- [Preview a Game](editor/preview/index.md)
  - [Previewing in Browser](editor/preview/browser.md)
  - [Introduction To Preview Process And Common Error Handling](preview-guid.md)

- [Particle Editor](particle-system/editor/index.md)
  - [Curve Editor](particle-system/editor/curve-editor.md)
  - [Gradient Editor](particle-system/editor/gradient-editor.md)
  - [Particle Effects](particle-system/editor/particle-effect-panel.md)

- [Animation](editor/animation/index.md)
  - [About Animation](editor/animation/animation.md)
  - [Familiar with animation editor](editor/animation/animation-editor.md)
  - [Create Animation components and animation clips](editor/animation/animation-create.md)
  - [Edit Animation Sequence](editor/animation/animation-clip.md)
  - [Creating A Frame Animation](editor/animation/sprite-animation.md)
  - [Edit Animation Curve](editor/animation/animation-curve.md)
  - [Animation event](editor/animation/animation-event.md)
- [Terrain System](editor/terrain/index.md)
- [Lightmap](editor/lightmap/index.md)

- [Build and Publish](editor/publish/index.md)
  - [About the Build Panel](editor/publish/build-panel.md)
  - [General Build Options](editor/publish/build-options.md)
  - [Publishing to the Web](editor/publish/publish-web.md)
  - [Publishing to Native](editor/publish/publish-native.md)
    - [Setup Native Development](editor/publish/setup-native-development.md)
    - [Debuging JavaScript on Native Platforms](editor/publish/debug-jsb.md)
  - [Publishing from the Command Line](editor/publish/publish-in-command-line.md)
  - [Custom Project Build Process](editor/publish/custom-project-build-template.md)
  - [Build Process with FAQ](editor/publish/build-guide.md)
  - Publishing to Mini Games
    - [Publishing to Alipay Mini Games](editor/publish/publish-alipay-mini-game.md)
    - [Publishing to ByteDance Mini Games](editor/publish/publish-bytedance-mini-game.md)
    - [Publishing to Cocos Play](editor/publish/publish-cocos-play.md)
    - [Publishing to Huawei Quick Games](editor/publish/publish-huawei-mini-game.md)
    - [Publishing to OPPO Mini Games](editor/publish/publish-oppo-mini-game.md)
    - [Publishing to vivo Mini Games](editor/publish/publish-vivo-mini-game.md)
    - [Publishing to Baidu Mini Games](editor/publish/publish-baidugame.md)
    - [Publishing to Xiaomi Quick Games](editor/publish/publish-xiaomi-quick-game.md)
    - [Publishing to WeChat Mini Games](editor/publish/publish-wechatgame.md)
      - [WeChat Engine Plugin](editor/publish/wechatgame-plugin.md)

## 进阶使用

- [Extended Editor](editor/extension/readme.md)
  - [The First Extension](editor/extension/first.md)
  - [Install And Share](editor/extension/install.md)
  - [Extension Description](editor/extension/define.md)
  - [Extended Panel](editor/extension/panel.md)
    - [Compose Panel](editor/extension/panel-boot.md)
    - [Panel Message](editor/extension/panel-messages.md)
  - [Contributions](editor/extension/contributions.md)
    - [Message](editor/extension/contributions-messages.md)
    - [Shortcuts](editor/extension/contributions-shortcuts.md)
    - [Menu](editor/extension/contributions-menu.md)
  - [Basic](editor/extension/basic.md)
    - [Extension](editor/extension/package.md)
    - [Message](editor/extension/messages.md)
    - [I18n](editor/extension/i18n.md)
    - [Profile](editor/extension/profile.md)
    - [Editor UI](editor/extension/ui.md)

## Engine Manual

- [功能地图](module-map/index.md)
  - [图形渲染](module-map/graphics.md)

- [Scene and Environment](concepts/scene/index.md)
  - [Coordinate system](concepts/scene/coord.md)
  - [Scene](concepts/scene/scene.md)
  - [Node](concepts/scene/node.md)
  - [Skybox](concepts/scene/skybox.md)

- [Lighting](concepts/scene/light.md)
  - [Physically based lighting](concepts/scene/light/pbr-lighting.md)
  - [Directional lighting](concepts/scene/light/dir-light.md)
  - [Spherical lighting](concepts/scene/light/sphere-light.md)
  - [Spot lighting](concepts/scene/light/spot-light.md)
  - [Shadows](concepts/scene/shadow.md)
  - [Ambient lighting](concepts/scene/ambient.md)

- [Materials System](material-system/overview.md)
  - [YAML 101](material-system/yaml-101.md)
  - [Effect Syntax](material-system/effect-syntax.md)
  - [Pass Params](material-system/pass-parameter-list.md)
  - [Builtin Shader Uniforms](material-system/builtin-shader-uniforms.md)
  - [Builtin Shader Variables](material-system/builtin-shader-variables.md)

- [Audio System](audio-system/overview.md)

- [Particle System](particle-system/overview.md)
  - [Particle System Module](particle-system/module.md)
  - [Main Module](particle-system/main-module.md)
  - [Emitter](particle-system/emitter.md)
  - [Color Module](particle-system/color-module.md)
  - [Size Modulle](particle-system/size-module.md)
  - [Rotation Module](particle-system/rotation-module.md)
  - [Velocity Module](particle-system/velocity-module.md)
  - [Limit Velocity Module](particle-system/limit-velocity-module.md)
  - [Force Module](particle-system/force-module.md)
  - [Texture Animation Module](particle-system/texture-animation-module.md)
  - [Renderer](particle-system/renderer.md)
  - [Trail Module](particle-system/trail-module.md)

- [Animation](engine/animation/index.md)
  - [Animation Components](engine/animation/animation-component.md)
  - [Animation Clips](engine/animation/animation-clip.md)
  - [Skeletal Animation](engine/animation/skeletal-animation.md)
- [Tween](tween/index.md)

- [Physics](physics/physics.md)
  - [Physics Options](physics/physics-item.md)
  - [Physics System](physics/physics-system.md)
  - [Physics Component](physics/physics-component.md)
  - [Using Physics](physics/physics-use.md)
  - [Physics Collider](physics/physics-collider.md)
  - [Materials](physics/physics-material.md)
  - [Rigid Body](physics/physics-rigidbody.md)
  - [Physics Events](physics/physics-event.md)
  - [Group Masks](physics/physics-group-mask.md)
  - [Raycast](physics/physics-raycast.md)

- [UI](ui-system/components/engine/index.md)
  - [Rendering Order](ui-system/components/engine/priority.md)
  - [UI Batch](ui-system/components/engine/ui-batch.md)
  - [Multi-Resolution Adaption](ui-system/components/engine/multi-resolution.md)
  - [Widget Alignment](ui-system/components/engine/widget-align.md)
  - [Label Layout](ui-system/components/engine/label-layout.md)
  - [Auto Layout Container](ui-system/components/engine/auto-layout.md)
  - [List with data](ui-system/components/engine/list-with-data.md)
  - [Stretchable UI Sprite](ui-system/components/engine/sliced-sprite.md)
  - [UI Custom Material](ui-system/components/engine/ui-material.md)

- [Components](editor/components/index.md)
  - [AudioSource](audio-system/overview.md)
  - [MeshRenderer](engine/renderable/model-component.md)
  - [SkinnedMeshRenderer](engine/animation/skeletal-animation.md)
  - [Camera](editor/components/camera-component.md)
  - [DirectionalLight](concepts/scene/light/dir-light.md)
  - [SphereLight](concepts/scene/light/sphere-light.md)
  - [SpotLight](concepts/scene/light/spot-light.md)
  - [Animation](engine/animation/animation-component.md)
  - [Billboard](particle-system/billboard-component.md)
  - [Line](particle-system/line-component.md)
  - [ParticleSystem](particle-system/main-module.md)
  - [BoxCollider](physics/physics-component.md#盒碰撞器组件（boxcollidercomponent）)
  - [SphereCollider](physics/physics-component.md#球碰撞器组件（spherecollidercomponent）)
  - [RigidBody](physics/physics-component.md#刚体组件)
  - [UI Component Reference](ui-system/components/editor/index.md)
    - [UI Renderer Component](ui-system/components/editor/render-component.md)
      - [Sprite Reference](ui-system/components/editor/sprite.md)
      - [Label Reference](ui-system/components/editor/label.md)
      - [Mask Reference](ui-system/components/editor/mask.md)
      - [Graphics Reference](ui-system/components/editor/graphics.md)
      - [RichText Reference](ui-system/components/editor/richtext.md)
      - [UIStaticBatch Reference](ui-system/components/editor/ui-static.md)
    - [UI Basic Component](ui-system/components/editor/base-component.md)
      - [Canvas Reference](ui-system/components/editor/canvas.md)
      - [UITransform Reference](ui-system/components/editor/ui-transform.md)
      - [Widget Reference](ui-system/components/editor/widget.md)
      - [Button Reference](ui-system/components/editor/button.md)
      - [Layout Reference](ui-system/components/editor/layout.md)
      - [EditBox Reference](ui-system/components/editor/editbox.md)
      - [ScrollView Reference](ui-system/components/editor/scrollview.md)
      - [ScrollBar Reference](ui-system/components/editor/scrollbar.md)
      - [ProgressBar Reference](ui-system/components/editor/progress.md)
      - [LabelOutline Reference](ui-system/components/editor/label-outline.md)
      - [Toggle Reference](ui-system/components/editor/toggle.md)
      - [ToggleContainer Reference](ui-system/components/editor/toggleContainer.md)
      - [Slider Reference](ui-system/components/editor/slider.md)
      - [PageView Reference](ui-system/components/editor/pageview.md)
      - [PageViewIndicator Reference](ui-system/components/editor/pageviewindicator.md)
      - [UIMeshRenderer Reference](ui-system/components/editor/ui-model.md)
      - [UIOpacity Reference](ui-system/components/editor/ui-opacity.md)
      - [BlockInputEvents Reference](ui-system/components/editor/block-input-enents.md)

- [脚本指南及事件机制](scripting/index.md)
  - [脚本创建](scripting/setup.md)
  - [脚本基础](scripting/basic.md)
  - [语言支持](scripting/language-support.md)
  - [ccclass](scripting/ccclass.md)
  - [属性参数参考](scripting/reference/attributes.md)
  - [访问节点和其他组件](scripting/access-node-component.md)
  - [常用节点和组件接口](scripting/basic-node-api.md)
  - [生命周期回调](scripting/life-cycle-callbacks.md)
  - [创建和销毁节点](scripting/create-destroy.md)
  - [加载和切换场景](scripting/scene-managing.md)
  - [获取和加载资源](scripting/load-assets.md)
  - [使用计时器](scripting/scheduler.md)
  - [组件](scripting/component.md)
  - [组件顺序](scripting/execution-order-component.md)
  - [事件机制](engine/event/index.md)
  - [插件脚本](scripting/external-scripts.md)
  - [添加 Log](scripting/log.md)
  - [废弃 API](scripting/deprecated.md)

- [Asset Manual](asset/index.md)
  - [Asset workflow](asset/asset-workflow.md)
  - [Loading assets](asset/load-assets.md)
  - [Subpackages](asset/subpackage.md)
  - [Scene](asset/scene.md)
  - [Images](asset/image.md)
    - [Textures](asset/texture.md)
    - [Sprite Frames](asset/sprite-frame.md)
    - [Skybox](concepts/scene/skybox.md#cubemap)
    - [Texture Auto Trim](ui-system/components/engine/trim.md)
    - [Compressed textures](asset/compress-texture.md)
    - [Atlas](asset/atlas.md)
    - [Auto Atlas](asset/auto-atlas.md)
    - [Render-texture](asset/render-texture.md)
  - [Prefab](asset/prefab.md)
  - [Scripting](asset/script.md)
  - [Fonts](asset/font.md)
  - [Audio](asset/audio.md)
  - [Material](asset/material.md)
  - [Mesh](asset/mesh.md)
  - [Animation assets](asset/anim.md)

- [测试规范](tests/index.md)
  - [测试流程文档](tests/qa-process.md)
  - [单元测试](tests/unit-test.md)
