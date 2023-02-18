<template>
    <div id="start-bar">
            <button id="start-button">
            <img src="../assets/w98startButton.png" id="start-button-image">
            </button>
            <div class="status-bar" style="float: right;">
            <p class="status-bar-field" style="top: 50%;"> hour:minute:second<br>dsa</p>
            </div>
        </div>
</template>

<script lang="ts">
export default{

}
</script>
<style>
#start-bar {
    background: #c0c0c0;
    height: 2rem;
    position: absolute;
    bottom: 0px;
    left: 0;
    right: 0;
    padding: 0.2rem;
    justify-content: space-between;
    box-shadow: 0 -2px #fffdfc, 0 -4px #cce9eb;
}

#start-button-image {
  max-width: 100%;
  max-height: 100%;
  padding: 0%;
  margin: 0%;
}

#start-button {
  max-width: 40px; 
  padding: 0%; 
  
}
</style>