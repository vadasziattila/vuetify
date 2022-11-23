<template>
  <v-container class="pt-15">
    <v-row>
      <v-col lg="6">
        <h2 class="intro-text">Welcome to our Vuetify App</h2>
        <p class="description">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Id cupiditate
          iusto in praesentium repudiandae ratione neque sint? Suscipit, rem
          cumque!
        </p>
        <v-btn href="https://vuetifyjs.com/en/" target="_blank" color="success" class="white--text mr-10" rounded
          >Get Started</v-btn
        >
        <v-btn href="https://youtube.com" target="_blank" color="indigo" class="white--text" rounded>
          <v-icon>mdi-play-circle</v-icon> Watch Video
        </v-btn>
      </v-col>
      <v-col lg="6">
        <img width="100%" src="./../assets/hero-img.png">
      </v-col>
    </v-row>
  </v-container>
</template>
<script>
export default {
  name: "HeroComponent",
};
</script>
<style scoped>
h2.intro-text {
  font-size: 60px;
  font-weight: bold;
  color: #444;
}
p.description {
    font-size: 19px;
    margin: 32px 0px;
    color: #444444ba;
}
</style>
