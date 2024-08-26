<template>
  <div>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
    <div>
      {{ text }}
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      text: "Hola vue",
    };
  },
};
</script>

<style>
p {
  color: red;
}
</style>
