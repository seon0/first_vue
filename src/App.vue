<template>
  <div id="app">
    <!--
    <HelloWorld msgs="test message"/>
    <testVue msgs="test message"/>
    <Home msgs="test message"/>
    -->
    <router-link to="/">Hello</router-link>&nbsp;&nbsp;
    <router-link to="/home">Home</router-link>&nbsp;&nbsp;
    <router-link to="/about">About</router-link>
    <router-view/>
  </div>
</template>
<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
