<template>
  <div class="hobbies">
    <h1>{{ msg }}</h1>
    <p>
      Meu principal hobby, quase um vício é viajar, o que me levou ao segundo hobby, que é a fotografia.
    </p>
  </div>
</template>

<script>
export default {
  name: "hobbies",
  props: {
    msg: String,
  },
};
</script>

