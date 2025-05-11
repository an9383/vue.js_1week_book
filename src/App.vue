<template>
  <nav>
    <router-link to="/">Home</router-link> |
    <!-- <router-link to="/about">About</router-link> |
    <router-link to="/databinding">Data Binding</router-link> |
    <router-link to="/databindinghtml">Data Binding HTML</router-link> |
    <router-link to="/databindingcheckbox">Check</router-link> |
    <router-link to="/databindingcheckbox2">Check2</router-link> |
    <router-link to="/databindingradio">Radio</router-link> |
    <router-link to="/databindingattr">Attr</router-link> |
    <router-link to="/databindingbutton">Button</router-link> |
    <router-link to="/databindingclass">Class</router-link> |
    <router-link to="/databindingstyle">Style</router-link> |
    <router-link to="/databindinglist">List</router-link> |
    <router-link to="/renderingvif">VIf</router-link> |
    <router-link to="/eventclick">eventclick</router-link> |-->
    <router-link to="/eventchange">eventchange</router-link> |
  </nav>
  <router-view/>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
