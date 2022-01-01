<template>
  <img alt="Vue logo" src="./assets/logo.png">
    <div v-for="item in products" :key="item">
        <h4>{{ item }}</h4>
        <p>50 만원</p>
    </div>
</template>

<script>

export default {
  name: 'App',
  data(){
      return {
          products : ["역삼동원룸", "역사동원룸", "역오동원룸"]
      }
  },
  components: {
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
