<template>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
  <main>
    <h1>MICHAIL KOPTSIS</h1>
    <h3>Software Engineer</h3>
    <section class="glass">
      <div class="general">
        <div class="contact">
          <h1>Contact</h1>
          <span>&#9742; 6975845071</span>
          <span>&#9993; mieciel-1908@hotmail.com</span>
          <span> Analipsi, Thessaloniki</span>
          <ul class="social-icons">
                <li><a class="github" href="https://github.com/mixailkop10" target="_blank"
                        rel="noopener noreferrer"><em class="fa fa-github"></em></a></li>
                <li><a class="linkedin" href="https://www.linkedin.com/in/mkoptsis/" target="_blank"
                        rel="noopener noreferrer"><em class="fa fa-linkedin"></em></a></li>
            </ul>
        </div>
        <div class="education">
          <h1>Education</h1>
        </div>
        <div class="other">
          <h1>Other</h1>
        </div>
      </div>
      <div class="work-exp">
        <h1>Work Experience</h1>
      </div>
      <div class="skills">
        <h1>Skills</h1>
      </div>
    </section>
  </main>
  <div class="circle1"></div>
  <div class="circle2"></div>
</template>

<script>
export default {};
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
main {
  margin-top: -75px;
  min-height: 100vh;
  background: linear-gradient(to right top, #65dfc9, #6cdbeb);
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
}
.glass {
  background: white;
  min-height: 80vh;
  width: 60%;
  background: linear-gradient(
    to right bottom,
    rgba(255, 255, 255, 0.7),
    rgba(255, 255, 255, 0.3)
  );
  border-radius: 2rem;
  z-index: 2;
  backdrop-filter: blur(3rem);
  display: flex;
}
.circle1,
.circle2 {
  background: white;
  background: linear-gradient(
    to right bottom,
    rgba(255, 255, 255, 1),
    rgba(255, 255, 255, 0.5)
  );
  height: 10rem;
  width: 10rem;
  position: absolute;
  border-radius: 50%;
}
.circle1 {
  top: 5%;
  right: 15%;
}
.circle2 {
  bottom: 2%;
  left: 13%;
}
.general {
  flex: 1;
  display: flex;
  flex-direction: column;
}
.contact {
  flex: 1;
  display: flex;
  flex-direction: column;
}
.education {
  flex: 2;
}
.other {
  flex: 1;
}
.work-exp {
  flex: 2;
}
.skills {
  flex: 1;
}
/* SOCIAL */
.social-icons a {
	width: 40px;
	height: 40px;
	line-height: 40px;
	margin-left: 6px;
	margin-right: 0;
	border-radius: 100%;
	background-color: transparent
}

.social-icons {
	padding-left: 0;
	margin-bottom: 0;
    list-style: none;
    text-align: center;
}

.social-icons li {
	display: inline-block;
	margin-bottom: 4px
}

.social-icons li.title {
	margin-right: 15px;
	text-transform: uppercase;
	color: white;
	font-weight: 700;
	font-size: 13px
}

.social-icons a {
	background-color: #eceeef;
	color: #ccc;
	font-size: 16px;
	display: block;
	line-height: 44px;
	width: 44px;
	height: 44px;
	text-align: center;
	margin-right: 8px;
	border-radius: 100%;
	-webkit-transition: all .2s linear;
	-o-transition: all .2s linear;
    transition: all .2s linear;
}

.social-icons a:active,
.social-icons a:focus,
.social-icons a:hover {
	color: white;
	background-color: #29aafe
}

.social-icons.size-sm a {
	line-height: 34px;
	height: 34px;
	width: 34px;
	font-size: 14px
}

.social-icons a.linkedin:hover {
	background-color: #007bb6
}

.social-icons a.github:hover {
	background-color: #333
}

.fa{
    margin: 13px;
}
</style>