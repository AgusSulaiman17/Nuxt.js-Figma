<template>
    <section class="header">
            <div class="text">
                <div class="besar">
                    <h1>Navigating the digital landscape for success</h1>
                </div>
                <div class="kecil">
                    <p>Our digital marketing agency helps businesses grow and succeed online through
                        a range of services including SEO, PPC, social media marketing, and content creation</p>
                </div>
                <div class="tombol">
                    <div class="buttonn">
                        <a href="#">Book a consultation</a>
                    </div>
                </div>
            </div>
            <div class="illustration">
                <img src="~/assets/Illustration.svg" alt="Logo">
            </div>
        </section>
</template>
<style>
@import url('https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@300..700&display=swap');
 .header {
  width: 1240px;
  height: 515px;
  justify-content: space-between;
  display: flex;
  gap: 108.54px;
  padding-inline: 100px;
}

.text {
  width: 531px;
  height: 481px;
}

.besar {
  width: 531px;
  height: 231px;
}

.besar h1 {
  font-family: Space Grotesk;
  font-size: 60px;
  line-height: 76.56px;
  text-align: left;
  margin: 0;
}

.kecil {
  width: 498px;
  height: 112px;
  margin: 35px 0px;
}

.kecil p {
  font-family: Space Grotesk;
  font-size: 20px;
  font-weight: 400;
  line-height: 28px;
  text-align: left;
}

.illustration img {
  width: 600.46px;
  height: 515px;
}

.tombol {
  width: 194px;
  height: 28px;
  padding: 20px 35px 20px 35px;
  gap: 10px;
  border-radius: 14px;
  opacity: 0px;
  background: #191A23;
  ;
}

.tombol a {
  font-family: Space Grotesk;
  font-size: 20px;
  font-weight: 400;
  line-height: 28px;
  text-align: center;
  color: white;
  text-decoration: none;
}
</style>