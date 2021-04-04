<template>
  <div class="quem">
    <h1>{{ msg }}</h1>
    <p>
      Meu nome é Dorival Junior, brasileiro/portugues, a viver em Lisboa há 12 anos. 
    </p>
  </div>
</template>

<script>
export default {
  name: "quem",
  props: {
    msg: String,
  },
};
</script>
