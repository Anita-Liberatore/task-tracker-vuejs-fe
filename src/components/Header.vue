<template>
  <header>
    <h1>{{ title }}</h1>
    <Button label="Add Task" color="#2196f3"/>
  </header>
</template>

<script>
import Button from './Button.vue'

export default {
  props: {
    title: String
  },
  components: {
    Button
  },
}
</script>

<style scoped>
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 20px;
}
</style>