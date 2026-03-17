<template>
    <i><h1 class="heading-project">My Recent Works</h1></i>
    <i><p class="paragraph">Here you can explore my recent projects, built with modern frontend technologies and real-world use cases.</p></i>
   <div class="projects-container">

  <div class="project-card">
    <img class="project-img" src="https://i.pinimg.com/1200x/af/22/e7/af22e76e8c4ea5a51b375b7e23222317.jpg">
    <div class="project-content">
      <h3 class="project-title">Pizza  Website</h3>
      <p class="project-text">
        Responsive Pizza shop website built with Vue.js and Tailwind CSS.
      </p>
      <button class="project-btn">View Project</button>
    </div>
  </div>


  <div class="project-card">
    <img class="project-img" src="https://i.pinimg.com/736x/0b/ec/ca/0becca47cf89569f0a512c054399f47f.jpg">
    <div class="project-content">
      <h3 class="project-title">Cake & iceCream Website</h3>
      <p class="project-text">
       Cake & iceCream landing page built using Vue.js and Tailwind CSS,
      </p>
      <button class="project-btn">View Project</button>
    </div>
  </div>


  <div class="project-card">
    <img class="project-img" src="https://i.pinimg.com/736x/c8/18/d4/c818d4b68c69d72ed5b76641cafe58b7.jpg">
    <div class="project-content">
      <h3 class="project-title">Aesthetic coach website</h3>
      <p class="project-text">
        Aesthetic coach landing page built using Vue.js and Tailwind CSS,
      </p>
      <button class="project-btn">View Project</button>
    </div>
  </div>


  <div class="project-card">
    <img class="project-img" src="https://i.pinimg.com/736x/c0/37/83/c03783cbb844f4d79671f40d3fc800c5.jpg">
    <div class="project-content">
      <h3 class="project-title">Dresses Website</h3>
      <p class="project-text">
         dreses landing page built using Vue.js and Tailwind CSS,
      </p>
      <button class="project-btn">View Project</button>
    </div>
  </div>


</div>
</template>


<style scoped>
.heading-project{
  color: #ffffff;
  font-size: 30px;
  font-weight: 700;
  text-align: center;
  margin-top: 25px;
}
.paragraph{
  color: #ffffff;
  font-size: 18px;
  font-weight: 200;
  align-items: center;
  margin-left: 30%;
  margin-top: 10px;

}
 .projects-container{
display:flex;
flex-wrap:wrap;
justify-content:center;
flex-direction: row;
gap:30px;
padding:40px;
margin-top: 13px;
}

.project-card{
width:300px;
background:#ffffff;
border-radius:12px;
overflow:hidden;
box-shadow:0 8px 25px rgba(0,0,0,0.15);
transition:0.3s;
}

.project-card:hover{
transform:translateY(-10px);
box-shadow:0 40px 30px rgba(0,0,0,0.25);
}

.project-img{
width:100%;
height:320px;
object-fit:cover;
}

.project-btn {
  background-color:#ac8b90;
  border-radius:20px;
  padding:10px 20px;
  color:#11151b;
  border:2px solid #eeb0de;
  text-transform:uppercase;
  cursor:pointer;
  margin-left: 20%;
 
  
}

.project-btn:hover{
background:#111111;
color: #ffffff;
}


.project-content{
padding:20px;
}

.project-title{
font-size:20px;
font-weight:bold;
margin-bottom:10px;
margin-left: 10%;
}

.project-text{
font-size:14px;
color:#555;
line-height:1.5;
margin-bottom:15px;
margin-left: 10%;
}
 
</style>
