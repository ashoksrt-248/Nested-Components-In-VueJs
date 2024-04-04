<template>
  <div id="app">
    <ComponentC />
  </div>
</template>

<script>
import ComponentC from './components/ComponentC.vue';
export default {
  name: 'App',
  components:{
    ComponentC
  },
  data(){
    return{

    }
  },
provide:{
  user:'Ashok Amara',
  employeeId: 40400060,
  company:'CBS'
}

}
</script>

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
