<template>
  <footer>
    <div>
      <h3>
        Contact
        <br />information —
      </h3>
      <p>
        Feel free to reach out to me any time.
        <br />I prefer to talk over email,
        <br />especially since we may
        <br />be a few time zones away.
      </p>
      <p class="p">E: buchionwuasoanya@gmail.com</p>
      <p class="p">P: +234-818-2102-582</p>
    </div>
    <div>
      <h3>Projects —</h3>
      <li>
        <a href="https://scanin.herokuapp.com/">Scan In</a>
      </li>
      <li>Coou Mobile</li>
      <li>Spark</li>
      <li><a href="https://dutton.netlify.app/">Dutton</a></li>
      <li>All Projects</li>
    </div>
    <div>
      <h3>Latest Articles —</h3>
      <li>Couchdb, Pouchdb and Ionic</li>
      <li>Node.js on Heroku</li>
      <li>Using Pipes in Angular</li>
      <li>CI/CD using travis CI</li>
      <li>GraphQL vs Rest APIs</li>
    </div>
    <div>
      <h3>Follow me on —</h3>
      <li>
        <a href="https://github.com/buchion">Github</a>
      </li>
      <li>
        <a href="https://www.instagram.com/buch.io">Instagram</a>
      </li>
      <li>
        <a href="https://twitter.com/buchi620">Twitter</a>
      </li>
      <li>
        <a href="https://www.linkedin.com/in/buchi-onwuasoanya-1170a310a/">LinkedIn</a>
      </li>
      <li>
        <a href="https://web.facebook.com/buchi.onwuasoanya">Facebook</a>
      </li>
    </div>
  </footer>
</template>

<script>
export default {
  name: "myFooter",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
a {
  text-decoration: none;
  color: black;
}

footer {
  display: flex;
  flex-flow: row wrap;
  justify-content: space-evenly;
  align-items: center;
  border-top: 2px solid #e7e8e9;
  margin-bottom: 4vh;
}

@media (max-width: 768px) {
  footer {
    justify-content: space-between;
    padding: 0 3vw 0 3vw;
  }
}

@media (min-width: 768px) and (max-width: 1024px) {
  footer {
    justify-content: space-between;
    padding: 0 3vw 0 3vw;
  }
}

div {
  text-align: left;
  margin: 0 2vw 0 2vw;
}

ul {
  margin: 0;
}

li {
  list-style: none;
  margin-top: 1vh;
  font-size: 17px;
}

div h3 {
  color: #0f141e;
  font-weight: 800;
  font-size: 22px;
}

p {
  font-size: 17px;
}

.p {
  font-weight: bolder;
  font-size: 18px;
}
</style>
