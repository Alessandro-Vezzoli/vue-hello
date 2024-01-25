<script>
export default {
  name: "app",
  data() {
    return {
      message: "MESSAGGIO STAMPATO ATTRAVERSO DATA ",
      img: "public/avatar.png",
    };
  },
};
</script>

<template>
  <div>
    <img :src="img" class="logo" />
    <br />
    {{ message }}
  </div>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
</style>
