<template>
  <div class="">
    
      <!-- <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> -->
      <nav class="navbar navbar-dark" style="background-color:#026aa7">
        <span>
          <i class="fas fa-home"></i>
          <span><i class="fas fa-chalkboard"></i>Boards</span>
        </span>
        Trello
        <span>
          <i class="fas fa-plus"></i>
          <i class="fas fa-exclamation-circle"></i>
          <i class="far fa-bell"></i>
        </span>
      </nav>
    <router-view />
  </div>
</template>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
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
  color: #42b983;
}
</style>
