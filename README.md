
# Error Demo of Nuxt with vue-facing-decorator

To generate error:
```
yarn
yarn generate
```

The erro LOG:
```console
 ERROR  Unexpected character '@' (Note that you need plugins to import files that are not JavaScript)
file: C:/Users/User/GitHubFette/SandBoxErrorNuxtDecorator/components/Test.vue?vue&type=script&lang.ts:4:0
2: import { Vue, Component } from "vue-facing-decorator";
3:
4: @Component
   ^
5: export default class Test extends Vue {
6:  helloWorld = "hello world";


 ERROR  Nuxt Build Error: Unexpected character '@' (Note that you need plugins to import files that are not JavaScript)

  at error (/C:/Users/User/GitHubFette/SandBoxErrorNuxtDecorator/node_modules/rollup/dist/es/shared/node-entry.js:2287:30)
  at Module.error (/C:/Users/User/GitHubFette/SandBoxErrorNuxtDecorator/node_modules/rollup/dist/es/shared/node-entry.js:13745:16)
  at Module.tryParse (/C:/Users/User/GitHubFette/SandBoxErrorNuxtDecorator/node_modules/rollup/dist/es/shared/node-entry.js:14476:25)
  at Module.setSource (/C:/Users/User/GitHubFette/SandBoxErrorNuxtDecorator/node_modules/rollup/dist/es/shared/node-entry.js:14077:39)
  at ModuleLoader.addModuleSource (/C:/Users/User/GitHubFette/SandBoxErrorNuxtDecorator/node_modules/rollup/dist/es/shared/node-entry.js:24649:20)
  at process.processTicksAndRejections (node:internal/process/task_queues:95:5)

error Command failed with exit code 1.
```
