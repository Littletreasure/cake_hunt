<template>
  <div class="container">
  <Header />
    <img src="../assets/cake hunt logo.jpg" />
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
.container {
  background: $colour-pink;
  margin: 0 auto;
  min-height: 100vh;  
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  align-items: center;
  
  img {
    width: 40%;
    border: 1px solid $colour-pink;
  }
}


</style>
