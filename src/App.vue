<template>
  <TrabalhoCloudComputing
    titulo="Trabalho de Cloud Computing & Site Reliability Engineering"
    aluno="Leonardo Bonn Nogueira Bastos"
    professor="Gilmar Luiz Vassoler"
  />
</template>

<script>
import TrabalhoCloudComputing from "./components/TrabalhoCloudComputing.vue"

export default {
  name: "App",
  components: {
    TrabalhoCloudComputing,
  },
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
