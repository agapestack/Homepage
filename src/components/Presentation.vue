<template>
  <div id="home">
    <div class="special-navbar">
      <div class="nav__wrapper" data-aos="fade-down" data-aos-delay="2250">
        <!-- <div class="link"><a href="#home">Home</a></div>

        <div class="link"><a href="#work">Work</a></div>

        <div class="link"><a href="#about">About</a></div>

        <div class="link"><a href="#contact">Contact</a></div> -->

        <div class="link"><a href="https://dashboard.agapestack.com" target="_blank">Dashboard</a></div>

        <div class="link"><a href="https://drive.agapestack.com" target="_blank">Drive</a></div>

      </div>
    </div>

    <div class="text" data-aos="fade-up" data-aos-duration="750">
      <div class="title-1">Hello, welcome</div>
      <div class="title-2">I'm <span id="pseudo">Agape</span></div>
      <div class="title-3">
        <span id="pseudo-sub">Passionate</span> Developer
      </div>

      <!-- <svg
        class="arrows"
        data-aos="fade"
        data-aos-duration="500"
        data-aos-delay="2500"
      >
        <path class="a1" d="M0 0 L30 32 L60 0"></path>
        <path class="a2" d="M0 20 L30 52 L60 20"></path>
        <path class="a3" d="M0 40 L30 72 L60 40"></path>
      </svg> -->

      <!-- <b-button><a href="#work"></a></b-button> -->
    </div>

    <div class="stack-cards">
      <div
        class="stack"
        data-aos="fade-left"
        data-aos-duration="500"
        data-aos-delay="750"
      >
        <h5>Design</h5>
        <img src="../assets/design.jpg" alt="" />
      </div>

      <div
        class="stack"
        data-aos="fade-left"
        data-aos-duration="500"
        data-aos-delay="1250"
      >
        <h5>Frontend</h5>
        <img src="../assets/frontend.jpg" alt="" />
      </div>

      <div
        class="stack"
        data-aos="fade-left"
        data-aos-duration="500"
        data-aos-delay="1750"
      >
        <h5>Backend</h5>
        <img src="../assets/backend.jpg" alt="" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  methods: {
    scrollPage: function () {},
  },
};
</script>

<style scoped>
#home {
  height: 100vh;
  display: grid;
  grid-template-rows: 0.5fr 1fr 1fr;
}

.arrows {
  width: 60px;
  height: 72px;
}

.arrows path {
  stroke: #007bff;
  fill: transparent;
  stroke-width: 1px;
  animation: arrow 2s infinite;
  -webkit-animation: arrow 2s infinite;
}

@keyframes arrow {
  0% {
    opacity: 0;
  }
  40% {
    opacity: 1;
  }
  80% {
    opacity: 0;
  }
  100% {
    opacity: 0;
  }
}

@-webkit-keyframes arrow /*Safari and Chrome*/ {
  0% {
    opacity: 0;
  }
  40% {
    opacity: 1;
  }
  80% {
    opacity: 0;
  }
  100% {
    opacity: 0;
  }
}

.arrows path.a1 {
  animation-delay: -1s;
  -webkit-animation-delay: -1s; /* Safari 和 Chrome */
}

.arrows path.a2 {
  animation-delay: -0.5s;
  -webkit-animation-delay: -0.5s; /* Safari 和 Chrome */
}

.arrows path.a3 {
  animation-delay: 0s;
  -webkit-animation-delay: 0s; /* Safari 和 Chrome */
}

.nav__wrapper {
  display: flex;
  max-width: 1440px;
  justify-content: space-around;
  margin: 2rem auto;
}

.link {
  transition: 0.3s;
}

.link:hover {
  transform: scale(1.3);
}

.text {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.title-1 {
  font-size: 4rem;
  font-weight: 500;
}

#pseudo,
#pseudo {
  color: #007bff !important;
}

.title-2 {
  font-size: 3rem;
}

#pseudo-sub {
  color: #28a745 !important;
  font-size: 2rem;
}

.title-3 {
  font-size: 2rem;
  margin-bottom: 2rem;
}

/* .title {
  color: #007bff!important;
  color: #28a745!important;
} */

h1 {
  font-size: 3rem;
}

.stack-cards {
  display: flex;
  justify-content: space-around;
  align-items: center;
}

.stack {
  text-align: center;
}

.stack h5 {
  font-size: 1.5rem;
}

.stack img {
  height: 25vh;
  width: 20vw;
  border-radius: 10px;
  border: 2px solid rgba(0, 0, 0, 0.15);
}
</style>