<template>
  <div>
    <Navigation />
    <form class="login">
      <h2>Login/Signup(It's Free!)</h2>
      <br />
      <input type="text" placeholder="Username" /><br />
      <input type="text" placeholder="Password" /><br />
      <input type="text" placeholder="Email" />
    </form>
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
.login {
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