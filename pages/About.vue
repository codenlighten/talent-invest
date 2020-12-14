<template>
  <div class="page">
    <Navigation />
    <div class="about">
      <h2>About Us</h2>
      <h2>Ipsum blah blahh....</h2>
    </div>
  </div>
</template>

<script>
import Navigation from "../components/Navigation";
export default { components: { Navigation } };
</script>

<style>
body {
  background: black;
}
.about {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  background: black;
  color: white;
}
</style>