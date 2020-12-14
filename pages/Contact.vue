<template>
  <div class="page">
    <Navigation />

    <div class="contact">
      <h2>Contact Us</h2>
      <form>
        <input type="text" placeholder="Name" /><br />
        <input type="text" placeholder="email" /><br />
        <textarea type="text" placeholder="What's On Your Mind?" /><br />
        <input type="submit" />
      </form>
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
.contact {
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