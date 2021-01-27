<template>
  <div class="about">
    <h2 class="about__header">About Me</h2>
    <img src="../assets/katy.jpg" class="about__image" />
    <p>This is a hobby of mine, I love making cakes and creating beautiful decorations for the top of the cake, I am currently at Sheffield collage learning more about bakery, patisserie and business management.</p>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.about {
  padding: 40px 20px;
  background-color: $colour-blue;
  width: 100%;

  &__header {
    margin-bottom: 15px;
    color: $colour-pink;
    text-align: center;
  }

  &__image {
    width: 20%;
    float: left;
    margin: 0 20px 20px 0;
  }
}
</style>