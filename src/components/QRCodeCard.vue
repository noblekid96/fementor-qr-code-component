<template>
  <div class="card">
    <img src="@/assets/image-qr-code.png" style="width:100%">
    <div class="container">
      <h3>Improve your front-end skills by building projects</h3>
      <p>Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
    </div>
  </div>
</template>

<script>
 export default {}
</script>

<style scoped>
 .card {
   display: flex;
   flex-flow: column;
   box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
   transition: 0.3s;
   width: 14%;
   height: max-content;
   border-radius: 10px;
   padding: 12px;
   font-family: 'Outfit';
   background-color: hsl(0, 0%, 100%);
   text-align: center;
 }

 .card:hover {
   box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
 }

 p {
   font-size: 15px;
   font-weight: 400;
   color: hsl(220, 15%, 55%);
 }

 img {
   border-radius: 10px;
 }

 .container {
   padding: 2px 16px;
 }
</style>
