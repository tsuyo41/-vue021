<template>
  <div>
      <!-- <input
      type="checkbox"
      v-model="checked"
      > -->

      <input type="checkbox" value="りんご" v-model="checkedFruits">りんご
      <input type="checkbox" value="バナナ" v-model="checkedFruits">バナナ
      <input type="checkbox" value="みかん" v-model="checkedFruits">みかん

      <p>選択したくだもの {{ checkedFruits }}</p>
  </div>
</template>

<script>
export default {
    data() {
        return {
            // checked: false
            checkedFruits: []
        }
    }
}
</script>

<style>

</style>