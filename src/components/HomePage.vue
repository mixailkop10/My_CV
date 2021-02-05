<template>
  <link
    rel="stylesheet"
    href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css"
  />
  <main>
    <div class="title">
      <h1>MICHAIL KOPTSIS</h1>
      <h3>Software Engineer</h3>
    </div>
    <section class="glass">
      <div class="general">
        <div class="contact">
          <h1>Contact</h1>

          <ul class="info">
            <li><span>&#9742; 6975845071</span></li>
            <li><span> Analipsi, Thessaloniki</span></li>
          </ul>

          <ul class="social-icons">
            <li>
              <a
                class="github"
                href="https://github.com/mixailkop10"
                target="_blank"
                rel="noopener noreferrer"
                ><em class="fa fa-github"></em
              ></a>
            </li>
            <li>
              <a
                class="linkedin"
                href="https://www.linkedin.com/in/mkoptsis/"
                target="_blank"
                rel="noopener noreferrer"
                ><em class="fa fa-linkedin"></em
              ></a>
            </li>
            <li>
              <a
                class="email"
                href="mailto:mieciel-1908@hotmail.com"
                target="_blank"
                rel="noopener noreferrer"
                ><em class="fa fa-envelope"></em
              ></a>
            </li>
          </ul>
        </div>
        <div class="education">
          <h1>Education</h1>
          <ul>
              <li><span>Applied Informatics, University of Macedonia ,2017</span></li>
          </ul>
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

body {
  background: linear-gradient(to right top, #65dfc9, #6cdbeb);
}

main {
  margin-top: -75px;
  margin-bottom: 10px;
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
  width: 70%;
  background: linear-gradient(to right top, #65dfc9, #6cdbeb);
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
  right: 10%;
}
.circle2 {
  bottom: 0%;
  left: 10%;
}
.title {
  background: linear-gradient(
    to right bottom,
    rgba(255, 255, 255, 1),
    rgba(255, 255, 255, 0.5)
  );
  margin-bottom: 10px;
  border-radius: 2rem;
  padding: 8px;
}

/* APPLY TO ALL */
h1 {
  border-bottom: 1px solid #65dfc9;
  font-style: italic;
  font-family: -webkit-body;
}
h3 {
  font-style: italic;
  font-family: -webkit-body;
}
li{
    list-style-type: '➭  ';
}


/* LEFT DIV */
.general {
  flex: 1;
  display: flex;
  flex-direction: column;
  background: linear-gradient(
    to right bottom,
    rgba(255, 255, 255, 0.7),
    rgba(255, 255, 255, 0.3)
  );
  border-radius: 2rem;
}
.contact {
  flex: 1;
  display: flex;
  flex-direction: column;
}

.info li {
  font-size: 0.88rem;
  font-style: italic;
  text-align: left;
  margin-left: 30px;
  margin-top: 12px;
}
.education {
  flex: 2;
}
.other {
  flex: 1;
}
/* CENTRAL DIV */
.work-exp {
  flex: 2;
  display: flex;
  flex-direction: column;
  background: linear-gradient(
    to right bottom,
    rgba(255, 255, 255, 0.7),
    rgba(255, 255, 255, 0.3)
  );
  border-radius: 2rem;
}
/* RIGHT DIV */
.skills {
  flex: 1;
  display: flex;
  flex-direction: column;
  background: linear-gradient(
    to right bottom,
    rgba(255, 255, 255, 0.7),
    rgba(255, 255, 255, 0.3)
  );
  border-radius: 2rem;
}
/* SOCIAL */
.social-icons a {
  margin-left: 6px;
  margin-right: 8px;
  border-radius: 100%;
  background-color: transparent;
  color: rgb(139, 80, 80);
  display: block;
  width: 30px;
  height: 30px;
  line-height: 27px;
  -webkit-transition: all 0.2s linear;
  -o-transition: all 0.2s linear;
  transition: all 0.2s linear;
}

.social-icons {
  padding-left: 0;
  margin-bottom: 0;
  list-style: none;
  text-align: center;
}

.social-icons li {
  display: inline-block;
  margin-bottom: 4px;
  margin-top: 10px;
}

.social-icons a:active,
.social-icons a:focus,
.social-icons a:hover {
  color: white;
  background-color: #29aafe;
}

.social-icons.size-sm a {
  line-height: 34px;
  height: 34px;
  width: 34px;
  font-size: 14px;
}

.social-icons a.linkedin:hover {
  background-color: #007bb6;
}

.social-icons a.github:hover {
  background-color: #333;
}
</style>