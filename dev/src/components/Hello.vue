<template>
  <div class="team-body">

    <div class="quickbar">
      <a href="#lauren">Lauren</a>
      <a href="#alvin">Alvin</a>
      <a href="#david">David</a>
    </div>



    <div class="team-members">

      <div class="team-member" id="lauren">

        <img src="/img/ohno.png"></img>
        <h2>Lauren Liu</h2>
        <div class="team-description">
          <p>Goals: I want to become a doctor</p>
          <p>Contact information:
          lliuu@neopets.com</p>
        </div>
      </div>

    </div>

    <div class="team-members">

      <div class="team-member" id="alvin">
        <img src="/img/kermit.png"></img>
        <h2>Alvin Ho</h2>
        <div class="team-description">

          <p>Goals: To own a Tesla... one day</p>
          <p>Contact information:
          google@gmail.com</p>
        </div>
      </div>

    </div>


    <div class="team-members">

      <div class="team-member" id="david">

        <img src="/img/noreply.png"></img>
        <h2>David Luu</h2>
        <div class="team-description">

        <p>Goals: I want to be done with these goons</p>
        <p>Contact information: davidluu@neopets.com </p>
        </div>
      </div>

    </div>



  </body>
</template>

<script>
export default {
  name: 'hello',
  data() {
    return {
      msg: 'Welcome to Your Vue.js App',
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
