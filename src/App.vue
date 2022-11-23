<template>
  <v-app>
    <Header />
    <v-main>
      <HeroComponent />
      <AboutUs />
      <Portfolio />
    </v-main>
  </v-app>
</template>

<script>
import Header from "./components/Header";
import HeroComponent from "./components/HeroComponent";
import AboutUs from "./components/AboutUs";
import Portfolio from "./components/Portfolio";

export default {
  name: "App",
  components: { HeroComponent, Header, AboutUs, Portfolio },

  data() {
    return {
      menus: [
        { title: "Home", route: "home" },
        { title: "About Us", route: "about-us" },
        { title: "Portfolio", route: "portfolio" },
        { title: "Project", route: "project" },
        { title: "Contact", route: "contact" },
      ],
    };
  },
};
</script>
<style scoped>
::v-deep .v-application--wrap {
  min-height: fit-content;
}
</style>
