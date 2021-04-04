<template>
  <div class="oque">
    <h1>{{ msg }}</h1>
    <p>
      Sou desenvolvedor de base de dados relacionais, com experiência em Informix-4gl e SqlServer. 
    </p>
  </div>
</template>

<script>
export default {
  name: "oque",
  props: {
    msg: String,
  },
};
</script>

