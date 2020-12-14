<template>
  <div class="home">
    <Navigation />

    <div class="container">
      <div class="more">
        <div>
          <Logo />
          <h1 class="title">Talent-Invest</h1>
          <h2>The #1 Marketplace for Talent & Investors</h2>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Logo from "../components/Logo";
import Navigation from "../components/Navigation";
export default {
  components: {
    Logo,
    Navigation,
  },
};
</script>

<style>
body {
  background: black;
}
.more {
  border-radius: 30%;

  background-image: url("../images/chess.jpeg");
}

.container {
  background-image: url("../images/chess.jpeg");
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  /* background: black; */
  color: white;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: red;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
