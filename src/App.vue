<template>
  <LottoGenerator/>
</template>

<script>
import LottoGenerator from './components/LottoGenerator.vue'
export default {
  name: 'App',
  components: {
    LottoGenerator,
  }
}
</script>

<style>
#LottoGeneratorapp {
  font-family: Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>