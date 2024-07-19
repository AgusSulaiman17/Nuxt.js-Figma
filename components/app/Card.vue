<template>
    <section class="cardselection">
        <div class="card1">
            <div class="content1">
                <div class="typo1">
                    <h3>Search Engine</h3>
                </div>
                <div class="typo1a">
                    <h3>optimazion</h3>
                </div>
                <div class="learn-more1">
                    <img src="~/assets/Icon (1).svg" alt="Logo">
                    <p>Learn more</p>
                </div>
            </div>
            <div class="foto-card1">
                <img src="~/assets/card-1.svg" alt="Logo">
            </div>
        </div>
        <div class="card2">
            <div class="content2">
                <div class="typo2">
                    <h3>Pay-per-click</h3>
                </div>
                <div class="typo2a">
                    <h3>advertising</h3>
                </div>
                <div class="learn-more2">
                    <img src="~/assets/Icon (2).svg" alt="Logo">
                    <p>Learn more</p>
                </div>
            </div>
            <div class="foto-card2">
                <img src="~/assets/card-2.svg" alt="Logo">
            </div>
        </div>
        <div class="card3">
            <div class="content3">
                <div class="typo3">
                    <h3>Social Media</h3>
                </div>
                <div class="typo3a">
                    <h3>Marketing</h3>
                </div>
                <div class="learn-more3">
                    <img src="~/assets/Icon (3).svg" alt="Logo">
                    <p>Learn more</p>
                </div>
            </div>
            <div class="foto-card3">
                <img src="~/assets/card-3.svg" alt="Logo">
            </div>
        </div>
        <div class="card4">
            <div class="content4">
                <div class="typo4">
                    <h3>Email</h3>
                </div>
                <div class="typo4a">
                    <h3>Marketing</h3>
                </div>
                <div class="learn-more4">
                    <img src="~/assets/Icon (4).svg" alt="Logo">
                    <p>Learn more</p>
                </div>
            </div>
            <div class="foto-card4">
                <img src="~/assets/card-4.svg" alt="Logo">
            </div>
        </div>
        <div class="card5">
            <div class="content5">
                <div class="typo5">
                    <h3>Content</h3>
                </div>
                <div class="typo5a">
                    <h3>Creation</h3>
                </div>
                <div class="learn-more5">
                    <img src="~/assets/Icon (2).svg" alt="Logo">
                    <p>Learn more</p>
                </div>
            </div>
            <div class="foto-card5">
                <img src="~/assets/card-5.svg" alt="Logo">
            </div>
        </div>
        <div class="card6">
            <div class="content6">
                <div class="typo6">
                    <h3>Analytics and</h3>
                </div>
                <div class="typo6a">
                    <h3>Tracking</h3>
                </div>
                <div class="learn-more6">
                    <img src="~/assets/Icon (3).svg" alt="Logo">
                    <p>Learn more</p>
                </div>
            </div>
            <div class="foto-card6">
                <img src="~/assets/card-6.svg" alt="Logo">
            </div>
        </div>
    </section>
</template>
<style>
@import url('https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@300..700&display=swap');
.cardselection {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  align-items: center;
  justify-content: center;
  width: 1240px;
  gap: 40px;
  padding-inline: 100px;
  margin-bottom: 40px;
}

.card1,
.card4 {
  display: flex;
  width: 600px;
  height: 310px;
  border-radius: 45px;
  border: 1px 0px 0px 0px;
  justify-content: space-between;
  box-shadow: 0px 5px 0px 0px #191A23;
  border: 1px solid rgba(25, 26, 35, 1);
  background: rgba(243, 243, 243, 1);
}

.content1,
.content4 {
  width: 221px;
  height: 210px;
  margin: 50px 0 50px 50px;
}

.typo1{
  width: 221px;
  height: 38px;
  gap: 10px;
  border-radius: 7px;
}
.typo4{
  width: 90px;
  height: 38px;
  gap: 10px;
  border-radius: 7px;
} 

.typo1 h3,
.typo4 h3 {
  font-family: Space Grotesk;
  font-size: 30px;
  font-weight: 500;
  line-height: 38.28px;
  text-align: left;
  margin: 0;
  text-align: center;
  border-radius: 7px;
  color: rgba(0, 0, 0, 1);
  background-color: #B9FF66;
}

.typo1a{
  width: 175px;
  height: 38px;
  gap: 10px;
  border-radius: 7px;
}
.typo4a{
  width: 161px;
  height: 38px;
  gap: 10px;
  border-radius: 7px;
} 

.typo1a h3,
.typo4a h3 {
  font-family: Space Grotesk;
  font-size: 30px;
  font-weight: 500;
  line-height: 38.28px;
  text-align: left;
  margin: 0;
  text-align: center;
  border-radius: 7px;
  color: rgba(0, 0, 0, 1);
  background-color: #B9FF66;
}

.learn-more1,
.learn-more4 {
  display: flex;
  justify-content: flex-start;
  align-items: center;
  width: 164px;
  height: 41px;
  gap: 15px;
  opacity: 0px;
  margin-top: 93px;
}

.learn-more1 p,
.learn-more4 p {
  font-family: Space Grotesk;
  font-size: 20px;
  font-weight: 400;
  line-height: 28px;
  text-align: left;
  color: rgba(0, 0, 0, 1);
}

.learn-more1 img,
.learn-more4 img {
  width: 41px;
  height: 41px;
}

.foto-card1,
.foto-card4 {
  width: 210px;
  height: 210px;
  padding: 0px 0.15px 0px 1px;
  margin: 50px 50px 0px 50px;
}

.foto-card1 img,
.foto-card4 img {
  width: 210px;
  height: 210px;
  padding: 0px 0.15px 0px 1px;
}

.card2,
.card5 {
  display: flex;
  width: 600px;
  height: 310px;
  border-radius: 45px;
  border: 1px 0px 0px 0px;
  justify-content: space-between;
  box-shadow: 0px 5px 0px 0px #191A23;
  border: 1px solid rgba(25, 26, 35, 1);
  background: rgba(185, 255, 102, 1)
}

.content2,
.content5 {
  width: 221px;
  height: 210px;
  margin: 50px 0 50px 50px;
}

.typo2{
  width: 209px;
  height: 38px;
  gap: 10px;
  border-radius: 7px;

}
.typo5 {
  width: 133px;
  height: 38px;
  gap: 10px;
  border-radius: 7px;
}

.typo2 h3,
.typo5 h3 {
  font-family: Space Grotesk;
  font-size: 30px;
  font-weight: 500;
  line-height: 38.28px;
  text-align: left;
  margin: 0;
  text-align: center;
  border-radius: 7px;
  color: rgba(0, 0, 0, 1);
  background-color: rgba(255, 255, 255, 1);
}

.typo2a{
  width: 178px;
  height: 38px;
  gap: 10px;
  border-radius: 7px;
}
.typo5a {
  width: 137px;
  height: 38px;
  gap: 10px;
  border-radius: 7px;
}

.typo2a h3,
.typo5a h3 {
  font-family: Space Grotesk;
  font-size: 30px;
  font-weight: 500;
  line-height: 38.28px;
  text-align: left;
  margin: 0;
  text-align: center;
  border-radius: 7px;
  color: rgba(0, 0, 0, 1);
  background-color: rgba(255, 255, 255, 1);
}

.learn-more2,
.learn-more5 {
  display: flex;
  justify-content: flex-start;
  align-items: center;
  width: 164px;
  height: 41px;
  gap: 15px;
  opacity: 0px;
  margin-top: 93px;
}

.learn-more2 p,
.learn-more5 p {
  font-family: Space Grotesk;
  font-size: 20px;
  font-weight: 400;
  line-height: 28px;
  text-align: left;
  color: rgba(0, 0, 0, 1);
}

.learn-more2 img,
.learn-more5 img {
  width: 41px;
  height: 41px;
}

.foto-card2,
.foto-card5 {
  width: 210px;
  height: 210px;
  padding: 0px 0.15px 0px 1px;
  margin: 50px 50px 0px 50px;
}

.foto-card2 img,
.foto-card5 img {
  width: 210px;
  height: 210px;
  padding: 0px 0.15px 0px 1px;
}

.card3,
.card6 {
  display: flex;
  width: 600px;
  height: 310px;
  border-radius: 45px;
  border: 1px 0px 0px 0px;
  justify-content: space-between;
  box-shadow: 0px 5px 0px 0px #191A23;
  border: 1px solid rgba(25, 26, 35, 1);
  background: rgba(25, 26, 35, 1);
}

.content3,
.content6 {
  width: 221px;
  height: 210px;
  margin: 50px 0 50px 50px;
}


.typo3{
  width: 197px;
  height: 38px;
  gap: 10px;
  border-radius: 7px;
}
.typo6 {
  width: 213px;
  height: 38px;
  gap: 10px;
  border-radius: 7px;
}

.typo3 h3{
  font-family: Space Grotesk;
  font-size: 30px;
  font-weight: 500;
  line-height: 38.28px;
  text-align: left;
  margin: 0;
  text-align: center;
  border-radius: 7px;
  color: rgba(0, 0, 0, 1);
  background-color: rgba(255, 255, 255, 1);
}
.typo6 h3 {
  font-family: Space Grotesk;
  font-size: 30px;
  font-weight: 500;
  line-height: 38.28px;
  text-align: left;
  margin: 0;
  text-align: center;
  border-radius: 7px;
  color: rgba(0, 0, 0, 1);
  background-color: #B9FF66;
}

.typo3a{
  width: 161px;
  height: 38px;
  gap: 10px;
  border-radius: 7px;
}
.typo6a {
  width: 138px;
  height: 38px;
  gap: 10px;
  border-radius: 7px;
}

.typo3a h3{
  font-family: Space Grotesk;
  font-size: 30px;
  font-weight: 500;
  line-height: 38.28px;
  text-align: left;
  margin: 0;
  text-align: center;
  border-radius: 7px;
  color: rgba(0, 0, 0, 1);
  background-color: rgba(255, 255, 255, 1);
}
.typo6a h3 {
  font-family: Space Grotesk;
  font-size: 30px;
  font-weight: 500;
  line-height: 38.28px;
  text-align: left;
  margin: 0;
  text-align: center;
  border-radius: 7px;
  color: rgba(0, 0, 0, 1);
  background-color: #B9FF66;
}
.learn-more3,
.learn-more6 {
  display: flex;
  justify-content: flex-start;
  align-items: center;
  width: 164px;
  height: 41px;
  gap: 15px;
  opacity: 0px;
  margin-top: 93px;
}

.learn-more3 p,
.learn-more6 p {
  font-family: Space Grotesk;
  font-size: 20px;
  font-weight: 400;
  line-height: 28px;
  text-align: left;
  color: rgba(255, 255, 255, 1);
}

.learn-more3 img,
.learn-more6 img {
  width: 41px;
  height: 41px;
}

.foto-card3,
.foto-card6 {
  width: 210px;
  height: 210px;
  padding: 0px 0.15px 0px 1px;
  margin: 50px 50px 0px 50px;
}

.foto-card3 img,
.foto-card6 img {
  width: 210px;
  height: 210px;
  padding: 0px 0.15px 0px 1px;
}

</style>