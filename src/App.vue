<template>
  <div id="nav">
    <router-link to="/">主页</router-link> |
    <router-link to="/diary">每日</router-link>| 
    <router-link to="/about">关于</router-link> 

  </div>
  <router-view />
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #55a5c5;
    }
  }
}
</style>
