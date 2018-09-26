<template>
  <div>
    <h1>Здесь будет компонент с кнопкой</h1>
    <button :style="{ zoom }" @click="count++">Было: {{ count }} щелчков...</button>
  </div>
</template>

<script>
export default {
  data () {
          return {
            count: 0
          }
        },
  props: {
    zoom: String
  }
}
</script>

<style scoped>
h1, button {
  color: red;
}

</style>
