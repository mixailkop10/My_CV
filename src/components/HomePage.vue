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
            <li>
              <span class="degree"
                >Applied Informatics, 2017 University of Macedonia</span
              >
            </li>
            <li>
              <span class="thesis-title">Thesis:</span
              ><span>
                E2 ( tax declaration ) in digital form executed in Java</span
              >
            </li>
            <li>
              <span class="internship-title">Internship:</span
              ><span> Accounting Office Mr. Stavropoulos, Office Work</span>
            </li>
            <li>
              <a
                class="project-fut-title"
                href="https://github.com/mixailkop10/FundMeUp-.Net-Project"
                target="_blank"
                rel="noopener noreferrer"
                >Project Future:</a
              ><span> ReGeneration Academy of .NET (CodeHub 2020)</span>
            </li>
            <li>
              <a
                class="pfizer-boot-title"
                href="https://github.com/mixailkop10/Pfizer-Sacchon-App"
                target="_blank"
                rel="noopener noreferrer"
                >Pfizer Bootcamp:</a
              ><span> Academy of Java & Angular (CodeHub 2020)</span>
            </li>
          </ul>
        </div>
        <div class="other">
          <h1>Other</h1>
          <ul>
            <li>
              <span class="other-title">English </span
              ><span class="grade">, lvl B2</span>
            </li>
            <li>
              <span class="other-title">French </span
              ><span class="grade">, lvl B1</span>
            </li>
            <li>
              <span class="other-title">Driving License </span
              ><span class="grade">A1,B</span>
            </li>
            <li>
              <span class="other-title">Fullfilled Military Obligations</span>
            </li>
          </ul>
        </div>
      </div>
      <div class="work-exp">
        <h1>Work Experience</h1>
      </div>
      <div class="skills">
        <h1>Skills</h1>
        <div class="premier-skills">
          <ul>
            <p>Java/Restlet/Hibernate</p>
            <progress id="file" value="65" max="100"></progress>
            <p>C#/ASP.NET/MVC</p>
            <progress id="file" value="70" max="100"></progress>
            <p>Vue JS</p>
            <progress id="file" value="60" max="100"></progress>
            <p>Angular/TS</p>
            <progress id="file" value="50" max="100"></progress>
            <p>HTML/CSS</p>
            <progress id="file" value="80" max="100"></progress>
            <p>Microsoft SQL Server</p>
            <progress id="file" value="70" max="100"></progress>
            <p>Git/Version Control</p>
            <progress id="file" value="80" max="100"></progress>
          </ul>
        </div>
        <div class="secondary-skills"></div>
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
li {
  list-style-type: "➭   ";
}
p{
    font-size: 0.88rem;
}

/* LEFT DIV */
.general {
  flex: 1;
  display: flex;
  flex-direction: column;
  justify-content: space-evenly;
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
  justify-content: space-evenly;
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
.education li {
  font-size: 0.88rem;
  font-style: italic;
  text-align: left;
  margin-left: 30px;
  margin-top: 12px;
}
.degree {
  font-weight: bold;
}
.thesis-title {
  color: rgb(0, 162, 255);
}
.internship-title {
  color: rgb(0, 162, 255);
}
.project-fut-title {
  color: rgb(0, 110, 255);
  text-decoration: none;
}
.pfizer-boot-title {
  color: rgb(0, 110, 255);
  text-decoration: none;
}
.other {
  flex: 1;
  margin-bottom: 6px;
}
.other li {
  font-size: 0.88rem;
  font-style: italic;
  text-align: left;
  margin-left: 30px;
  margin-top: 12px;
}
.other-title {
  background-color: rgb(168, 222, 230);
  border-radius: 50%;
  padding: 6px;
}
.grade {
  font-family: Arial, Helvetica, sans-serif;
  font-style: oblique;
  font-weight: bold;
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
.premier-skills{
    border-bottom: 1px solid #65dfc9;
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

.social-icons a.linkedin:hover {
  background-color: #007bb6;
}

.social-icons a.github:hover {
  background-color: #333;
}
</style>