<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">

    <h1>Hello World</h1>

    <button @click="goToDayBook" class="btn btn-primary">primary</button>
    <button @click="goToDayBook" class="btn btn-secondary">secondary</button>
    <button @click="goToDayBook" class="btn btn-success">success</button>
  </div>
</template>

<script>
export default {
  methods: {
    goToDayBook(){
      this.$router.push({name: 'no-entry'})
    }
  }
}
</script>