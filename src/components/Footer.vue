<template>
  <footer>
    <div class="right"></div>
    <div class="center">
      <h6>Made with 💙 by Agape</h6>
    </div>

    <div class="right">
      <div class="separator"></div>
      <!-- <h1>AgapeStack</h1> -->
      <div class="link__wrapper">
        <a href="https://dashboard.agapestack.com" target="_blank">Dashboard</a>
        <a href="https://drive.agapestack.com" target="_blank">Drive</a>
      </div>
    </div>
  </footer>
</template>

<script>
export default {};
</script>

<style scoped>
footer {
  border-top: 1px solid rgba(0, 0, 0, 0.15);
  height: 35vh;
  width: 100vw;
  display: grid;
  grid-template-columns: repeat(3, 1fr);
}

.center
{
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: left;
  margin: 0 auto;
}

.right {
  display: flex;
  justify-content: center;
  align-items: center;
}

.link__wrapper {
  display: flex;
  flex-direction: column;
}

.separator {
  border-right: 1px solid rgba(0, 0, 0, 0.1);
  height: 60%;
  margin: 0 2em;
}

h1 {
}
</style>