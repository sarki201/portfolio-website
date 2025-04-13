<template>
  <!-- Header -->
  <Heading tempID="projects" heading="Projects" headingNum="03"></Heading>

  <!-- Place Special Tiles Here </ -->
  <div class="h-full mx-auto w-full max-w-screen-xl">
    <Tile
      special="true"
      title="SKICO E-Commerce"
      description="A zero framework e-commerce platform"
      :languages="['HTML', 'CSS', 'JavaScript', 'PHP']"
      gitLink="https://github.com/sarki201/skico-e-commerce"
      exLink="https://skico-e-commerce.vercel.app"
      imageURL="/images/skico.png"
    ></Tile>

    <Tile
      flip="true"
      special="true"
      title="MERN-Stack Chat App"
      description="A fully functioning web chat application, built using the MEAN tech stack."
      :languages="[
        'React',
        'NodeJS',
        'MongoDB',
        'Express',
        'socket.io',
        'Cloudinary',
      ]"
      gitLink="https://github.com/sarki201/mernstack-chatapp"
      exLink="https://mernstack-chatapp-hwxt.onrender.com"
      imageURL="/images/chat-app.png"
    ></Tile>

    <Tile
      special="true"
      title="Custom Random Number"
      description="A powerful and flexible random number generator package."
      :languages="['JavaScript', 'TypeScript', 'NodeJS']"
      gitLink="https://github.com/sarki201/custom-random-number"
      exLink="https://www.npmjs.com/package/custom-random-number"
      imageURL="images/custom-random-number.png"
    ></Tile>

    <Tile
      flip="true"
      title="Portfolio Website"
      description="My personal portfolio website"
      :languages="['VueJS', 'Vite']"
      gitLink="https://github.com/"
      exLink="/"
      imageURL="images/portfolio-website.png"
    ></Tile>
  </div>

  <!-- /> Place Normal Tiles Here -->

  <!-- Other Projects -->
  <div class="w-2/3 h-auto rounded-lg mx-auto mb-50px z-0">
    <h1 class="text-main text-center text-[25px]"
      >The rest of my projects can be found on
      <a
        class="hover:text-main text-accent"
        href="https://www.github.com/sarki201"
        target="_blank"
        >my GitHub Profile.</a
      ></h1
    >
  </div>
</template>

<script>
import Heading from "../heading.vue";
import Tile from "../tile.vue";

export default {
  name: "projects",
  components: {
    Heading,
    Tile,
  },
};
</script>
