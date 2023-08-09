<template>
  <h1>Union Catalogue</h1>
  <p>For experimental use only</p>
  <b>by {{ name }} </b>
  <button @click="changeName">Change Name</button>
  
  
</template>

<script>

export default {
  name: 'App',
  data() {
    return{
      name : "Alumni Jozz"
    }
  },
  methods: {
    changeName(){
       this.name = "Alumni Fijozz"
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
