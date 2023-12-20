<template>
  <div class="post-card">
    <h3>Titulo</h3>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Rerum ad
      temporibus ipsum quasi explicabo eaque, aspernatur quia atque deserunt
      adipisci id, mollitia voluptatum. Voluptates maxime nihil quae veniam illo
      iste.
    </p>
    <PosButton></PosButton>
  </div>
</template>

<script lang="ts" setup>
import PosButton from "./PosButton.vue";
</script>

<style scoped>
.post-card {
  border-radius: 15px;
  padding: 10px;
  margin: 1px solid #ccc;
}
</style>
