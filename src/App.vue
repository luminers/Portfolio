<template>
  <nav class="header-nav">
    <router-link to="/"><h3>Conocimientos</h3></router-link>
    <router-link to="/proyectos"><h3>Proyectos</h3></router-link>
    <router-link to="/sobre-mi"><h3>Sobre mi</h3></router-link>
  </nav>
  <router-view />
</template>

<style>
* {
  margin: 0;
  box-sizing: border-box;
}

.video-bg {
  position: fixed;
  right: 0;
  top: 0;
  width: 100%;
  height: 100%;
}
video {
  width: 100%;
  height: 100%;
  object-fit: cover;
}
a {
  text-decoration: none;
  color: #000;
}

body {
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2e2f30;
  border: 1px solid #aaa;
  width: 90vw;
  height: 80vh;
  background: rgba(255, 255, 255, 0.25);
  box-shadow: 0 8px 32px 0 rgba(74, 74, 74, 0.37);
  backdrop-filter: blur(2px);
  -webkit-backdrop-filter: blur(4px);
  border-radius: 10px;
  border: 1px solid rgba(255, 255, 255, 0.18);
  display: flex;
  flex-flow: column nowrap;
}

.header-nav {
  width: 90vw;
  height: 90px;

  display: flex;
  align-items: center;
  justify-content: center;
}
.header-nav a {
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100%;
  border-bottom: 1px solid black;
}
.header-nav a:hover {
  box-shadow: 0 8px 12px 0 rgba(2, 2, 2, 0.574);

  transition: 0.5s ease;
}
</style>
