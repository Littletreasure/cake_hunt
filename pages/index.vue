<template>
  <main class="container">
    <img src="../assets/cake hunt logo.jpg" />
    <Introduction />
    <div class="break">
    </div>
    <About />
  </main>
</template>

<script>
export default {}
</script>

<style lang="scss" scoped>
.container {
  background: $colour-pink1;
  margin: 0 auto;
  min-height: 100vh;  
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  align-items: center;
  
  img {
    width: 40%;
    border: 1px solid $colour-pink1;
  }
}

.break {
  // background-color: #ff80bf;
  background-image: url('../assets/cupcakes.jpg');
  background-attachment: fixed;
  background-repeat:no-repeat;
  background-size: cover;
  min-height: 100px;
  width: 100%;
}
</style>
