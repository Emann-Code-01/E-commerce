<script setup>  
import Logo from "../assets/vector.svg";
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
            <li><a href="#catalogue">catalogue</a></li>
            <li><a href="#fashion">fashion</a></li>
            <li><a href="#favorite">favorite</a></li>
            <li><a href="#lifestyle">lifestyle</a></li>
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
  height: 37px;
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
  text-transform: uppercase;
  padding: 10px 50px;
}

li {
  display: inline-block;
  list-style-type: none;
  text-decoration: none;
  padding: 1px 30px;
}

a {
  font-size: 18px;
  color: #242323;
  font-weight: 500;
  position: relative;
  line-height: auto;
  letter-spacing: 1px;
}

button:hover {
  background-color: #000000c2;
}

.sign-in {
  display: flex;
}

button {
  border: none;
  margin-left: 10px;
  margin-right: -30px;
  padding: 10px 16px;
  background-color: #000;
  border-radius: 5.25px;
  color: #ffff;
  cursor: pointer;
  font-size: 20px;
  transition: all 0.3s ease;
  top: 0;
}

@media (max-width: 768px) {
  .left {
    padding-left: 5px;
    margin-left: -30px;
  }

  .left img {
    height: 30px;
  }

  .left h1 {
    font-size: 26px;
  }

  .right {
    padding: 0px 10px;
  }

  li {
    margin-right: 13px;
    padding: 1px 8px;
  }

  a {
    font-size: 13px;
  }

  button {
    padding: 5px 12px;
    font-size: 16px;
    margin-right: -47px;
  }
}

@media (max-width: 480px) {
  .left {
    padding-left: 0px;
  }

  .right {
    padding: 0px;
  }

  li {
    margin-right: -1px;
    padding: 0px 10px;
  }

  a {
    font-size: 10px;
  }

  button {
    text-wrap: nowrap;
    padding: 0px 11px;
    font-size: 14px;
    margin-right: 0px;
  }
}
</style>
