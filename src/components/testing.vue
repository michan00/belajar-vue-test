<template>
  <div class="head">
    <ul>
      <li>home</li>
      <li>about</li>
      <button>test</button>
    </ul>
  </div>
</template>

<script>
export default {
  name: "testing",
  props: {
    msg: String,
  },
};
</script>

<style scoped>
.head {
  color: black;
}
li {
  list-style-type: none;
}
button {
  background-color: blue;
}
</style>