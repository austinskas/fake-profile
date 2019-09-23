<template>
<div>
  <AppHeader />
  <RouterView />
  <Footer class="AppFooter">© 2019 Arnas Austinskas </Footer>
</div>
</template>

<script>
import AppHeader from '@/components/AppHeader'
import AppFooter from '@/components/AppFooter'


export default {
  name: 'App',
  components: {
    AppHeader,
    AppFooter,
  }
}
</script>
    
  


<style lang="scss">

body {
  background-color:#EEEFF3;
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
#nav {
  padding: 10px;
  background-color:#3252E5;
  height:469px;
  text-align: right;

  
  a {
    font-weight: 400;
    margin:8px;
    font-size:16px;
    color: #ffffff;
    &.router-link-exact-active {
      color: #42b983;
      
    }
  }
}

  

</style>
