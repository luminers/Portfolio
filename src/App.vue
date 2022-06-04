<template>
  <nav class="header-nav">
    <router-link to="/"><h3>Conocimientos</h3></router-link>
    <router-link to="/about"><h3>Proyectos</h3></router-link>
    <router-link to="/about"><h3>Sobre mi</h3></router-link>
  </nav>
  <router-view />
</template>

<style>
* {
  margin: 0;
  box-sizing: border-box;
}

a {
  text-decoration: none;
  color: #000;
}

body {
  background-color: #558595;
  background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='100' height='100' viewBox='0 0 200 200'%3E%3Cdefs%3E%3ClinearGradient id='a' gradientUnits='userSpaceOnUse' x1='100' y1='33' x2='100' y2='-3'%3E%3Cstop offset='0' stop-color='%23000' stop-opacity='0'/%3E%3Cstop offset='1' stop-color='%23000' stop-opacity='1'/%3E%3C/linearGradient%3E%3ClinearGradient id='b' gradientUnits='userSpaceOnUse' x1='100' y1='135' x2='100' y2='97'%3E%3Cstop offset='0' stop-color='%23000' stop-opacity='0'/%3E%3Cstop offset='1' stop-color='%23000' stop-opacity='1'/%3E%3C/linearGradient%3E%3C/defs%3E%3Cg fill='%23417180' fill-opacity='0.6'%3E%3Crect x='100' width='100' height='100'/%3E%3Crect y='100' width='100' height='100'/%3E%3C/g%3E%3Cg fill-opacity='0.5'%3E%3Cpolygon fill='url(%23a)' points='100 30 0 0 200 0'/%3E%3Cpolygon fill='url(%23b)' points='100 100 0 130 0 100 200 100 200 130'/%3E%3C/g%3E%3C/svg%3E");
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
