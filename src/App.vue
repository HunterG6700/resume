<template>

<div :style="myStyle" id="wrapper">
  <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link> |
    <router-link to="/resume">Resume</router-link>
  </nav>
  <router-view/>
  </div>
 
</template>

<style>
#app {
  background-color: #6e6e6e;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #000000;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #000000;
}

nav a.router-link-exact-active {
  color: #42b983;
}

body{
  background-color: #6e6e6e;
  background-image:
    linear-gradient(
        to top right, 
      rgb(19, 180, 92), #6e6e6e
      
    );}

</style>
