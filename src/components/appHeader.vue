<template>
  <div class="header">
    <header class="header">
      <nav class="header-nav">
        <a class="logo" href="#home"><img src="../assets/Logo.png" /></a>  
        <div class="mobile-menu">
          <div class="line1"></div>
          <div class="line2"></div>
          <div class="line3"></div>
        </div>
        <ul class="nav-list">
          <li><a class="navQuemSomos" id="logo" href="#Time">O time</a></li>
          <li><a class="navDepoimento" id="logo" href="#Modulo">O módulo</a></li>
          <li><a class="navFundadores" id="logo" href="#Projeto">O projeto</a></li>
          <li><a class="navPlanos" id="logo" href="#Resultados">Os resultados</a></li>
          <li><a class="navContato" id="logo" href="#Insights">Insights</a></li>
        </ul>
      </nav>
    </header>
  </div>
</template>


<script>
import "@fontsource/roboto";
export default {

}
</script>

<style scoped>
* {
  margin: 0;
  padding: 0;
}

body {
  background-color: #F4f4f4;
  position: relative;
}

#logo {
  color: #18ADE0;
  text-decoration: none;
  transition: 0.3s;
  font-size: 20px;
}

#logo:hover {
  opacity: 0.7;
 color: #229679;
}


img {
  width: 100px;
  
}

.header-nav {
  display: flex;
  justify-content: space-around;
  align-items: center;
  height: 9vh;
}

.header {
  box-shadow: 0 0 0 0.20rem #18ADE0;
  background-color: #F4f4f4;
  top: 0;
  width: 100%;
  position: fixed;
  z-index: 2;
  right: 0px;
}

.nav-list {
  list-style: none;
  display: flex;
  position: relative;
}

.nav-list li {
  margin-left: 32px;
  margin-top: 10px;
  position: relative;
}




</style>