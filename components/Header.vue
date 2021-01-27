<template>
  <header class="header">
    <img class="header__image" src="../assets/cake hunt logo.jpg" />
    <h4>Gallery</h4>
  </header>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.header {
  width: 100%;
  height: 60px;
  position: sticky;
  top: 0px;
  background: white;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  padding: 0 10px;

  &__image {
    width: 60px;
  }
}
</style>