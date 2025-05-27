<script setup>
import Pic from "../assets/card-pic.svg";
import Star from "../assets/star.svg";
</script>

<template>
  <div class="card">
    <div class="left-side">
      <h1>
        <span class="f1">LET<span style="font-style: italic;">'</span>S <br> </span> <span class="f2">EXPLORE</span>
        <br> <span class="f3">UNIQUE <br> </span>
        <span class="f4">CLOTHES.</span>
      </h1>
      <p>Live for Influential and Innovative fashion!</p>
      <button type="button">Shop Now</button>
    </div>
    <div class="right-side">
      <div class="st-1">
        <img :src="Star" alt="Star">
        <img :src="Star" alt="Star">
      </div>
      <div class="main-img">
        <img :src="Pic" alt="Card-Pic">
      </div>
      <div class="st-2">
        <img :src="Star" alt="Star">
        <img :src="Star" alt="Star">
      </div>
    </div>
  </div>
</template>

<style scoped>
.card {
  padding: 50px 80px;
  display: flex;
  background: #f4f6f5c7;
  height: auto;
  width: 89%;
  margin: 18px 7em;
  border-radius: 40px;
}

h1 {
  font-size: 75px;
  font-weight: 900;
  letter-spacing: 0;
  line-height: 100px;
}

.left-side {
  margin-top: 4em;
}

.f1 {
  display: flex;
  width: 68%;
  background: #FFFFFF;
  padding-left: 0.3em;
}

.f2 {
  padding-left: 0.3em;
}

.f3 {
  display: flex;
  width: 73%;
  background: #EBD96B;
  padding-left: 0.3em;
}

.f4 {
  padding-left: 0.3em;
}

p {
  font-size: 26px;
  font-weight: 400;
  letter-spacing: -1px;
  font-family: 'Poppins', sans-serif;
  padding: 15px 20px 25px 0.7em;
  text-wrap: nowrap;
}

button {
  background: #000;
  color: #fff;
  border-radius: 10px;
  padding: 15px 31px;
  font-size: 22px;
  letter-spacing: -1px;
  font-weight: 400;
  font-family: 'Poppins', sans-serif;
  margin-left: 29px;
}

button:hover {
  background-color: #000000c2;
}

.rigth-side {
  display: flex;
  max-width: 100%;
}

.main-img {
  margin-bottom: -106px;
  margin-left: 10px;
  padding: 0px;
  width: auto;
}

.st-1 {
  display: flex;
  justify-content: space-between;
  width: 100%;
}

.st-2 {
  display: flex;
  justify-content: space-between;
  width: 100%;
}

@media (max-width: 768px) {}

@media (max-width: 480px) {
  /*
  p {
    background: #FFFFFF;
    paddin
  }*/
}
</style>
