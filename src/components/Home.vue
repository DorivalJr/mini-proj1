<template>
  <div class="myHome">
    <h1>{{ msg }}</h1>
    <img alt="Vue logo" src="../assets/eu.png" />
    <p>
      Meu mini-cv é uma SPA desenvolvido a partir da framework Vue.js, com sendo a solução da tarefa 2.2.
    </p>
  </div>
</template>

<script>
export default {
  name: "Myhome",
  props: {
    msg: String,
  },
};
</script>

