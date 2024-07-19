<template>
    <nav>
            <div class="logo">
                <img src="~/assets/Icon.png" alt="Logo">
                <img src="~/assets/Positivus.png" alt="Logo">
            </div>
            <ul class="wrapper-nav">
                <li><a href="#">About us</a> </li>
                <li><a href="#">Services</a></li>
                <li><a href="#">Use Cases</a> </li>
                <li><a href="#">Pricing</a></li>
                <li><a href="#">Blog</a></li>
                <div class="button"><a href="#">Reques a quote</a></div>
            </ul>
        </nav>
</template>
<style>
@import url('https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@300..700&display=swap');
nav {
  width: 1243px;
  padding-inline: 100px;
  margin-bottom: 115px;
  justify-content: space-between;
  display: flex;
  margin: 40px 0px 70px 0px;
  align-items: center;
}

.logo {
  display: flex;
  width: 219.537px;
  height: 36px;
  justify-content: center;
  align-items: center;
  gap: 12.92px;
}

.wrapper-nav {
  width: 811px;
  height: 68px;
  gap: 40px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.wrapper-nav li {
  list-style: none;
  font-family: "Space Grotesk";
}

.wrapper-nav a {
  font-size: 20px;
  font-weight: 400;
  line-height: 28px;
  text-align: left;
  text-decoration: none;
  color: black;
  font-family: "Space Grotesk";
}

.button {
  border: 1px solid #000;
  border-radius: 14px;
}

.button a {
  text-decoration: none;
  color: #000;
  font-family: "Space Grotesk";
  font-size: 20px;
  font-weight: 400;
  line-height: 28px;
  display: flex;
  padding: 20px 35px;
}
</style>