<template>
  <v-app>
    <v-app-bar
      app
      inverted-scroll
      scroll-threshold="150"
      dark
      height="46"
    >
      <div class="d-flex align-center">
        <v-img
          alt="Catty"
          class="shrink mr-2"
          contain
          :src="`${publicPath}ficon.png`"
          transition="scale-transition"
          width="30"
        />

        
      </div>

      <v-spacer></v-spacer>

      <v-btn
        @click="$vuetify.goTo(800, {duration: 800,offset: 10, easing: 'easeOutCubic'})"
        target="_blank"
        text
      >
        <span class="mr-2 caption">Projects</span>
        <v-icon>mdi-tools</v-icon>
      </v-btn>
      <v-btn
        :href="`${publicPath}resume.pdf`"
        target="_blank"
        text
      >
        <span class="mr-2 caption">Resume</span>
        <v-icon>mdi-file-document</v-icon>
      </v-btn>
    </v-app-bar>

    <v-content>
      <Homepage/>
    </v-content>
  </v-app>
</template>

<script>
import Homepage from './components/Homepage';
export default {
  name: 'App',
  components: {
    Homepage,
    
  },

  data () {
  return {
    publicPath: process.env.BASE_URL
  }
 
}

};
</script>
