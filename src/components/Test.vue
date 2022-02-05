<template>
  <div id="example-5">
    <select v-model="selected">
      <option disabled value="">请选择</option>
      <option>A</option>
      <option>B</option>
      <option>C</option>
    </select>
    <span>Selected: {{ selected }}</span>
  </div>
</template>

<script>
export default {
  name: "Test",
  data() {
    return {
     selected: ''
    }
  },
}
</script>

<style scoped>

</style>