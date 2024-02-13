<template>
 
  <hello-world v-slot:bottomSlot>'Hello!'</hello-world>
</template>

<style>
  #app {
    width: 300px;
  }
</style>     
<script>
import Helloworld from './components/Helloworld.vue';
export default{
  components : {
    'hello-world' : Helloworld,

  }
}
</script>
