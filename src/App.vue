<script>
import Navbar from "./components/navbar.vue";
import sideFooter from "./components/side-footer.vue";
import hero from "./components/sections/hero.vue";
import About from "./components/sections/about.vue";
import Projects from "./components/sections/projects.vue";
import Contact from "./components/sections/contact.vue";
import Footer from "./components/footer.vue";
import Experience from "./components/sections/experience.vue";

export default {
  name: "App",
  components: {
    Navbar,
    sideFooter,
    hero,
    About,
    Experience,
    Projects,
    Contact,
    Footer,
  },
};
</script>

<template>
  <div class="too-small-max:hidden">
    <Navbar />
    <sideFooter />
    <hero class="mt-[100px] lg:mt-[150px]" />
    <About />
    <Experience />
    <Projects />
    <Contact />
    <Footer />
  </div>

  <div class="too-small-min:hidden w-1/2 h-[250px] mx-auto my-[125%]">
    <h1 class="text-main text-center text-[25px]"
      >This website is <span class="text-accent">not optimized</span> for your
      device. :(</h1
    >
  </div>
</template>

<style>
@font-face {
  font-family: Cabin;
  src: url("./assets/fonts/Cabin/Cabin-VariableFont_wdth\,wght.ttf");
}

* {
  font-family: Cabin;
  margin: 0;
  padding: 0;
  transition: all 0.25s cubic-bezier(0.645, 0.045, 0.355, 1);
}

body {
  background-color: #22333b;
}
</style>
