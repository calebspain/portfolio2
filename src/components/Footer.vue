<template>
  <nav>
    <div class="logo">
      <p>&copy; 2020 Caleb Spain | All Rights Reserved</p>
    </div>
    <div class="menu-options">
      <p>Load More...</p>
    </div>
    <div class="social">
      <p>Download CV</p>
    </div>
  </nav>
</template>

<script>
export default {
  name: "Footer"
};
</script>

<style scoped>
nav {
  display: grid;
  grid-gap: 10px;
  grid-template-columns: 1fr 1fr 1fr;
  height: 90px;
  padding: 0px 50px;
  border-bottom: 1px solid #cdcdcd;
}

p {
  font-size: 14px;
  line-height: 30px;
  font-weight: 500;
  letter-spacing: 1px;
  color: #555;
  transition: all 0.4s ease-in-out 0s;
  text-decoration: none;
  text-transform: uppercase;
}

.menu-options {
  display: flex;
  justify-content: center;
}

.social,
.menu-options,
.logo {
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>
