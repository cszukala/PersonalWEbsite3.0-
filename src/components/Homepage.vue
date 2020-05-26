<template>
  <v-container class="ma-0 pa-0" fluid>
      <v-parallax src="../assets/mana.jpg" height=800>
        <v-row
        align="center"
        justify="center"
      >
        <v-col class="text-center" cols="12">
          <h1 data-aos="fade-right" data-aos-duration="1500" class="display-1 font-weight-thin mb-4">Carter Szukala</h1>
          <h4 data-aos="fade-left" data-aos-duration="1500" class="subheading">Programmer Student  Athlete</h4>
          <v-btn data-aos="fade-left" data-aos-duration="1500" color="transparent" class="white--text" :href="`${publicPath}resume.pdf`">Resume</v-btn> 
       <v-btn data-aos="fade-left" data-aos-duration="1500" color="transparent" class="white--text" @click="$vuetify.goTo(800, {duration: 800,offset: 10, easing: 'easeOutCubic'})">Projects</v-btn> 
        </v-col>
      </v-row>
      </v-parallax>
      <v-row >
        <v-col class="text-left ma-12 col-auto" style="padding-left: 8%; padding-top: 4%;">
          <h1 data-aos="fade-right" data-aos-duration="1000" class="display-1 font-weight-thin mb-4">Plex Media Server</h1>
          <h4 data-aos="fade-left" data-aos-duration="1000" class="subheading grey--text">PROJECT</h4>
          <div class="row pa-0 ma-0">
            <div class="col-auto pa-0 pr-8">
              <h5 data-aos="fade-left" data-aos-duration="1000" >Watch for free</h5>
              <p data-aos="fade-left" data-aos-duration="1000" class="font-weight-thin caption">Tired of Netflix? <br>Make a Plex account <br>and watch now!</p>
            </div>
            <div class="col-auto pt-0 pl-0">
              <h5 data-aos="fade-left" data-aos-duration="1000" >Expand the Collection</h5>
              <p data-aos="fade-left" data-aos-duration="1000" class="font-weight-thin caption">Not have a movie? Request<br>it through a Sonarr or Radarr Server</p>
          </div>
          <div class="col-auto pt-0 pl-0">
              <h5 data-aos="fade-left" data-aos-duration="1000" >Tools Used</h5>
              <p data-aos="fade-left" data-aos-duration="1000" class="font-weight-thin caption">Docker Sonarr Radarr <br>Jackett and the usenet</p>
          </div>
          </div>

          <v-btn data-aos="fade-up" data-aos-duration="1500" text small class="pa-0 ma-0" href="https://github.com/cszukala">view on github</v-btn>
        </v-col>
        <v-col class="text-left ma-12">
          <img data-aos="fade-right" data-aos-duration="1000" style="width: 800px;" src="../assets/plex.jpg">
        </v-col>

      </v-row >
      <v-row style="background: #0f6451" align="center"
        justify="center"
      >
            <img data-aos="fade-right" data-aos-duration="1000" height=200 src="../assets/dislog.png">

        <v-col class="text-left ma-12 col-auto">
          <h4 data-aos="fade-left" data-aos-duration="1000" class="subheading grey--text">PROJECT</h4>
          <h3 data-aos="fade-left" data-aos-duration="1000" class="white--text">Matchmaking Discord Bot</h3>
          <div class="row pa-0 ma-0">
            <div class="col-auto pa-0 pr-8">
              <h5 data-aos="fade-left" data-aos-duration="1000" class="white--text">Have Friends?</h5>
              <p data-aos="fade-left" data-aos-duration="1000" class="font-weight-thin caption white--text">Activate this app on your server <br>and queue up!</p>
            </div>
            <div class="col-auto pt-0 pl-0">
              <h5 data-aos="fade-left" data-aos-duration="1000" class="white--text">Automate Automate Automate!</h5>
              <p data-aos="fade-left" data-aos-duration="1000" class="font-weight-thin caption white--text">Don't sit waiting for a reply, <br>let Queuer matchmake for you!</p>
          </div>
          </div>

          <v-btn data-aos="fade-up" data-aos-duration="1500" text small class="pa-0 ma-0 white--text" href="https://github.com/cszukala">view on github</v-btn>
        </v-col>
      </v-row>

       <v-row style="background:#ECEFF1">
        <v-col class="text-left ma-12 col-auto" style="padding-left: 8%; padding-top: 4%;">
          <h1 data-aos="fade-right" data-aos-duration="1000" class="display-1 font-weight-thin mb-4">C-SPAN Web Scaper</h1>
          <h4 data-aos="fade-left" data-aos-duration="1000" class="subheading grey--text">PROJECT</h4>
          <div class="row pa-0 ma-0">
            <div class="col-auto pa-0 pr-8">
              <h5 data-aos="fade-left" data-aos-duration="1000">Store politics</h5>
              <p data-aos="fade-left" data-aos-duration="1000" class="font-weight-thin caption">Data-horder? <br>Perfect store some videos</p>
            </div>
            <div class="col-auto pt-0 pl-0">
              <h5 data-aos="fade-left" data-aos-duration="1000" >Expand the Collection</h5>
              <p data-aos="fade-left" data-aos-duration="1000" class="font-weight-thin caption">Warning to the wise<br>Don't redistribute it's a felony</p>
          </div>
          </div>

          <v-btn data-aos="fade-up" data-aos-duration="1500" text small class="pa-0 ma-0" href="https://github.com/cszukala">view on github</v-btn>
        </v-col>
        <v-col class="text-left ma-12">
          <img width=400 data-aos="fade-right" data-aos-duration="1000" style="width: 800px;" src="../assets/data-scraping.png">
        </v-col>

      </v-row>
      <hr>

      <v-row style="background:#ECEFF1" justify="center" align="center" class="text-center">
      <v-col data-aos="fade-left" data-aos-duration="500" class="col-2">
      <a href="https://www.github.com/cszukala">
      <v-icon size=100>mdi-github</v-icon> </a>
      </v-col>
      <v-col data-aos="fade-up" data-aos-duration="500" class="col-2">
      <a :href="`${publicPath}resume.pdf`">
      <v-icon size=100 >mdi-file-document</v-icon></a>
      </v-col>
      <v-col data-aos="fade-right" data-aos-duration="500" class="col-2">
      <a href="https://www.linkedin.com/in/carter-szukala-a84b49123/">
      <v-icon size=100>mdi-linkedin</v-icon></a>
      </v-col>
      </v-row>

             

  </v-container>
</template>
<script>
  export default {
    name: 'Homepage',

    data () {
      return {
        publicPath: process.env.BASE_URL
    }
 
    },
  }
</script>
