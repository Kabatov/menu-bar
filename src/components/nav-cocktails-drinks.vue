<template>
  <div>
    <button
      class="beverages" 
      type="button"
      id="coctails"
      @click="clickList"
      >
      Коктейли
    </button>
    <div>
      <ul 
        class="list-cocktails general-style"
        v-if="isVisible"
    >
      <li>Маргарита - 600₽</li>
      <li>Кровь и Песок - 700₽</li>
      <li>Френч 75 - 750₽</li>
      <li>Эль Дьябло - 800₽</li>
      <li>Люсьен Гаден - 900₽</li>
      <li>Май Тай - 750₽</li>
      <li>Кловер Клаб - 800₽</li>
    </ul>
    </div>
  </div>
</template>

<script>


export default {
  data() {
    return {
      isVisible: false
    }
  },

  methods: {
    clickList() {
      this.isVisible = !this.isVisible
    }
  }
}
</script>

<style>

</style>