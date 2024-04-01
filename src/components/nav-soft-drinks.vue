<template>
  <div>
    <button 
      class="beverages" 
      type="button"
      id="soft-drinks"
      @click="clickList"
    >
    Б/А напитки
    </button>
    <div>
      <ul 
        class="list-soft-drinks general-style"
        v-if="isVisible"
    >
      <li>Сок - 350₽</li>
      <li>Кока-Кола - 600₽</li>
      <li>Вода - 400₽</li>
      <li>Смузи - 500₽</li>
      <li>Молочный коктейль - 450₽</li>
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