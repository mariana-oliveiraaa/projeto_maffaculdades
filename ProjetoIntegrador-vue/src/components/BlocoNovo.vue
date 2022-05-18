<script>
export default {
  props: ["nome", "cor"],
};
</script>
<template>
  <div class="areas">
    <article :id="cor" class="block"></article>
    <p class="titulo">{{ nome }}</p>
  </div>
</template>
<style scoped>
.areas {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.titulo {
  margin-top: -5px;
}
</style>
