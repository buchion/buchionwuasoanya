<template>
  <div>
    <div class="firstDiv">
      <h5>Buchi Onwuasoanya</h5>
      <h1>
        Full Stack
        <br />Web Developer
      </h1>

      <h3>Over the past 3 years, as a Full Stack Developer, I’ve worked with big companies and up-and-coming startups to successfully help them reach their full potential and attract new customers.</h3>
    </div>
    <div class="secondDiv">
      <h1>Projects Case Study</h1>
      <div>
        <img src="../assets/dutton.png" alt="Dutton" />
        <h3>Dutton Tea</h3>
      </div>
      <div>
        <img src="../assets/sl.png" alt="Social Lender" />
        <h3>Social Lender</h3>
      </div>
      <div>
        <img src="../assets/cooumobile.png" alt="CoouMobile" />
        <h3>Coou Mobile</h3>
      </div>
      <div>
        <img src="../assets/scanin.png" alt="ScanIn" />
        <h3>Scan In</h3>
      </div>
      <div>
        <img src="../assets/dutton.png" alt="Dutton" />
        <h3>Dutton</h3>
      </div>
      <div>
        <img src="https://tympanus.net/Development/HoverEffectIdeas/img/12.jpg" alt="img12" />
        <h3>Nigerian Tourism</h3>
      </div>
      <div>
        <img src="../assets/precredita.png" alt="Procredita" />
        <h3>Procredita</h3>
      </div>
      <div>
        <img src="../assets/mysite.png" alt="img12" />
        <h3>My Site</h3>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Home",
};
</script>

<style scoped>
.firstDiv {
  margin-top: 37vh;
  margin-bottom: 10vh;
  margin-left: 6.5vw;
}

.imagediv {
  background: url("../assets/imgbg.png");
  background-position: top;
  background-repeat: no-repeat;
  background-size: cover;
}

h5 {
  line-height: 1.25rem;
  text-transform: uppercase;
  letter-spacing: 0.6em;
  color: #878a8f;
  font-size: 1em;
}

.firstDiv h3 {
  color: #878a8f;
  line-height: 1.875rem;
  font-weight: 500;
}

.firstDiv h1 {
  font-size: 35px;
  color: #0f141e;
  width: 90vw;
}

/* SECOND DIV STYLING */
.secondDiv {
  margin-bottom: 5vh;
  background: url("../assets/divbackground.jpg");
  padding: 5vh 0 10vh 0;
  display: flex;
  flex-flow: row wrap;
  justify-content: space-evenly;
  align-items: center;
  text-align: center;
}

.secondDiv h1 {
  text-align: start;
}

.secondDiv div {
  transition: transform 0.2s;
}

.secondDiv img {
  filter: grayscale(100%);
}

/* 
  ##Device = Desktops
  ##Screen = 1281px to higher resolution desktops
*/
@media (min-width: 1281px) {
  .firstDiv h1 {
    font-size: 4em !important;
  }

  .secondDiv h1 {
    font-size: 3.3em !important;
  }

  .firstDiv h3 {
    width: 50vw;
    font-size: 1.2rem;
  }

  .secondDiv div {
    height: 20rem !important;
    width: 24rem !important;
  }
}

/* 
  ##Device = Laptops, Desktops
  ##Screen = B/w 1025px to 1280px
*/
@media (min-width: 1025px) and (max-width: 1280px) {
  .secondDiv h1,
  .firstDiv h1 {
    font-size: 60px;
    width: 60vw;
  }

  .secondDiv div {
    height: 20rem !important;
    width: 24rem !important;
  }
  .firstDiv h3 {
    font-size: 1.2rem;
  }
}

/* 
  ##Device = Tablets, Ipads (landscape)
  ##Screen = B/w 768px to 1024px
*/
@media (min-width: 768px) and (max-width: 1024px) and (orientation: landscape) {
  .secondDiv h1 {
    font-size: 45px;
    width: 60vw;
  }

  .secondDiv div {
    height: 14rem !important;
    width: 17rem !important;
  }
}

@media (min-width: 481px) and (max-width: 767px) and (orientation: landscape) {
  .secondDiv h1 {
    font-size: 45px;
    width: 60vw;
  }

  .secondDiv div {
    height: 14rem !important;
    width: 17rem !important;
  }
}

.secondDiv h3 {
  font-size: x-large;
}

.secondDiv h1 {
  font-size: 35px;
  /* font-weight: 700; */
  color: #0f141e;
  width: 90vw;
}

.secondDiv div:hover {
  box-shadow: 0 4px 8px 0 #00000033, 0 6px 20px 0 #00000030;
  transform: scale(1.05);
  z-index: 2;
}

.secondDiv img:hover {
  filter: grayscale(0%);
  z-index: 2;
}

.secondDiv img {
  width: 100%;
  height: 80%;
}

.secondDiv div {
  /* box-shadow: 0 4px 8px 0 #00000033, 0 6px 20px 0 #00000030; */
  height: 17rem;
  width: 22rem;
  opacity: 1;
  margin-bottom: 2vh;
  background: #f3f3f3;
}

.secondDiv h3 {
  margin: 0;
}
</style>
