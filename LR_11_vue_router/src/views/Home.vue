<template>
  <div>
    <h1>Добро пожаловать на главную страницу</h1>
    <p>Этот сайт посвящен интересным фактам о животных.</p>
    <router-link to="/cats">Факты о кошках</router-link> | 
    <router-link to="/dogs">Факты о собаках</router-link>
  </div>
</template>

<script>
export default {
  name: 'Home'
}
</script>