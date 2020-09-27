<template>
  <div>
      <select v-model="selectedFruit" name="" id="">
          <option value="" disabled>果物を洗濯</option>
          <option value="りんご">りんご</option>
          <option value="みかん">みかん</option>
          <option value="きゅうい">きゅうい</option>
      </select>
      <p>洗濯した果物： {{ selectedFruit }}</p>
  </div>
</template>

<script>
export default {
data() {
    return {
        selectedFruit: ''
    }
}
}
</script>

<style>

</style>