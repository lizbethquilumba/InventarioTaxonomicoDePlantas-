<template>
  <h3>{{ counter }}</h3>
  <button @click="addCounter"></button>
</template>

<script lang="ts">
import { defineComponent } from "vue";
export default defineComponent({
  name: "CounterComposition",
  setup() {
    let counter = 0;
    const addCounter = () => {
      counter++;
    };
    return { counter, addCounter };
  },
});
</script>
