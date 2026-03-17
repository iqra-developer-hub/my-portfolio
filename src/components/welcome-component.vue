<template>
  <!-- Hero Section -->
  <div class="welcome-background welcome-img-flex">
    <div class="main-text">
      <p class="welcome-paragraph1"><i>WELCOME TO MY PORTFOLIO</i></p>
      <h1 class="welcome-heading1 typing-text">
      <i> Hi, I'm </i> <strong class="strong-name"><i>IqraKhanzadi</i></strong>
      </h1>
      <h2 class="animated-heading"><i>Frontend</i></h2>
      <h3 class="welcome-heading3"><i>Developer</i></h3>
      <p class="welcome-paragraph2">
        <i>I build modern, responsive, and user-friendly websites<br>
        Using clean and efficient code. Transforming ideas into digital reality.</i>
      </p>
      <div class="buttons-container">
        <button class="welcome-button">Html</button>
        <button class="welcome-button">Css</button>
        <button class="welcome-button">JavaScript</button>
        <button class="welcome-button">Vue.js</button>
        <button class="welcome-button">Tailwind</button>
      </div>
    </div>
    <img class="welcome-image" src="../assets/hero.png" />
  </div>

  <!-- Icon Section -->
  <div class="div1">
    <i class="fa-brands fa-html5 div1-icons"></i>
    <i class="fa-brands fa-css div1-icons"></i>
    <i class="fa-brands fa-square-js div1-icons"></i>
    <i class="fa-brands fa-vuejs div1-icons"></i>
    <i class="fa-brands fa-github div1-icons"></i>
  </div>

  <!-- About Section -->
  <div class="div2">
    <h1 class="about-heading">A Little Bit About Me</h1>
    <p class="about-paragraph">
      I am a passionate <strong class="about-heading-strong">Frontend Developer</strong> who enjoys building modern, responsive, and user-focused web experiences. My interest in web development started with a simple curiosity about how websites work, and it soon grew into a deep passion for coding.
    </p>
    <p class="about-paragraph">I continuously learn new tools and technologies to create clean, efficient, and engaging digital interfaces.</p>
  </div>

  <!-- Contact Icons -->
  <h1 class="contact-heading">Find Me On</h1>
  <div class="icons-container">
    <div class="icon-item">
      <a href="https://github.com/iqra-khanzadii" target="_blank"><i class="fa-brands fa-square-github div1-icons"></i></a>
      <span>GitHub</span>
    </div>

    <div class="icon-item">
      <a href="https://www.instagram.com/iqraKhanzadii22" target="_blank"><i class="fa-brands fa-square-instagram div1-icons"></i></a>
      <span>Instagram</span>
    </div>

    <div class="icon-item">
      <i class="fa-brands fa-square-linkedin div1-icons"></i>
      <span>LinkedIn</span>
    </div>

    <div class="icon-item">
      <i class="fa-solid fa-briefcase div1-icons"></i>
      <span>Fiverr</span>
    </div>
  </div>
</template>

<style scoped>

/* General */
*{
margin:0;
padding:0;
box-sizing:border-box;
}

body{
background-color:#795d61;
width:100%;
}

/* Welcome Section */
.background-color{
background-color:#795d61;
min-height:100vh;
padding:20px;
color:beige;
display:flex;
flex-direction:column;
justify-content:center;
}

.welcome-img-flex{
display:flex;
justify-content:space-between;
align-items:center;
gap:40px;
flex-wrap:wrap;
}

.main-text{
max-width:500px;
margin-top: 10%;
margin-left: 2%;
}

.welcome-image{
width:420px;
max-width:90%;
height:auto;
}

/* Headings & Paragraphs */

.description{
font-size:20px;
color:#ffc0cb;
line-height:1.5;
}

.welcome-heading1{
font-size:40px;
color:#f6f4e9;
margin-bottom:5px;
}

.welcome-heading2{
font-size:37px;
color:black;
margin-bottom:5px;
}

.welcome-heading3{
font-size:33px;
color:#f6f4e9;
margin-bottom:10px;
}

.welcome-paragraph2{
font-size:20px;
color:black;
margin:10px 0 20px 0;
}

/* Animated Heading */

.animated-heading{
font-size:37px;
color:black;
font-weight:600;
margin-bottom:5px;
position:relative;
overflow:hidden;
}

.animated-heading::after{
content:'';
position:absolute;
width:100%;
height:3px;
background:#0a0a0a;
bottom:0;
left:-100%;
animation:slide-in 2s forwards infinite alternate;
}

/* Buttons */

.buttons-container{
display:flex;
flex-wrap:wrap;
gap:10px;
margin-top:10px;
}

.welcome-button{
background-color:#ac8b90;
width:22%;
border-radius:20px;
padding:10px 10px;
color:#11151b;
border:2px solid #11151b;
text-transform:uppercase;
cursor:pointer;
}

.welcome-button:hover{
background-color:black;
color:#dad5d5;
box-shadow:0 10px 20px rgba(6,12,8,0.9);
}

/* Skills Icons */

.div1{
background-color:#795d61;
padding:20px;
border-radius:10px;
text-align:center;
margin-top:20px;
}

.div1-icons{
font-size:45px;
margin:10px;
color:#1f2020;
border-top:2px solid #141414;
border-bottom:2px solid black;
border-radius:10px;
box-shadow:0 10px 10px rgba(196,133,196,0.9);
}

/* About Section */

.div2{
background-color:rgb(14,13,13);
max-width:80%;
border-radius:20px;
padding:30px;
margin:40px auto 20px;
box-shadow:0 10px 20px rgba(6,12,8,0.9);
}

.about-heading{
text-align:center;
color:#be8d8d;
margin-bottom:10px;
font-weight:900;
}

.about-paragraph{
color:#f6f4e9;
font-size:20px;
margin-bottom:10px;
}

.about-heading-strong{
color:#be8d8d;
}

/* Contact Section */

.contact-heading{
text-align:center;
color:black;
font-size:35px;
margin:20px 0 10px;
}

.icons-container{
display:flex;
justify-content:center;
flex-wrap:wrap;
gap:25px;
padding-top:15px;
}

.icon-item{
display:flex;
flex-direction:column;
align-items:center;
cursor:pointer;
}

.icon-item span{
color:white;
margin-top:5px;
}

/* Typing Animation */

.typing-text{
font-size:37px;
font-weight:600;
color:black;
overflow:hidden;
white-space:nowrap;
border-right:3px solid black;
width:19ch;

animation:
typing 3s steps(19) infinite,
blink 0.3s step-end infinite;
}

@keyframes typing{
from{
width:0;
}
to{
width:19ch;
}
}

@keyframes blink{
50%{
border-color:transparent;
}
}


/* Responsive Media Queries */

/* Mobile */

@media(max-width:768px){

.welcome-img-flex{
flex-direction:column;
text-align:center;
}

.main-text,
.welcome-image{
max-width:90%;
}

.welcome-heading1{
font-size:32px;
margin-top: 2%;
}

.welcome-heading2{
font-size:30px;
}

.welcome-heading3{
font-size:26px;
}

.welcome-paragraph2{
font-size:17px;
}

.buttons-container{
flex-direction:column;
align-items:center;
}

.welcome-button{
display: inline; 

width:33%;
padding:10px 15px;
}

.div1-icons{
font-size:35px;
}

.contact-heading{
font-size:28px;
}

.heading-1{
padding-top: 10%;
}

}

/* Tablet */

@media(min-width:769px) and (max-width:1024px){

.welcome-heading1{
font-size:34px;
margin-top: 5%;
}

.welcome-heading2{
font-size:32px;
}

.welcome-heading3{
font-size:28px;
}

.welcome-button{
width:22%;
}

.div1-icons{
font-size:38px;
}
.contact-heading{
  margin-top: 9% ;
}

}

/* Desktop */

@media(min-width:1025px){

.welcome-button{
width:22%;
}
.welcome-image{
  margin-right: 10%;
}
.div1-icons{
font-size:55px;
margin-top: 5%;
}

}

</style>
