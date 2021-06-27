<template>
  <div id="work">
    <div class="section-title">
      <h1>Work</h1>
    </div>

    <div class="drive">
      
    </div>


    </div>
  </div>
</template>

<script>
export default {
  components: {},
  data() {
    return {
      projects: [
        {
          title: "AgapeDrive",
          text: "A straightfoward cloud based storage solution.",
          img: "../assets/drive.png",
          id: "1",
        },
        {
          title: "AgapeDrive",
          text: "A straightfoward cloud based storage solution.",
          img: "../assets/drive.png",
          id: "2",
        },
      ],
    };
  },
};
</script>

<style scoped>
#work {
  display: grid;
  grid-template-columns: repeat(6, 1fr);
}

.drive {
  grid-column: 3 / 7;
  height: 60vh;
  border-radius: 10px;
  overflow: hidden;
}

.drive img {
  width: 100%;
  height: 100%;
}

.section-title {
  margin: 2rem;
}
.section-title {
  grid-column: 1 / span 6;
}

.title-1 {
  grid-row: 2;
  grid-column: 2;
}
</style>