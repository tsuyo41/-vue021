<template>
  <div>
      <textarea cols="30" rows="10" v-model="body"></textarea>
      <pre>{{ body }}</pre>
  </div>
</template>

<script>
export default {
    data() {
        return {
            body: ''
        }
    }
}
</script>

<style>

</style>