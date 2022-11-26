<script>
 import QRCodeCard from './components/QRCodeCard.vue'

 export default {
   components: {
     QRCodeCard
   }
 }
</script>

<template>
  <div class="content">
    <QRCodeCard/>
  </div>
  <div class="attribution">
    Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>.
    Coded by <a href="#">Cheow Fu</a>.
  </div>
</template>

<style scoped>
.content {
   height: 100vh;
   display: flex;
   align-items: center;
   justify-content: center;
   background-color: hsl(212, 45%, 89%);
 }

 .attribution {
   position: absolute;
   left: 0;
   bottom: 0;
   width: 100%;
   color: black;
   font-size: 11px;
   text-align: center;

 }

 .attribution a {
   color: hsl(228, 45%, 44%);
 }

   /* .attribution { font-size: 11px; text-align: center; } */
   /* .attribution a { color: hsl(228, 45%, 44%); } */
</style>
