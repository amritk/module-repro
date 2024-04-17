<template>
  <div>This is but a test component from the module</div>
</template>

<script setup lang="ts">
import createDebug from "debug";

const debug = createDebug("module-test");
console.log({ debug });
debug("This is but a test log");
</script>
