<template>
  <div id="app">
    <nav>
      <router-link to="/">Главная</router-link> |
      <router-link to="/about">О сайте</router-link> |
      <router-link to="/cats">Кошки</router-link> |
      <router-link to="/dogs">Собаки</router-link>
    </nav>
    <router-view/>
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
nav {
  padding: 20px;
}
nav a {
  font-weight: bold;
  color: #2c3e50;
  padding: 0 10px;
}
nav a.router-link-exact-active {
  color: #42b983;
}
</style>