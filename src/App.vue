<script>
export default {
  data() {
    return {
      hello: "Hello World!",
      par: "Ciao, sono Vite e sono utilissimo!",
    };
  },
};
</script>

<template>
  <div>
    <a href="https://vitejs.dev" target="_blank">
      <img src="/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>

    <h1 class="hello">{{ hello }}</h1>
    <p class="par">{{ par }}</p>
  </div>
</template>

<style>
body {
  background-color: cadetblue;
}
</style>

<style scoped>
.hello {
  padding: 7px;
  color: burlywood;
  box-shadow: inset 1px 1px 5px 5px gold;
}
.par {
  font-size: 30px;
  text-decoration: underline;
}
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
