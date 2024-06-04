<template>
  <button>{{ btn }}</button>
</template>

<script>
import { ref } from "vue";
export default {
  setup() {
    const btn = ref("hi");

    return { btn };
  },
};
</script>
