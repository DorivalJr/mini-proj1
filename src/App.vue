<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/quem">Quem sou eu</router-link> |
      <router-link to="/oque">O que eu faço</router-link> |
      <router-link to="/hobbies">Meus hobbies</router-link> |
    </div>
    <router-view />
    <div id="foot">
    <h3>Redes Sociais</h3>
    <ul>
      <li>
        <a href="https://www.linkedin.com/in/dorivalcamargojr/" target="_blank" rel="noopener"><img src="./assets/linkedin.png" width="45" height="45" border="0"></a>
      </li>
      <li>
        <a href="https://www.facebook.com/dorivalcamargojr" target="_blank" rel="noopener"> <img src="./assets/facebook.png" width="45" height="45" border="0"></a>
      </li>      
      <li>
        <a href="https://www.instagram.com/dorivalcamargojr/" target="_blank" rel="noopener"><img src="./assets/instagram.png" width="45" height="45" border="0"></a>
      </li>      
    </ul>
    </div>    
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #346be0;
}
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
</style>
