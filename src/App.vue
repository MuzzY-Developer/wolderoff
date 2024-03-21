<script setup>
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <div class="wrapper">
    <div class="text-effect-wrapper">
  <!-- The contenteditable attribute means you can type your text right on the page -->
  <h1 class="text" contenteditable>Neon</h1>
</div>

<label for="option-toggle">
  <input type="checkbox" id="option-toggle"> Version toggle
</label>

  </div>
<div>
  <a href="https:/totembosite.netlify.app/">
    <video class="movie" autoplay loop muted src="./Crayson.mp4"></video>
  </a>]
   <h4>1</h4>
  <a href="https:/totembosite.netlify.app/">
    <video class="movie" autoplay loop muted src="./Crayson.mp4"></video>
  </a>
 <h4>2</h4>
  <a href="https:/totembosite.netlify.app/">
    <video class="movie" autoplay loop muted src="./Crayson.mp4"></video>
  </a>
  <h4>3</h4>
  
</div>

   
  <RouterView />
</template>

<style>
.wrapper{
  max-width: 1440px;
   width: 100%;
 margin: 0 auto;
}
</style>
