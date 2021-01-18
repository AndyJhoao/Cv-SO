<template>
  <div class="home">
    <!-- <HelloWorld class="logo" msg="Andy Jhoao" /> -->
    <div>
      <div class="background">
        <img
          class="img-back"
          src="@/assets/fondo-black.jpg"
          alt="development"
        />
        <div class="modal-profile">
          <img class="profile" src="@/assets/profile2.jpg" alt="profile" />
          <h3 class="titulo">Mi nombre es : <b>Andy Jhoao Huacre Molina</b></h3>
          <p class="text">
            Estudiante de la carrera de Ingenieria en Sistemas Computacionales,
            apasionado por el desarrollo tanto Front End como Back End. Tengo 21
            años y este es mi curriculum web.
          </p>
        </div>
      </div>
      <div class="proyectos">
        <h2>Proyectos</h2>
        <div class="container-proyectos">
          <h3 class="titulo"><b>Más Limpiecito</b></h3>
          <p class="titulo">
            Página web desarrollada en Vue para una tienda de productos de
            limpieza, sigue en pleno desarrollo.
            <a href="http://mas-limpiecito.com/">Más Limpiecito</a>
          </p>

          <img
            class="img-proyectos"
            src="@/assets/mas-limpiecito.png"
            alt="mas-limpiecito"
          />
        </div>
        <div class="container-proyectos">
          <h3 class="titulo"><b>Platzi-exchange</b></h3>
          <p class="titulo">
            Página web desarrollada en Vue con consume de una API para obtener
            los datos sobre las criptomodenas y tasa de cambio.
            <a href="https://andy-platzi-exchange.netlify.app/"
              >Platzi-Exchange</a
            >
          </p>

          <img
            class="img-proyectos"
            src="@/assets/platzi-exchange.png"
            alt="platzi-exchange"
          />
        </div>
        <h3 class="titulo space"><b>Muchas más proximamente....</b></h3>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Home",
  components: {
    // HelloWorld
  }
};
</script>

<style scoped>
.img-proyectos {
  width: 80%;
  margin-top: 30px;
  border: 2px black solid;
  border-radius: 10px;
}
.space {
  margin: 20px;
}
.img-back {
  width: 1300px;
  height: 550px;
}
.modal-profile {
  background-color: #f5f4f4;
  width: 500px;
  height: 420px;
  position: relative;
  padding-top: 30px;
  margin: 0 auto;
  top: -350px;
  /* box-shadow: 3px 3px 5px 6px #8888; */
  border-radius: 10px;
  box-shadow: rgba(0, 0, 0, 0.1) 0px 20px 25px -5px,
    rgba(0, 0, 0, 0.04) 0px 10px 10px -5px;
}
/* .container-modal {
} */
.profile {
  width: 200px;
  border-radius: 50%;
}
.home {
  padding-top: 100px;
  width: 100%;
  height: auto;
}
.titulo {
  margin-top: 20px;
}
.text {
  margin: 0 30px;
  margin-top: 20px;
  line-height: 1.5;
  text-align: justify;
  font-size: 1.1rem;
}
.background {
  height: 800px;
}
</style>
