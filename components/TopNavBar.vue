<template>

  <div class="topnav">
  <NuxtLink class="main-link" to="/">Pablo Cru</NuxtLink>
  <NuxtLink  class="about-link" to="/about">About</NuxtLink> 
  <NuxtLink  class="blog-link" to="/blog">Blog</NuxtLink>
  <NuxtLink  class="contact-link" to="/contact">Contacto</NuxtLink>
  
 
</div>
</template>

<script>
  export default {
    name: 'TopNavBar',
    data() {},
    computed: {},
    mounted() {},
    methods: {}
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>


* {box-sizing: border-box;}

body {
  margin: 0;
  font-family: var(--font-family);
}

.topnav {
  overflow: hidden;
  background-color:#110557;
  color: #C0C0E0;
  height: 54px; 
  display: grid;
  grid-template-columns: repeat(24, 1fr) ;
  grid-template-rows: 1fr;
}
.topnav a,p {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  float: right;
  display: block;
  color: #ffffff;
  text-align: center;
  
  text-decoration: none;
  

}


.topnav a:hover {
  background-image: #3000ff;
  color:gold;
  border-radius: 10px;
  /* border: 1px solid;
  border-color: #ddd; */
}

.topnav a.active {
  
  background-color: #2196F3;
  color:gold;
  border-radius: 10px;
}

.topnav .main-link {
  grid-column-start: 4;
  grid-column-end:8;
  grid-row-start: 1;
  grid-row-end: 2;
  font-family: "Avenir Next LT Pro", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  float: left;
  padding: 7px;
  font-size: 30px;

}


.topnav .blog-link {
  grid-column-start: 14;
  grid-column-end: 16;
  grid-row-start: 1;
  grid-row-end: 2;
  font-family: "Avenir Next LT Pro", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  float: right;
  padding: 12px;
  font-size: 18px;
}
.topnav .about-link {
  grid-column-start: 16;
  grid-column-end: 18;
  grid-row-start: 1;
  grid-row-end: 2;
  font-family: "Avenir Next LT Pro", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  float: right;
  padding: 12px;
  font-size: 18px;
}
.topnav .contact-link {
  grid-column-start: 18;
  grid-column-end: 19;
  grid-row-start: 1;
  grid-row-end: 2;
  font-family: "Avenir Next LT Pro", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  float: right;
  background-color: #7e3a29;
  padding: 12px;
  font-size: 18px;
}









@media screen and (max-width: 600px) {
  .topnav .login-container {
    float: none;
  }
  .topnav a, .topnav input[type=text], .topnav .login-container button {
    float: none;
    display: block;
    text-align: left;
    width: 100%;
    margin: 0;
    padding: 14px;
  }
  .topnav input[type=text] {
    border: 1px solid #ccc;  
  }
}
</style>