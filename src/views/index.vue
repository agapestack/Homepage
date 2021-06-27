<template>
  <div id="global__wrapper">
    <Presentation />

    <!-- <div class="main__wrapper">
      <div></div>

      <div class="sections__wrapper">
        <section class="work">
          <Work />
        </section>

        <section class="about">
          <About />
        </section>

        <section class="contact">
          <Contact />
        </section>
      </div>

      <div data-aos="fade-left" data-aos-duration="1000" data-aos-delay="500">
        <nav>
          <div class="link"><a href="#home">Home</a></div>
          <div class="link"><a href="#work">Work</a></div>
          <div class="link"><a href="#about">About</a></div>
          <div class="link"><a href="#contact">Contact</a></div>
        </nav>
      </div>
    </div>

    <Footer /> -->
  </div>
</template>

<script>
import Presentation from "../components/Presentation.vue";
import About from "../components/About.vue";
import Work from "../components/Work.vue";
import Contact from "../components/Contact.vue";
import Footer from "../components/Footer.vue";

export default {
  name: "Home",
  components: {
    Presentation,
    Contact,
    Work,
    About,
    Footer,
  },
};
</script>

<style scoped>
.main__wrapper {
  display: grid;
  grid-template-columns: 1fr 6fr 1fr;
}

nav {
  position: -webkit-sticky; /* Safari */
  position: sticky;
  top: 40vh;
  height: 200px;
  width: 100px;
  margin: 0 auto;
  border-left: 1px solid rgba(0, 0, 0, 0.171);
  display: flex;
  flex-direction: column;
  justify-content: space-around;
}

.link {
  margin: 0 2rem;
  text-decoration: none;
}

section {
  min-height: 100vh;
  width: 100vw;
  max-width: 1440px;
  margin: 0 auto;
}
</style>
