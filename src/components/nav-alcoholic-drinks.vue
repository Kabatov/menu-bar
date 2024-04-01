<template>
  <div>
    <button
      class="beverages"
      type="button"
      id="alcohol-drink"
      @click="clickList"
    >
      Алкоголь
    </button>
    <div>
      <ul
        class="list-alko-drinks general-style"
        v-if="isVisible"
    >
      <li>Виски - 4000₽</li>
      <li>Ром - 3000₽</li>
      <li>Текила - 3500₽</li>
      <li>Водка - 1500₽</li>
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