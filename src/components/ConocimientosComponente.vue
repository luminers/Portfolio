<template>
  <main class="main-section">
    <Carrera />

    <Front />
    <Back />

    <Tools />
    <div class="back-tools"></div>
  </main>
</template>

<script>
import Carrera from "@/components/Carrera.vue";
import Front from "@/components/Front.vue";
import Back from "@/components/Back.vue";
import Tools from "@/components/Tools.vue";

export default {
  name: "ConocimientosComponente",
  components: {
    Carrera,
    Front,
    Back,
    Tools,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
.main-section {
  border: 1px solid green;
  width: 100%;
  height: 200vh;
  padding: 20px;
  display: flex;
  flex-flow: column wrap;
  overflow-y: scroll;
  overflow-x: hidden;
}

.div-content {
  display: flex;
  text-align: center;
  justify-content: center;
  align-items: center;
  padding: 10px 0px;
  height: 15vh;
  background: rgba(124, 124, 124, 0.129);
  box-shadow: 0 8px 32px 0 rgba(43, 43, 50, 0.37);
  backdrop-filter: blur(4px);
  -webkit-backdrop-filter: blur(4px);
  border-radius: 5px;
  margin-bottom: 20px;
}
.carrera {
  padding-left: 30px;
}

.carrera-img {
  width: 200px;
}

.icon {
  width: 40px;
}

.front {
  padding: 10px;
  width: 70%;
  justify-content: space-evenly;
}
.back-tools {
  border: 1px solid black;
  width: 60%;
}
</style>
