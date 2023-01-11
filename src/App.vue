<template>
  <div id="app">
    <router-view />
  </div>
</template>

<style>
/* global style */
body {
  -ms-overflow-style: none;
  /* IE, Edge */
  scrollbar-width: none;
  /* Firefox */
  margin: 0;
}
          
body::-webkit-scrollbar {
  display: none;
}
          
* {
  box-sizing: border-box;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
