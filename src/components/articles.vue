<template>
  <div>
    <h2>
      <span>Articles</span>
    </h2>
    <section>
      <a href class="panel_with_image">
        <div class="photo_wrap">
          <img
            class="photo"
            src="https://cdn-media-1.freecodecamp.org/images/1*zuVag9ipdXYb-A4ojT_FxQ.png"
            alt
          />
        </div>
        <span class="heading">CI/CD using travis CI</span>
        <p>Continuous Integration and Continuous Deployment using Github and Travis CI.</p>
      </a>
      <a href class="panel_with_image">
        <div class="photo_wrap">
          <img class="photo" src="https://miro.medium.com/max/963/1*IaLvSnns9WRO1rmfA_ReFQ.png" alt />
        </div>
        <span class="heading">CouchDB perks and features</span>
        <p>and why it should be considered in your next offline Project.</p>
      </a>
      <a href class="panel_with_image">
        <div class="photo_wrap">
          <img
            class="photo"
            src="https://images.prismic.io/digitalocean/21ab4275-bcf3-42ac-b148-6f81d516ca1d_Twitter_graphic.png?auto=compress,format&amp;rect=0,61,1024,387&amp;w=370&amp;h=140"
            alt
          />
        </div>
        <span class="heading">GraphQL vs Rest APIs</span>
        <p>Comparing the advantages and disadvantages of Both APIs.</p>
      </a>
    </section>
  </div>
</template>

<script>
export default {
  name: "articles",
};
</script>

<style scoped>
h2 {
  width: 100%;
  text-align: center;
  border-bottom: 1px solid #c5c7cf;
  line-height: 0.1em;
  margin: 10px 0 20px;
}

h2 span {
  background: #f3f3f3;
  padding: 0 10px;
}
a {
  text-decoration: none;
}
.panel_with_image .heading {
  border-top: 1px solid #c5c7cf;
  font-weight: 800;
  color: #031b4e;
  display: inline-block;
  font-size: 15px;
  min-width: auto !important;
  padding: 25px 0 10px;
  text-transform: uppercase;
  transform: scale(1, 1.2);
  -webkit-transform: scale(1, 1.2); /* Safari and Chrome */
  -moz-transform: scale(1, 1.2); /* Firefox */
  -ms-transform: scale(1, 1.2); /* IE 9+ */
  -o-transform: scale(1, 1.2); /* Opera */
}
p {
  font-size: 20px;
  line-height: 30px;
}

.photo {
  -o-object-fit: cover;
  height: 9em;
  width: 100%;
  object-fit: cover;
}

.panel_with_image {
  background-color: #fff;
  border-radius: 3px;
  -webkit-box-shadow: 0 2px 4px rgba(1, 14, 40, 0.05);
  box-shadow: 0 2px 4px rgba(1, 14, 40, 0.05);
  color: #5b6987;
  display: block;
  margin: 15px;
  overflow: hidden;
  /* padding: 140px 30px 30px; */
  position: relative;
  text-align: center;
  transition: box-shadow 0.25s linear, -webkit-box-shadow 0.25s linear;
  width: 370px;
}

section {
  display: -ms-flexbox;
  display: flex;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  -ms-flex-pack: center;
  justify-content: center;
  padding: 20px;
}

@media (min-width: 1230px) {
  section {
    padding-left: calc(50% - 600px);
    padding-right: calc(50% - 600px);
  }
}
</style>
