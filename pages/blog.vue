<template>
  
  <section class="container">
    <div>
      <img class="banner" src="~/static/pablo_img/Pablo_banner.png" alt="Pablo Cru main banner">
      <h1 class="title">
        Aqui ira tu blog con links a los post en forma de imagenes, con scroll infinito si quieres
      </h1>
      <h2 class="subtitle">
        Todos los links seran staticos al principio y luego se pueden cambiar a dinamicos como hablamos
      </h2>
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

<style scoped>
.container {
  min-height: 100vh;
  /* display: flex;
  justify-content: center;
  align-items: center; */
  text-align: center;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 30;
  font-size: 60px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 10px;
}
.banner{
  background-color: #456789;
  max-width:100%;
  max-height:100%;
  color:#ffffff;
  font-size:40px;
  text-align: center;
}
</style>

