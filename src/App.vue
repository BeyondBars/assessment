<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/challenge-1">Challenge 1</router-link> |
      <router-link to="/challenge-2">Challenge 2</router-link> |
      <router-link to="/challenge-3">Challenge 3</router-link> |
      <router-link to="/final">Final</router-link>
    </div>
    <router-view />
    <div class="i_am_bunny">
      <img
        src="https://cdn.pixabay.com/photo/2020/12/21/02/32/hide-and-seek-5848592_1280.jpg"
      />
    </div>
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
.i_am_bunny {
  width: 200px;
  height: 200px;
  float: right;
  bottom: 0px;
  right: 0px;
  position: absolute;
}
.i_am_bunny img {
  width: 100%;
}
</style>
