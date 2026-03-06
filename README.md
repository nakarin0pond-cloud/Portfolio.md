<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Nakarin Portfolio</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial, Helvetica, sans-serif;
}

body{
background:linear-gradient(135deg,#0f2027,#203a43,#2c5364);
color:white;
}

/* NAVBAR */

nav{
display:flex;
justify-content:space-between;
align-items:center;
padding:20px 10%;
background:#0a0a0a;
}

nav h2{
color:#00eaff;
}

nav ul{
display:flex;
list-style:none;
}

nav ul li{
margin-left:25px;
}

nav ul li a{
text-decoration:none;
color:white;
font-weight:bold;
}

/* HERO */

.hero{
height:90vh;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
text-align:center;
}

.hero img{
width:170px;
height:170px;
border-radius:50%;
border:4px solid #00eaff;
margin-bottom:20px;
}

.hero h1{
font-size:40px;
margin-bottom:10px;
}

.hero span{
color:#00eaff;
}

.hero p{
margin-bottom:25px;
font-size:18px;
}

.btn{
padding:12px 30px;
background:#00eaff;
color:black;
border:none;
border-radius:25px;
font-weight:bold;
cursor:pointer;
text-decoration:none;
}

/* SECTION */

section{
padding:80px 10%;
}

.section-title{
text-align:center;
font-size:32px;
margin-bottom:40px;
color:#00eaff;
}

/* ABOUT */

.about{
max-width:800px;
margin:auto;
text-align:center;
line-height:1.7;
}

/* SKILLS */

.skills{
display:flex;
flex-wrap:wrap;
justify-content:center;
gap:20px;
}

.skill-box{
background:#111;
padding:15px 25px;
border-radius:10px;
}

/* PROJECT */

.projects{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:25px;
}

.project-card{
background:#111;
padding:20px;
border-radius:12px;
}

.project-card h3{
margin-bottom:10px;
}

.project-card a{
color:#00eaff;
text-decoration:none;
}

/* FOOTER */

footer{
text-align:center;
padding:30px;
background:#0a0a0a;
margin-top:40px;
}

</style>
</head>

<body>

<!-- NAVBAR -->

<nav>
<h2>Nakarin</h2>

<ul>
<li><a href="#about">About</a></li>
<li><a href="#skills">Skills</a></li>
<li><a href="#projects">Projects</a></li>
<li><a href="#contact">Contact</a></li>
</ul>

</nav>

<!-- HERO -->

<div class="hero">

<img src="images/pond.png" alt="profile">

<h1>Hello, I'm <span>Nakarin</span></h1>

<p>IT Student | Web Developer | Problem Solver</p>

<a class="btn" href="#projects">See My Work</a>

</div>

<!-- ABOUT -->

<section id="about">

<h2 class="section-title">About Me</h2>

<div class="about">

<p>
I am an Information Technology student at Maejo University with a passion for web development.
I enjoy building web applications that solve real-world problems and improve user experience.
</p>

<br>

<p>
My graduation project is a Community Agricultural Pre-order Website that allows users to pre-order agricultural products directly from local farmers.
</p>

</div>

</section>

<!-- SKILLS -->

<section id="skills">

<h2 class="section-title">Skills</h2>

<div class="skills">

<div class="skill-box">Java</div>
<div class="skill-box">Spring MVC</div>
<div class="skill-box">HTML</div>
<div class="skill-box">CSS</div>
<div class="skill-box">MySQL</div>
<div class="skill-box">Docker</div>
<div class="skill-box">GitHub</div>

</div>

</section>

<!-- PROJECTS -->

<section id="projects">

<h2 class="section-title">Projects</h2>

<div class="projects">

<div class="project-card">

<h3>Community Agricultural Pre-order Website</h3>

<p>
Web application for pre-ordering agricultural products from community farmers.
</p>

<br>

<p>
Tech: Java, Spring MVC, MySQL, HTML, CSS
</p>

<br>

<a href="https://github.com/786pondchannel" target="_blank">
View Project →
</a>

</div>

</div>

</section>

<!-- CONTACT -->

<section id="contact">

<h2 class="section-title">Contact</h2>

<div class="about">

<p>Email: Nakarin_p@gmail.com</p>
<p>Phone: 081-515-7121</p>
<p>Location: Chiang Rai, Thailand</p>

</div>

</section>

<footer>

<p>© 2026 Nakarin Portfolio</p>

</footer>

</body>
</html>
