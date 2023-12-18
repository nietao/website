<!--
 * @Author: 聂涛
 * @Date: 2023-12-18 15:36:27
 * @LastEditors: 聂涛
 * @LastEditTime: 2023-12-18 15:57:39
 * @Description:
-->
<template>
  <router-view/>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
