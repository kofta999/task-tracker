<script lang="ts">
export default {
  name: "Footer",
};
</script>

<template>
  <footer>
    <p>Copyright &copy; 2023</p>
    <router-link to="/about">About</router-link>
  </footer>
</template>

<style scoped>
a {
  color: antiquewhite;
}

footer {
  margin-top: 30px;
  text-align: center;
}
</style>
