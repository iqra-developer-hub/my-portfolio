<template>
  <h1 class="heading-1"><i>Get to Know Me!</i></h1>

  <p class="para-1">
    I’m <strong class="strong-white">IQRA,</strong> a passionate Frontend 
    <strong class="strong-white"> Developer </strong> from Pakistan, dedicated to crafting clean,
    <strong class="strong-white">responsive,</strong> and user-friendly websites using modern web technologies.
    I thrive on <strong class="strong-white">solving problems,</strong> learning new tools, and
    <strong class="strong-white">transforming</strong> ideas into seamless
    <strong class="strong-white">digital experiences.</strong>
  </p>

  <p class="para-2">
    <i>“Hard work turns potential into success, even when talent falls short.”</i>
  </p>

  <h1 class="heading-1"><i>Professional Skillset</i></h1>

  <div class="buttons-container">
    <button class="button">JavaScript (ES6+)</button>
    <button class="button">HTML5 & CSS3</button>
    <button class="button">Tailwind CSS</button>
    <button class="button">Vue.js</button>
    <button class="button">Git & GitHub</button>
    <button class="button">Responsive Design</button>
  </div>

  <h1 class="heading-1"><i>Technologies I Work With</i></h1>

  <div class="buttons-container">
    <button class="button-2">Visual Studio Code</button>
    <button class="button-2">Git & GitHub</button>
    <button class="button-2">Windows</button>
    <button class="button-2">Browser DevTools</button>
  </div>
</template>

<style scoped>
/* Headings & Paragraphs */
.heading-1 {
  color: rgb(238, 228, 228);
  font-size: 33px;
  font-weight: 600;
  text-align: center;
  /* margin-top: 10%; */
  margin: 40px 0 20px;
}

.para-1 {
  color: #0c0c0c;
  font-size: 20px;
  font-weight: 500;
  text-align: center;
  margin: 15px auto;
  padding: 0 15px;
}

.para-2 {
  color: #111111;
  font-size: 20px;
  font-weight: 540;
  text-align: center;
  margin: 10px auto 30px auto;
}

/* BUTTON CONTAINER */
.buttons-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 15px;
  margin: 20px auto 40px;
  padding: 0 10px;
}

/* BUTTON STYLES */
.button,
.button-2 {
  height: 50px;
  padding: 10px 15px;
  text-transform: uppercase;
  cursor: pointer;
  border-radius: 23px;
  flex: 1 1 150px; /* responsive width */
  max-width: 200px;
  text-align: center;
}

.button {
  color: black;
  border: 2px solid #df97a4;
  background-color: #a88389;
}

.button-2 {
  color: black;
  border: 2px solid #df97a4;
  background-color: #ac8b90;
}

/* Hover Effects */
.button:hover,
.button-2:hover {
  border: 2px solid black;
  color: black;
  box-shadow: 0 10px 10px rgba(0, 0, 0, 0.5);
}

/* Strong Colors */
.strong-white {
  color: rgb(210, 214, 214);
}

.strong {
  color: rgb(23, 23, 34);
}

/* MEDIA QUERIES */

/* Small screens (up to 480px) */
@media (max-width: 480px) {
  .heading-1 {
    font-size: 25px;
    margin: 30px 0 15px;
  }
  .para-1,
  .para-2 {
    font-size: 16px;
  }
  .button,
  .button-2 {
    flex: 1 1 100%;
    max-width: 90%;
    padding: 10px;
  }
}

/* Tablets (481px - 768px) */
@media (max-width: 768px) {
  .heading-1 {
    font-size: 28px;
  }
  .para-1,
  .para-2 {
    font-size: 18px;
  }
  .button,
  .button-2 {
    flex: 1 1 45%;
    max-width: 160px;
    padding: 10px;
  }
}
/* tablet */
@media (min-width: 768px) {
  .heading-1 {
    font-size: 28px;
  }
  .para-1,
  .para-2 {
    font-size: 18px;
  }
  .button,
  .button-2 {
    flex: 1 1 45%;
    max-width: 160px;
    padding: 10px;
  }
}
/* TABLET SCREENS (768px – 1024px) */
@media (min-width: 768px) and (max-width: 1024px) {
  .heading-1 {
    font-size: 50px;
    margin-top: 10%;
    padding: 0%;
   
  }
  .para-1,
  .para-2 {
    font-size: 30px;
     margin-top: 8% ;
  }
  .buttons-container,
  .buttons-container2 {
    justify-content: center;
    margin-top: 20% ;
    margin-bottom: 20%; 
    /* gap: 15px; */
  }
  .button,
  .button-2 {
    flex: 1 1 20%;
    max-width: 200px;
    padding: 10px;
    margin-bottom: 9%;
  }
}


/* LAPTOP / DESKTOP SCREENS (1025px – 1199px) */
@media (min-width: 1025px) and (max-width: 1199px) {
  .heading-1 {
    font-size: 32px;
  }
  .para-1,
  .para-2 {
    font-size: 20px;
  }
  .button,
  .button-2 {
    flex: 1 1 30%;
    max-width: 180px;
    padding: 12px 15px;
  }
}

/* EXTRA LARGE SCREENS (1200px+) */
@media (min-width: 1200px) {
  .heading-1 {
    font-size: 33px;
  }
  .para-1,
  .para-2 {
    font-size: 20px;
  }
  .button,
  .button-2 {
    flex: 1 1 22%;
    max-width: 200px;
    padding: 12px 20px;
  }
}
</style>