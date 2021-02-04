<template>
  <main>
    <h1>MICHAIL KOPTSIS</h1>
    <h3>Software Engineer</h3>
    <section class="glass">
        <div class="general">
            <div class="contact">
                <h1>Contact</h1>
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
  z-index: 2 ;
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
.general{
    flex: 1;
}
.work-exp{
    flex: 2;
}
.skills{
    flex: 1;
}
</style>