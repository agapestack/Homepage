<template>
  <div id="app">  
    <main>
      <router-view />
    </main>
  </div>
</template>

<script>

export default {
  name: 'App',
}
</script>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Lato', sans-serif;
  background: #f2f7f5;
  color: #475d5b;
}

h1, h2, h3, h4, h5, h6 {
  color: #475d5b;
}

main {
  min-height: 100vh;
}
</style>
