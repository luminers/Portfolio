<template>
  <main class="main-section">
    <h3>Perfil</h3>
    <div class="div-content perfil">
      <p>
        Soy un estudiante universitario en busca de una oportunidad de trabajo
        que me permita crecer laboral y personalmente. Apasionado por la
        tecnología y la innovación, pero dispuesto a aprender sobre cualquier
        rubro. Cuento con una gran capacidad de aprendizaje y un gran sentido de
        responsabilidad.
      </p>
      <img class="img-perfil" :src="img" alt="foto" />
    </div>
  </main>
</template>

<script>
export default {
  name: "ResumenComponente",
  data() {
    return {
      img: "https://scontent.fcor2-1.fna.fbcdn.net/v/t39.30808-6/271826419_6678716818865378_8670965358419858852_n.jpg?_nc_cat=102&ccb=1-7&_nc_sid=09cbfe&_nc_ohc=AkZGqpe2I8wAX-NjS1-&_nc_ht=scontent.fcor2-1.fna&oh=00_AT8ijZh2QKritRlEgpDIMBcBmE7ty9m9INLmKHv7-K6zfg&oe=62A41E43",
    };
  },
};
</script>

<style scoped>
.perfil {
  margin-top: 0;
  width: 100%;
  height: auto;
}

.img-perfil {
  width: 30%;
  border-radius: 10px;
  margin: 30px;
}
</style>
