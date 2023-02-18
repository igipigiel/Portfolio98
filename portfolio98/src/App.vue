<template>
  <AppIcon></AppIcon>
  <Taskbar></Taskbar>
</template>

<script lang="ts">
import Taskbar from './components/Taskbar.vue';
import AppIcon from './components/AppIcon.vue';

export default {
    components: { 
      Taskbar,
      AppIcon,
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
