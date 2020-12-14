<template>
  <div class="page">
    <Navigation />
    <div class="nav"></div>
    <div class="portfolio">
      <h2>Welcome to the Portfolio</h2>
      <br />
      <h3>Coming soon...</h3>
    </div>
  </div>
</template>

<script>
import Navigation from "../components/Navigation";
export default {
  components: { Navigation },
};
</script>

<style>
body {
  background: black;
}
.portfolio {
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