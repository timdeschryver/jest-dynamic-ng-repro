## Run with Jasmine/Karma

Succeeds

```bash
npm run test
```

## Run Jest ([jest-preset-angular](https://github.com/thymikee/jest-preset-angular))

Fails

```bash
npm run test:jest
```

```
No component factory found for DynamicButtonComponent. Did you add it to @NgModule.entryComponents?

      at noComponentFactoryError (../packages/core/src/linker/component_factory_resolver.ts:17:17)
      at CodegenComponentFactoryResolver.Object.<anonymous>.CodegenComponentFactoryResolver.resolveComponentFactory (../packages/core/src/linker/component_factory_resolver.ts:72:13)
      at NgComponentOutlet.Object.<anonymous>.NgComponentOutlet.ngOnChanges (../packages/common/src/directives/ng_component_outlet.ts:105:36)
      at checkAndUpdateDirectiveInline (../packages/core/src/view/provider.ts:207:15)
      at checkAndUpdateNodeInline (../packages/core/src/view/view.ts:429:14)
      at checkAndUpdateNode (../packages/core/src/view/view.ts:389:12)
      at debugCheckAndUpdateNode (../packages/core/src/view/services.ts:430:44)
      at debugCheckDirectivesFn (../packages/core/src/view/services.ts:391:7)
      at Object.eval [as updateDirectives] (ng:/DynamicHostModule/DynamicHostComponent.ngfactory.js:14:9)
      at Object.debugUpdateDirectives [as updateDirectives] (../packages/core/src/view/services.ts:385:19)
      at checkAndUpdateView (../packages/core/src/view/view.ts:359:12)
      at callViewAction (../packages/core/src/view/view.ts:615:11)
      at execComponentViewsAction (../packages/core/src/view/view.ts:559:7)
      at checkAndUpdateView (../packages/core/src/view/view.ts:370:3)
      at callWithDebugContext (../packages/core/src/view/services.ts:629:23)
      at Object.debugCheckAndUpdateView [as checkAndUpdateView] (../packages/core/src/view/services.ts:346:10)
      at ViewRef_.Object.<anonymous>.ViewRef_.detectChanges (../packages/core/src/view/refs.ts:260:16)
      at ComponentFixture.Object.<anonymous>.ComponentFixture._tick (../../packages/core/testing/src/component_fixture.ts:107:28)
      at ../../packages/core/testing/src/component_fixture.ts:120:36
      at ZoneDelegate.invoke (node_modules/zone.js/dist/zone.js:396:30)
      at ProxyZoneSpec.onInvoke (node_modules/zone.js/dist/proxy.js:117:43)
      at ZoneDelegate.invoke (node_modules/zone.js/dist/zone.js:395:36)
      at Object.onInvoke (../packages/core/src/zone/ng_zone.ts:302:25)
      at ZoneDelegate.invoke (node_modules/zone.js/dist/zone.js:395:36)
      at Zone.run (node_modules/zone.js/dist/zone.js:153:47)
      at NgZone.Object.<anonymous>.NgZone.run (../packages/core/src/zone/ng_zone.ts:178:50)
      at ComponentFixture.Object.<anonymous>.ComponentFixture.detectChanges (../../packages/core/testing/src/component_fixture.ts:120:19)
      at src/app/dynamic-host.component.spec.ts:15:13
      at node_modules/tslib/tslib.js:113:75
      at new ZoneAwarePromise (node_modules/zone.js/dist/zone.js:915:33)
      at Object.__awaiter (node_modules/tslib/tslib.js:109:16)
      at src/app/dynamic-host.component.spec.ts:13:49
      at ZoneDelegate.invoke (node_modules/zone.js/dist/zone.js:396:30)
      at ProxyZoneSpec.onInvoke (node_modules/zone.js/dist/proxy.js:117:43)
      at ZoneDelegate.invoke (node_modules/zone.js/dist/zone.js:395:36)
      at Zone.run (node_modules/zone.js/dist/zone.js:153:47)
```
