<!DOCTYPE html>

<html>

<head>

<title>IT 1000 Final Project</title>

<meta charset="utf-8">

<meta name="viewport" content="width=device-width initial-scale=1 shrink-to-fit=no">

<link rel="stylesheet" type="text/css" href="style.css">

<link rel="icon" href="favicon (6).ico">

<link href="https://fonts.googleapis.com/css2?family=Quintessential&display=swap" rel="stylesheet">

<link href="https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@100;300;400;500;700;900&display=swap"

rel="stylesheet">

<link href="https://fonts.googleapis.com/css?family=Open+Sans" rel="stylesheet" type="text/css">

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">

</head>

<body>

<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.8.2/css/all.css"

integrity="sha384-oS3vJWv+0UjzBfQzYUhtDYW+Pj2yciDJxpsK1OYPAYjqT085Qq/1cq5FLXAZQ7Ay" crossorigin="anonymous">

<div class="topnav" id="myTopnav">

<a href="#home" class="active">Home Page</a>

<a href="#about">About Me</a>

<a href="#education">My Education</a>

<a href="#hobbies">Hobbies</a>

<a href="#skills">Skills</a>

<a href="#projects">Coursework</a>

<a href="certificates.html">Certifications</a>

<a href="#contacts">Contact Me</a>
<a href="javascript:void(0);" class="icon" onclick="myFunction()">


</a>

</div>

<section>

<section class="home" id="home">

<div class="inner">

<p>IT 1000</p>

</div>

</section>

<section class="about" id="about">

<div class="inner">

<h1>About Me</h1>

<p>

I am an undergraduate at the University of Missouri

I study Biology and Psychology.

I also work at the MU Career Center as a Career Specialist and supervisor and for Cytive Lyfe Sciences as a Undergradute Campus Representative.<br>
<figure>
	<blockquote>
		<p><img src="smiley.gif" alt="Smiley face" width="42" height="42" style="border:5px solid black"></p>
	</blockquote>
</figure>

</p>

</div>

</section>

<section class="education" id="education">

<div class="inner">

<h1>Education</h1>
<p>

I attended Bowling Green High School.
</p>
<div>


</section>

<section class="hobbies" id="hobbies">

<div class="inner">

<h1> Hobbies</h1>

<div>

<p>I like playing with my dog, running, spending time with friends and traveling.</p>

</div>

</div>

</section>

<section class="skills" id="skills">

<div class="inner">

<h1>Skillls</h1>

<div>

<ul>

<li>Communication</li>

<li>Organization</li>

<li>Self-Motivated</li>

</ul>

</div>


</div>

</section>

<section id="projects" class="projects">

<div class="inner">

<h1>Coursework- Here is a coding sample and a link to learn about coding</h1>

<div>

<code>&lt;blockquote&gt;
&lt;p&gt;&lt;img src="smiley.gif" alt="Smiley face" width="42" height="42" style="border:5px solid black"&gt;&lt;/p&gt;
&lt;/blockquote&gt;</code>

</div>

<div>


<a href="https://www.w3schools.com/tags/tag_img.asp" target="_blank">

<p>Link to Source</p>

</a>

</div>

<div>


</section>

<section class="contacts" id="contacts">

<div class="inner">

<h1>Contact Me</h1>

<div class="contact-links">

<a href="https://www.linkedin.com/in/blake-meyer-577315162/" target="_blank"

class="btn contact-details"><i class="fab fa-linkedin-in"></i> LinkedIn</a>

<a href="bemk9h@mail.missouri.edu" class="btn contact-details"><i class="fas fa-at"></i> Send an email</a>


</div>

</div>

</section>

</section>

<footer class="footer">

<p>

<marquee onmouseover="this.stop();" onmouseout="this.start();" behavior="alternate">This page is created by

<span>Blake Meyer</span><sup> ©</sup>.</marquee>

</p>
    </footer>
    <script>
        function myFunction() {
            var x = document.getElementById("myTopnav");
            if (x.className === "topnav") {
                x.className += " responsive";
            } else {
                x.className = "topnav";
            }
        }
    </script>

</body>

</html>
css

@import url("https://fonts.googleapis.com/css?family=Poppins:400,500,600,700&display=swap");
body {
  margin: 0px auto;
  width: 100%;
}
.topnav {
  background-color: rgba(62, 61, 82, 0.699);
  overflow: hidden;
  position: fixed;
  float: none;
  width: 100%;
}

/* Style the links inside the navigation bar */
.topnav a {
  float: left;
  justify-content: center;
  display: block;
  color: #f2f2f2;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 18px;
  text-shadow: 3px 3px 3px rgb(22, 22, 22);
}

/* Change the color of links on hover */
.topnav a:hover {
  padding-bottom: 0;
  border-bottom: 2px solid #000;
  color: rgb(0, 0, 0);
}

/* Add an active class to highlight the current page */

/* Hide the link that should open and close the topnav on small screens */
.topnav .icon {
  display: none;
}

section {
  background-color: #4cbbb9;
}
.home {
  text-align: center;
  font-size: 48px;
  color: #ffffff;
  display: table;
  height: 100vh;
  width: 100%;
  animation: home 15s infinite;
}
@keyframes home {
  0% {
    background-color: #4b5053;
  }
  25% {
    background-color: #413e4d;
  }
  50% {
    background-color: #302d3b;
  }
  75% {
    background-color: #2e2c3f;
  }
  100% {
    background-color: #211f30;
  }
}
.inner {
  display: table-cell;
  vertical-align: middle;
}
.home .inner img {
  border-radius: 100%;
  width: 200px;
  height: auto;
  box-shadow: 0 0 100px #2c0505;
}
.home .inner p {
  color: #ffffff;
  font-size: 2.5;
  font-family: "Quintessential", cursive;
}
.about {
  background-image: url("https://i.pinimg.com/originals/51/95/eb/5195ebb8c5f9772deda82aa2937134d3.jpg");
  display: table;
  height: 100vh;
  width: 100%;
  background-size: cover;
  background-repeat: no-repeat;
}

.about .inner {
  display: table-cell;
  float: left;
  width: 60%;
  padding-top: 75px;
  padding-left: 50px;
}
.about .inner h1 {
  font-size: 40px;
  color: #fff;
}
.about .inner p {
  font-size: 25px;
  color: #f7f7f7;
  font-weight: 350;
  width: 80%;
  font-family: "Noto Sans KR", sans-serif;
  line-height: 30px;
  text-align: justify;
}
.education {
  background-color: rgb(208, 209, 203);
  display: table;
  height: 100vh;
  width: 100%;
}
.education .inner {
  padding: 50px;
}
.education h1,
.hobbies h1,
.skills h1,
.projects h1,
.contacts h1 {
  font-size: 42px;
}
.education .inner div,
.hobbies .inner div,
.skills .inner div,
.projects .inner div {
  width: 30%;
  margin-left: 5px;
  margin-right: 5px;
  float: left;
  text-align: center;
}
.education .inner div p,
.hobbies .inner div p,
.skills .inner div ul li,
.projects .inner div p {
  font-size: 21px;
}
.education .inner div img,
.hobbies .inner div img,
.projects .inner div img {
  width: 100px;
  height: auto;
}
.hobbies,
.skills,
.projects,
.contacts {
  display: table;
  height: 100vh;
  width: 100%;
}
.hobbies .inner,
.projects .inner,
.contacts .inner {
  padding: 50px;
}
.hobbies {
  background-color: #424f5a;
}
.skills {
  background-image: url("https://blog.bannersnack.com/wp-content/uploads/2016/05/Banner-Ad-Design-Examples--1200x900.png");
  background-repeat: no-repeat;
  background-size: cover;
}
.skills .inner {
  background-color: rgba(0, 0, 0, 0.8);
  padding: 50px;
  color: #fff;
}
.skills .inner div ul li {
  list-style-type: none;
  font-weight: bolder;
  padding-top: 10px;
  padding-bottom: 10px;
}
.projects {
  background-color: #000;
  background-image: linear-gradient(
    to bottom,
    rgb(230, 49, 139, 0.4),
    rgba(52, 171, 175, 1)
  );
  text-align: center;
}
.projects .inner a {
  text-decoration: none;
  color: #fff;
}
.projects .inner a :hover {
  color: rgb(1, 6, 34);
  text-decoration: underline;
  transition-duration: 1s;
}
.projects .inner > div {
  padding-top: 10px;
  border: 1px solid black;
  border-radius: 4%;
}
.btn-show-all {
  margin-top: 50px;
  font-size: 1.2rem;
  display: inline-block;
  padding: 1rem 2rem;
  border-radius: 50%;
  transition: background 0.5s ease-out;
  border-style: double;
  border-color: #000;
}

.btn-show-all:hover {
  background: #286d6d;
}
.contacts .inner {
  text-align: center;
}
.contact-links {
  display: flex;
  justify-content: center;
  width: 90%;
  margin-top: 4rem;
  flex-wrap: wrap;
}
.contact-details {
  font-size: 2rem;
  text-shadow: 1px 1px 2px #01000e;
  transition: transform 0.3s ease-out;
}

.contact-details:hover {
  transform: translateY(8px);
  color: rgb(28, 12, 66);
}
.btn {
  color: rgb(70, 66, 75);
  display: inline-block;
  padding: 1rem 2rem;
  border-radius: 30%;
  text-decoration: none;
}

footer p {
  background-color: rgb(3, 13, 32);
  color: #fff;
  font-size: 1.2em;
  padding-top: 10px;
  margin-top: 0px;
  padding-bottom: 5px;
  margin-bottom: 0px;
}
footer p span:hover {
  color: rgb(151, 116, 116);
}

/* Responsive Design */
@media (min-width: 320px) and (max-width: 767px) {
  .topnav {
    padding: 0;
    margin: 0;
    width: 100%;
    float: right;
  }
  .topnav a:not(:first-child) {
    display: none;
  }
  .topnav a.icon {
    float: right;
    display: block;
  }
  .topnav.responsive {
    position: fixed;
  }
  .topnav.responsive a.icon {
    position: absolute;
    right: 0;
    top: 0;
  }
  .topnav.responsive a {
    float: none;
    display: block;
    text-align: left;
  }
  .home .inner {
    padding-top: 100px;
  }
  .home .inner img {
    border-radius: 10%;
    width: 250px;
    height: auto;
    box-shadow: 0 0 50px #2c0505;
  }
  .about .inner {
    width: 80%;
  }
  .about .inner p {
    font-size: 20px;
    text-align: justify;
    width: 100%;
  }
  .education .inner div {
    width: 100%;
    border: 1px solid black;
    border-radius: 2%;
    padding-top: 10px;
    margin-top: 5px;
  }
  .hobbies .inner div {
    width: 100%;
    border-bottom: 1px solid black;
    border-radius: 10%;
    padding-top: 10px;
    margin-top: 5px;
  }
  .skills .inner div {
    width: 100%;
  }
  .projects .inner div {
    width: 100%;
    padding-top: 10px;
    margin-top: 5px;
  }
}
@media (min-width: 768px) and (max-width: 1023px) {
  .about .inner {
    width: 70%;
  }
  .about .inner p {
    font-size: 20px;
    text-align: justify;
    width: 100%;
  }

  .education .inner div {
    border: 1px solid black;
    border-radius: 5px;
  }
}
