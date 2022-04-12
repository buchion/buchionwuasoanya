<template>
<div>

  <section>
<div class="grayDiv">
  <div class="grayOuter"><img class="grayImg" src="../assets/image/teacup.png"/>
  <h4 class="projTitle">Dutton Tea</h4>
  <p>Dutton Tea is an E-Commerce (Tea only) Website built using react and redux.</p></div>


</div>
<div class="blackDiv">
 <div class="grayOuter"><img width="200px" src="../assets/image/plax-logo.png"/>
  <h4 class="projTitle blackTitle">Plax Cares</h4>
  <p class="blackTitle">PlaX enables a seamless end-to-end solution for administration of public benefits and social development initiatives.</p></div>

</div>
  </section>

  <section>

    <div class="blackDiv">
 <div class="grayOuter"><img class="img" width="50px" src="../assets/image/tribearc.png"/>
  <h4 class="projTitle blackTitle">Tribe Arc</h4>
  <p class="blackTitle">TribeArc is a community platform for Mentors, Persons of Interest, Influencers or any one interested in building and maintaining a social community world wide.</p></div>
</div>

<div class="grayDiv">
  <div class="grayOuter"><img class="img" width="260px" src="../assets/image/sllogo.png"/>
  <h4 class="projTitle">Social Lender</h4>
  <p>Social Lender is a FinTech platform that grants loans/financial aids based on the social reputation of its customers based on activities of their connected socail platforms.</p></div>
</div>

  </section>

  <section>

<div class="grayDiv">
  <div class="grayOuter">
    <!-- <img class="grayImg" src="../assets/image/teacup.png"/> -->
  <h4 class="projTitle">Coou Mobile</h4>
  <p>Coou is a Mobile platform that aids students of Anambra State University with Finding Accomodation, Exam Preparation, Events Attendance and Lots More. </p></div>
</div>

<div class="blackDiv">
  <div class="grayOuter"><img width="70px" src="../assets/image/fcmb-logo.png"/>
  <h4 class="projTitle blackTitle">FCMB Loan</h4>
  <p class="blackTitle">FCMB Loan is an Adminstrator Platform for Approving, UnderWriting and Reviewing Loans of over two hundred thousand loan Applicants.</p></div>
</div>

</section>


  <section>

<div class="blackDiv">
 <div class="grayOuter">
   <!-- <img width="200px" src="../assets/image/plax-logo.png"/> -->
  <h4 class="projTitle blackTitle">FGBMFI Mobile</h4>
  <p class="blackTitle">Full Gospel Business Men Fellowship International is a mobile platform that serve over 100,000 members of the Association Nation Wide(Nigeria)</p></div>
</div>

<div class="grayDiv">
  <div class="grayOuter">
    <!-- <img class="grayImg" src="../assets/image/teacup.png"/> -->
  <h4 class="projTitle">Scan In</h4>
  <p>Scan In is an Event enabler. With Scan in you can , Create Events and Sell tickets, buy tickets and register for events. </p></div>
</div>


  </section>


  </div>
</template>

<script>
export default {
  name: "Projects",
};
</script>

<style scoped>
@media (max-width: 706px) {
}

.grayOuter {
  margin-left: 30px;
}

.projTitle {
  font-size: 35px;
  margin-top: 0px;
  margin-bottom: 0px;
}

.blackTitle {
  color: #fff;
}

.grayImg {
  width: 100px;
}

.blackDiv {
  height: 500px;
  width: 48%;
  background-color: #211e1e;
  border: 3px solid #211e1e;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  justify-content: flex-end;
}

.grayDiv {
  height: 500px;
  width: 48%;
  border: 3px solid #211e1e;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  justify-content: flex-end;
}

section {
  display: flex;
  flex-direction: row;
  width: 100%;
  padding-left: 10px;
  padding-right: 10px;
  align-items: center;
  justify-content: space-around;
  margin-bottom: 30px;
}


.img {
  filter: grayscale(100%);
}
/* .leftProj {
  width: 100%;
  height: 380px;

  filter: grayscale(100%);
}

.rightProj {
  width: 100%;
  height: 380px;
  filter: grayscale(100%);
} */

/* .longHold {
  height: 500px;
  width: 100%;
  border: 1px solid red;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: space-between;
} */
</style>
