<template>
  <main>
    <h1>MICHAIL KOPTSIS</h1>
    <h3>Software Engineer</h3>
    <section class="glass"></section>
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
  background: linear-gradient(to right top, #65dfc9, #6cdbeb);
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
</style>