<template>
    <div class="header-container">
        <NavBar/>
        <!-- <img class="header-image" src="../static/images/mechanic-header.jpeg"> -->
        <div class="header-image"></div>
        <h1 class="title">Alf Auto Repair</h1>
        <p class="subtitle">Auto Repair & Body Shop</p>

    </div>
</template>

<script>

import NavBar from '@/components/partials/NavBar'

export default {
 

  components: {
   NavBar
  }
}

</script>

<style lang="scss">
    .header-container {
        position: relative;
        text-align: center;
    }
    .title {
        font-size: 140px;
        position: absolute;
        top: 200px;
        left: 16px;
        color: white;
        margin-left: 50px;
    }
    
    .subtitle {
        font-size: 40px;
        position: absolute;
        top: 380px;
        left: 16px;
        color: white;
        margin-left: 50px;
    }
    
    .header-image {
         display: flex;
  justify-content: center;
  align-items: center;
  width: auto;
  height: 600px;
  background-position: center;
  background-size: cover;  
  opacity: 1;
  background-image: linear-gradient(0deg, rgba(0,0,0,0.5), rgba(0, 0, 0, 0.5)), url("../static/images/mechanic-header.jpeg")
    }


</style>