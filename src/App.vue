<template>
  <div id="app">
    <div id="menu" class="logo flex fixed">
      <logo></logo>
      <div id="nav">
        <router-link to="/">Inicio</router-link> |
        <router-link to="/about">Acerca de</router-link>
      </div>
    </div>
    <router-view />
  </div>
</template>

<script>
import Logo from "@/components/Logo.vue";
export default {
  name: "app",
  data() {
    return {
      menu: null
    };
  },
  components: {
    Logo
  },
  computed: {}
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Lobster&display=swap");

* {
  margin: 0;
  padding: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
.logo {
  font-family: "Lobster", cursive;
  background-image: linear-gradient(to right, #a3ddcb, #1a508b);
}
.flex {
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: space-around;
}
.fixed {
  position: fixed;
  z-index: 1;
}
#nav {
  padding: 30px;
}

#nav a {
  font-size: 1.4rem;
  font-weight: bold;
  color: #2c3e50;
  text-decoration: none;
  transition: all 0.5s;
}

#nav a.router-link-exact-active {
  color: #ff884b;
  text-decoration: underline;
  transform: perspective(1.1s);
}
</style>
