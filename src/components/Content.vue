<template>
  <div class="content">{{ title }}</div>
</template>

<script>
import { ref } from "vue";
export default {
  setup() {
    const title = ref("staff content");
    return { title };
  },
};
</script>

<style>
.content {
  color: blanchedalmond;
}
</style>

