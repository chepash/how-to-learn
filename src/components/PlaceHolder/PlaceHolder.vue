<template>
  <div class="placeholder-container">
    <h2>Please open this site on desktop. Adaptive design is not ready</h2>
  </div>
</template>

<script>
export default {
  name: "PlaceHolder",
};
</script>

<style scoped>
.placeholder-container {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  margin: 0;
  padding: 0 5vw 0;
}

h2 {
  text-align: center;
}
</style>
