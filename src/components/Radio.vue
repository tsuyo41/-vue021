<template>
  <div>

      <input type="radio" value="りんご" v-model="selectedValue">りんご
      <input type="radio" value="バナナ" v-model="selectedValue">バナナ
      <input type="radio" value="みかん" v-model="selectedValue">みかん

      <p>選択したくだもの {{ selectedValue }}</p>
  </div>
</template>

<script>
export default {
    data() {
        return {
            // checked: false
            // checkedFruits: []
            selectedValue: null
        }
    }
}
</script>

<style>

</style>