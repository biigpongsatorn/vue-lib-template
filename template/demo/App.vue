<template>
  <div id="app">
    <{{ name }}/>
  </div>
</template>

<script>
import {{ name }} from '../src/index.vue'

export default {
  name: 'app',
  components: { {{ name }} }
}
</script>

<style scoped>
</style>
