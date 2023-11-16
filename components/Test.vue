
<template>
  {{ helloWorld }}
</template>

<script lang="ts">
import { Vue, Component } from "vue-facing-decorator";

@Component
export default class Test extends Vue {
 helloWorld = "hello world";
}
</script>
<style lang="scss" scoped>

</style>