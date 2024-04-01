<template>
  <div class="container">
    <h1 class="title">Барное меню от бара "У Васька" <br>🤡</h1>
    <NavMenu />
  </div>
</template>

<script>
import NavMenu from "./components/navigation-menu.vue"

export default {
  components: {
    NavMenu,
  }  
}
</script>

<style>
.container {
  width: 70%;
  margin: 0 auto;
  background-color: #B0C4DE;
}

.title {
  text-align: center;
  font-size: 36px;
  margin-bottom: 30px;
  font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
}
</style>
