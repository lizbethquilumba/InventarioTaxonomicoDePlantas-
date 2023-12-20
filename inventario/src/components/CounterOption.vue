<template>
  <div></div>
  <h3>{{ Counter }}</h3>
  <button @click="addCounter">Incrementar</button>
</template>

<script lang="ts">
import { defineComponent } from "vue";
export default defineComponent({
  name: "CounterOption",
  components: {},
  data() {
    let Counter = 0;
    return { Counter };
  },
  methods: {
    addCounter() {
      this.Counter++;
    },
  },
});
</script>

<style></style>
