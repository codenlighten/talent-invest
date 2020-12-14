<template>
  <div class="navigation">
    <button><a href="./register"> Register</a></button>
    <button><a href="./portfolio"> Portfolio</a></button>
    <button><a href="./about"> About</a></button>
    <button><a href="./contact"> Contact</a></button>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
a {
  text-decoration: none;
  color: #111112;
  font-weight: bold;
}
button {
  background: #0593ff;
  background-image: -webkit-linear-gradient(top, #0593ff, #1019c9);
  background-image: -moz-linear-gradient(top, #0593ff, #1019c9);
  background-image: -ms-linear-gradient(top, #0593ff, #1019c9);
  background-image: -o-linear-gradient(top, #0593ff, #1019c9);
  background-image: linear-gradient(to bottom, #0593ff, #1019c9);
  -webkit-border-radius: 28;
  -moz-border-radius: 28;
  border-radius: 28px;
  font-family: Arial;
  color: #ffffff;
  font-size: 14px;
  padding: 10px 20px 10px 20px;
  text-decoration: none;
}

button:hover {
  background: #893cfc;
  background-image: -webkit-linear-gradient(top, #893cfc, #3444d9);
  background-image: -moz-linear-gradient(top, #893cfc, #3444d9);
  background-image: -ms-linear-gradient(top, #893cfc, #3444d9);
  background-image: -o-linear-gradient(top, #893cfc, #3444d9);
  background-image: linear-gradient(to bottom, #893cfc, #3444d9);
  text-decoration: none;
}
.navigation {
  display: flex;
  justify-content: space-around;
  background: black;
  flex-direction: row;
  color: white;
  margin: 10px;
}
</style>