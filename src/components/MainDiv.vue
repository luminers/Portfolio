<template>
  <main class="main-section">
    <div class="div-content carrera">
      <p>
        Estudiante de Tecnicatura Universitaria en Programación en la
        universidad tecnologica nacional de San Francisco, Córdoba.
      </p>
      <img
        class="carrera-img"
        src="https://utn.edu.ar/images/logo-utn.png"
        alt="UTN logo"
      />
    </div>
    <div class="div-content front">
      <img class="icon" src="https://vuejs.org//images/logo.png" alt="icon" />
      <img
        class="icon"
        src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/61/HTML5_logo_and_wordmark.svg/2048px-HTML5_logo_and_wordmark.svg.png"
        alt="icon"
      />
      <img
        class="icon"
        src="https://www.returngis.net/wp-content/uploads/2012/05/logo_CSS3.png"
        alt="icon"
      />
      <img
        class="icon"
        src="https://upload.wikimedia.org/wikipedia/commons/6/6a/JavaScript-logo.png"
        alt="icon"
      />
    </div>
    <div class="div-content back">
      <img
        class="carrera-img"
        src="https://utn.edu.ar/images/logo-utn.png"
        alt="UTN logo"
      />
    </div>
  </main>
</template>

<script>
export default {
  name: "MainDiv",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.icon {
  width: 40px;
}

.main-section {
  height: 100%;
  width: 100%;
  padding: 20px;
}
.div-content {
  display: flex;
  text-align: center;
  justify-content: center;
  align-items: center;
  padding: 10px 0px;
  padding-left: 20px;
  height: 15vh;
  background: rgba(124, 124, 124, 0.129);
  box-shadow: 0 8px 32px 0 rgba(43, 43, 50, 0.37);
  backdrop-filter: blur(4px);
  -webkit-backdrop-filter: blur(4px);
  border-radius: 5px;
  margin-bottom: 20px;
}
.carrera-img {
  width: 200px;
}

.front,
.back {
  width: 50%;
  justify-content: space-around;
}
</style>
