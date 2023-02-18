<template>
  <label>content</label>
  <Taskbar></Taskbar>
</template>

<script lang="ts">
import Taskbar from './components/Taskbar.vue';

export default {
    components: { 
      Taskbar,
    },
    data(){
      return{

      };
    }
}

</script>

<style>
#app {
  background-color: #008080; 
  position: absolute;
  top: 0px;
  bottom: 0px;
  left: 0px;
  right: 0px;
}
</style>
