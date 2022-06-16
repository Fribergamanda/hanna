
<template>
  <div id="app">
    <nav>
      <router-link to="/">Home</router-link> |
      <router-link to="/work">Work</router-link> |
      <router-link to="/contact">Contact</router-link>
    </nav>
    <router-view/>
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background-color: rgba(0, 255, 255, 0.045);
  padding-bottom: 20px;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50ad;
}

nav a.router-link-exact-active {
  color: #000000;
}
</style>
