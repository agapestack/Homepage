<template>
  <nav id="nav">
    <particles-bg type="circle" :num="3" :bg="true" />
    <div class="brand">
      <h1 style="color: #28a745 !important;">Agape</h1><h1 style="color: #007bff !important;">Stack</h1>
    </div>
  </nav>
</template>

<script>
import { ParticlesBg } from "particles-bg-vue";

export default {
  components: {
    ParticlesBg,
  }
}
</script>

<style scoped>
nav, canvas {
  height: 64px !important;
  width: 100vw !important;
  display: flex;
  align-items: center;
  box-shadow: 1px 3px 6px rgb(0 0 0 / 10%)
}

.brand {
  display: flex;
  align-items: center;
  padding: .5rem 2rem;
}

h1 {
  font-size: 2rem;
  font-weight: 500;
}

</style>