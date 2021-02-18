<template>
  
  <section class="container">
    <div>
      <div class="main-container">
      <img class="main-img" src="~/static/pablo_img/Pablo_main.png" alt="Pablo Cru main picture">
      <h1 class="title">
        ¿Necesitas ayuda con tu marca o marketing?
      </h1>
      <h2 class="subtitle">
        Hola, Mi nombre es Pablo Cru y soy la persona que te va ayudar a sacar el maximo partido a tu marca, ya sea personal o de empresa.
      Aquí encontraras toda la informacion que buscas. Si crees que esto puede ser algo para ti, quedate.
      </h2>
      </div>

     <div>
       <p> Aqui va la explicacion de tu home, esta pagina puede tener tanto scroll como quieras
         incluso scroll infinito, animaciones, etc.
       </p>
     </div>
    </div>
  </section>
</template>

<script>
import AppLogo from '~/components/AppLogo.vue'
import TopNavBar from '~/components/TopNavBar.vue'

export default {
  components: {
    AppLogo,
    TopNavBar
  }
}
</script>

<style>
body{
  margin:0;
}
.container {
  min-height: 100vh;
  /* display: flex;
  justify-content: center;
  align-items: center; */
  text-align: center;
}

.links {
  padding-top: 10px;
}
.main-container {
  margin: auto;
  width:80%;
  height:555px;
  box-sizing: border-box;
  z-index: -20;
  display: grid;
  grid-template-columns: 42.5fr 57.5fr ;
  grid-template-rows: repeat(20, 27.25px);
  border-radius: 25px;
  
}
.main-img{
  grid-column-start: 1;
  grid-column-end: 2;
  grid-row-start: 4;
  grid-row-end: 21;
  border-radius: 20px;
  z-index:-15;
  max-width:100%;
  max-height:100%;
}
.title {
  grid-column-start: 2;
  grid-column-end: 3;
  grid-row-start: 5;
  grid-row-end: 9;
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 30;
  font-size: 42px;
  color: #35495e;
  letter-spacing: 1px;
}
.subtitle{
  grid-column-start: 2;
  grid-column-end: 3;
  grid-row-start: 12;
  grid-row-end: 17;
  margin:25px;
  font-weight: 300;
  font-size: 18px;
  text-align: justify;
  text-justify: inter-word;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
}


</style>

