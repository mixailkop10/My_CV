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
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    background: linear-gradient(to right top, #65dfc9, #6cdbeb);
}
main {
  min-height: 100vh;
  background: linear-gradient(to right top, #65dfc9, #6cdbeb);
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
}
.glass{
    background: white;
    min-height: 80vh;
    width: 60%;
}
</style>