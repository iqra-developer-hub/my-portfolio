<template>
<header class="header h1 header">

  <h1 class="logo logo:hover"><i class="fa-solid fa-laptop"></i><strong class="strong-name"><i>Iqra</i></strong><i>Khanzadi</i></h1>
  <!-- Hamburger -->
<div class="hamburger" @click="toggleMenu">
<span></span>
<span></span>
<span></span>
</div>
  <nav :class="['nav-links', { active: menuOpen }]">
    <RouterLink class="header-nav-pages " to="/"><i class="fa-regular fa-house"></i><i> Home </i></RouterLink>
    <RouterLink class="header-nav-pages " to="/Project"><i class="fa-brands fa-trello"></i><i>My Projects </i></RouterLink>
     <RouterLink class="header-nav-pages " to="/About"><i class="fa-solid fa-circle-info"></i><i>About me </i></RouterLink>
    <RouterLink class="header-nav-pages" to="/Resume"><i class="fa-regular fa-file"></i><i>Resume </i></RouterLink>
  </nav>

</header>
</template>

<script setup>
import { ref } from "vue"

const menuOpen = ref(false)

function toggleMenu(){
menuOpen.value = !menuOpen.value
}
</script>

<style scoped>
/* Header */
.header{
  width:100%;
  background-color: #795d61; 
  padding: 15px 10px;
  display:flex;
  justify-content: space-between;
  align-items:center;
  box-shadow:0 10px 35px #070707;
  border-bottom:2px solid #6e5757;
  flex-wrap: wrap;
  position:sticky; 
  top:0;
}
.logo{
  color:black;
  font-size:30px;
  font-weight:600;
}
.header-nav-pages{
  color: rgb(221,210,210);
  text-decoration:none;
  padding-left:15px;
  font-size:18px;
  font-weight:600;
}
.header nav a:hover{
  color:#d4c7c7;
  font-weight:900;
  text-decoration: underline;
}

.strong-name{
  color:rgb(236, 236, 221);
}
.nav-links{
display:flex;
gap:25px;
}

.nav-item{
color:#f7f1f1;
text-decoration:none;
font-size:18px;
transition:0.3s;
}

.nav-item:hover{
color:#d4af37;
}
/* Hamburger */
.hamburger{
display:none;
flex-direction:column;
cursor:pointer;
gap:5px;
}

.hamburger span{
width:25px;
height:3px;
background: white;
}
/* Mobile */

@media (max-width:768px){

.nav-links{
display:none;
flex-direction:column;
position:absolute;
top:70px;
right:0;
background:#000;
width:200px;
padding:20px;
}

.nav-links.active{
display:flex;
}

.hamburger{
display:flex;
}

}
@media (min-width:768px){

.hero-content-container{
max-width:85%;
gap:15px;
}

}
</style>