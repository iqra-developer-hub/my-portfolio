<template>
    <!-- Footer -->
  <div class="footer">
    <h2 class="h2-footer">© 2026 IqraKhanzadi | Frontend Developer. All rights reserved.</h2>
    <p class="p">Built with  and Vue.js & Tailwind CSS.</p>
  </div>
</template>

<style>


/* Footer */
.footer{
  background-color:black;
  width:100%;
  padding:20px;
  text-align:center;
  font-size:16px;
  color:white;
  border-radius:10px;
  margin-top:30px;
}


 .h2-footer{
    color: rgb(255, 255, 255);
    font-size: 14px;
    margin-left: 20px;
 }
 .p{
  color:white;
  font-size: 12px;
  text-align: center;
  padding: 8px;
 }


  
  html, body{
    height:100%;
    margin:0;
}

body{
    display:flex;
    flex-direction:column;
}


  #app{
  min-height:100vh;
  display:flex;
  flex-direction:column;
}

main{
  flex:1; 
}
</style>

