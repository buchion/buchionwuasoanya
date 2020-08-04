<template>
  <div class="divBig">
    <Home />
    <backGround />
    <articles />
    <myFooter />
  </div>
</template>

<script>
import Home from "./components/home.vue";
import backGround from "./components/background";
import articles from "./components/articles";
import myFooter from "./components/footer";

export default {
  name: "App",
  components: {
    Home,
    backGround,
    articles,
    myFooter,
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css?family=Montserrat:300,400,500,600,700,800");

html,
body {
  background-color: #f3f3f3;
  font-family: "Montserrat", sans-serif;
}

html {
  overflow: auto;
}

.divBig {
  height: 1000px;
}

/* Scrollbar Styling */
::-webkit-scrollbar {
  width: 10px;
}

::-webkit-scrollbar-track {
  background-color: #ebebeb;
  -webkit-border-radius: 10px;
  border-radius: 10px;
  margin: 5px 0 10px 0;
}

::-webkit-scrollbar-thumb {
  -webkit-border-radius: 10px;
  border-radius: 10px;
  background: #504f4f;
}
</style>
