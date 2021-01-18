<template>
  <div class="about">
    <div class="modal-profile">
      <img class="profile" src="@/assets/profile2.jpg" alt="profile" />
      <h3 class="titulo">Mucho texto</h3>
      <p class="text">
        Me llamo Andy Jhoao Huacre Molina nací en Lima, Perú y en la actualidad
        vivo en México por temas de trabajo por mi padre. Soy muy competitivo en
        todos los aspectos, estudio en el Instituto Tecnologico de Cuautla
        cursando la carrera de Ingenieria en Sistemas Computacionales. Al inicio
        de la carrera no tenia ningun conocimiento sobre programacion o algo
        relacionado, fue entonces hasta 2do semestre en el que empecé a
        agarrarle al onda a la programación, cuento con varios compañeros que al
        inicio de la carrera eran muy buenos ya que tenian conocimientos
        previos, lo cual activo mi competitividad al aprender ya que me iba mal
        en las primeras unidades. No todos dejaron de aprender algunos siguen
        mejorando como ingenieros y como programadores ya sea en web o
        escritorio. Inicie con el lenguaje de programacion Java, lenguaje
        complejo para mi pensar. Para finalizar en estos momentos sigo mejorando
        mis aptitudes de desarrollador todavia me falta mucho por aprender y
        para eso sigo creando paginas y entrando a cursos online.
      </p>
    </div>
  </div>
</template>
<style scoped>
.about {
  padding: 120px;
}
.modal-profile {
  background-color: #f5f4f4;
  width: 900px;
  height: 580px;
  position: relative;
  padding-top: 30px;
  margin: 0 auto;
  /* box-shadow: 3px 3px 5px 6px #8888; */
  border-radius: 10px;
  box-shadow: rgba(0, 0, 0, 0.1) 0px 20px 25px -5px,
    rgba(0, 0, 0, 0.04) 0px 10px 10px -5px;
}
.profile {
  width: 200px;
  border-radius: 50%;
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
</style>
