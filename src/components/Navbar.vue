<template>
  <nav>
    <div class="logo">
      <a href="#">Caleb Spain</a>
    </div>
    <div class="menu-options">
      <a href="#">About Me</a>
      <a href="#">Experience</a>
      <a href="#">Education</a>
      <a href="#">Contact</a>
    </div>
    <div class="social">
      <a href="#">
        <i class="fa fa-code-fork" aria-hidden="true"></i>
      </a>
      <a href="#">
        <i class="fa fa-codepen" aria-hidden="true"></i>
      </a>
      <a href="#">
        <i class="fa fa-linkedin" aria-hidden="true"></i>
      </a>
      <a href="#">
        <i class="fa fa-instagram" aria-hidden="true"></i>
      </a>
    </div>
  </nav>
</template>

<script>
export default {
  name: "Navbar"
};
</script>

<style scoped>
nav {
  display: flex;
  align-items: center;
  justify-content: space-between;
  height: 110px;
  padding: 0px 50px;
  border-bottom: 1px solid #cdcdcd;
}

a {
  font-size: 14px;
  line-height: 30px;
  font-weight: 500;
  letter-spacing: 1px;
  color: #555;
  padding: 40px 20px;
  transition: all 0.4s ease-in-out 0s;
  text-decoration: none;
  text-transform: uppercase;
}

a:hover {
  font-weight: 600;
  color: #333;
}

.logo a {
  font-size: 22px;
  font-weight: 600;
}

.menu-options {
  display: flex;
  justify-content: center;
}
</style>
