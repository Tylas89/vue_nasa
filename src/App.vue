<template>
  <div class="app">
    <div class="nav">
      <router-link to="/">Nasa API</router-link>
      <router-link to="/about">about</router-link>
    </div>
    <router-view />
  </div>
</template>

<style lang="scss">
@import url('https://fonts.googleapis.com/css?family=Montserrat&display=swap');

*{
  box-sizing: border-box;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
body{
  font-family: 'Montserrat', sans-serif;
  margin: 0;
  padding: 0;
}
</style>
