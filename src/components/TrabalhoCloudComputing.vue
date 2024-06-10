<template>
  <div class="hello">
    <h1>Disciplina: {{ titulo }}</h1>
    <h2>Aluno: {{ aluno }}</h2>
    <h2>Professor: {{ professor }}</h2>
    <h3>Trabalho 1</h3>
  </div>
</template>

<script>
export default {
  name: "TrabalhoCloudComputing",
  props: {
    titulo: String,
    aluno: String,
    professor: String,
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
