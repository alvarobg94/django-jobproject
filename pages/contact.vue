<template>
  
  <section class="container">
    <div>
      <div class = "banner"> una foto para contacto</div>
      
      <h1 class="title">
        Esta sera tu Contacto
      </h1>
      <h2 class="subtitle">
        Todo interactivo pero con SSR (cosa tecnica) para que no te estropee el SEO
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
  font-weight: 300;
  font-size: 100px;
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
  height:150px;
  width:100%;
  color:#ffffff;
  font-size:40px;
  text-align: center;
}
</style>