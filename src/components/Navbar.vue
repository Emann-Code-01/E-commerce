<script setup>
import Logo from "../assets/logo.svg";
</script>

<template>
  <nav>
    <div class="nav-bar">
      <div class="left">
        <img :src="Logo" alt="Page Logo" />
        <h1>FASHION</h1>
      </div>
      <div class="right">
        <div class="link">
          <ul>
            <li><a href="#home">catalogue</a></li>
            <li><a href="#about">fashion</a></li>
            <li><a href="#services">favorite</a></li>
            <li><a href="#contact">lifestyle</a></li>
          </ul>
        </div>
        <div class="sign-in">
        <button type="button">SIGN UP</button>
        </div>
      </div>
    </div>
  </nav>
</template>

<style scoped>
nav {
  max-width: 100%;
}

.nav-bar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  color: #000;
  font-family: 'Poppins', sans-serif;
  height: 100%;
  width: 100%;
  border: none;
  padding: 30px 66px;
}

.left {
  display: flex;
  justify-content: flex-start;
  gap: 10px;
  padding-left: 14px;
}

.left img {
  padding-top: 11px;
  height: 42px;
  width: auto;
}

.left h1 {
  font-size: 33px;
  font-weight: 900;
  letter-spacing: 3%;
}

.right {
  display: flex;
  justify-content: flex-end;
  align-items: center;
  gap: 1px;
  text-transform: uppercase;
  padding: 10px 50px;
}

li{
  display: inline-block;
  list-style-type: none;
  text-decoration: none;
  padding: 1px 30px;
}

a{
  font-size: 18px;
  color: #242323;
  font-weight: 500;
  position: relative;
  line-height: auto;
  letter-spacing: 1%;
}

.sign-in {
  display: flex;
}

button {
  border: none;
  margin-left: 10px;
  margin-right: -30px;
  padding: 11px 14px;
  background-color: #000;
  border-radius: 5.25px;
  color: #ffff;
  cursor: pointer;
  font-size: 20px;
  transition: all 0.3s ease;
  top: 0;
}

@media (min-width: 1024px) {
  
}
</style>
