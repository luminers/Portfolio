<template>
  <main class="main-section">
    <Proyecto
      v-for="(proyecto, index) in proyectos"
      :key="index"
      :link="proyecto.link"
      :img="proyecto.img"
      :logos="proyecto.logo"
      :title="proyecto.title"
    />
  </main>
</template>

<script>
import Proyecto from "@/components/Proyecto.vue";

export default {
  name: "ProyectosComponente",
  data() {
    return {
      proyectos: [
        {
          link: "https://luminers.github.io/KainotoLandingPage/",
          img: "https://luminers.github.io/KainotoLandingPage/assets/img/nosotros.jpg",
          logo: [
            "https://www.returngis.net/wp-content/uploads/2012/05/logo_CSS3.png",
            "https://upload.wikimedia.org/wikipedia/commons/6/6a/JavaScript-logo.png",
          ],
          title: "Proyecto Kainoto",
        },
        {
          link: "https://luminers.github.io/WP-Api-SPA/",
          img: "https://css-tricks.com/wp-content/uploads/2022/05/wp-patterns-featured-image.jpg",
          logo: [1, 2],
          title: "Scrapper con WordPress API",
        },
      ],
    };
  },
  components: {
    Proyecto,
  },
};
</script>

<style scoped>
.main-section {
  height: 100vh;
  display: flex;
  flex-flow: column wrap;
  align-items: center;
}
</style>
