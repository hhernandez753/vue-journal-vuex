<template>
  <div class="container">
    <div class="col-12 text-center">
      <img alt="Vue logo" src="../assets/logo.png">
      <h1>Hola Mundo</h1>
      <button @click="goToDaybook" class="btn btn-primary">Primary</button>
      <button class="btn btn-secondary">Secondary</button>
      <button class="btn btn-success">Success</button>
    </div>
  </div>
</template>

<script>
export default {
  methods: {
    goToDaybook() {
      this.$router.push({name: 'no-entry'})
    }
  }
}
</script>
