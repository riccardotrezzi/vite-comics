<script>
export default {
  name: "AppHeader",
  data() {
    return {
      message: 'Template Vite + Vue'
    }
  }

}
</script>

<template>
  <header>
    <h1>
      {{ message }}
    </h1>
  </header>
</template>

<style scoped>
header{
  background-color: aquamarine;
  text-align: center;
}
h1 {
  color: black;
}
</style>
