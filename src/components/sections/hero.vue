<template>
  <!-- Hero Section Container -->
  <div
    class="nav-sm:w-[80%] ssm:w-[85%] mx-auto w-2/3 flex flex-col text-main h-full max-w-screen-xl"
  >
    <!-- TypeWriter -->
    <TypeWriter></TypeWriter>

    <!-- Header -->
    <p
      class="flex flex-col select-none font-extrabold text-main text-lg leading-none h-[120px] lg:h-[150px] ssm:h-[50px] mt-[5px]"
    >
      <span
        class="ssm:text-[40px] select-none text-[70px] lg:text-[110px] text-main"
      >
        I'm
        <span class="hover:text-accent">Umar.</span>
      </span>
    </p>

    <!-- Description -->
    <p class="text-base ssm:text-base-sm">
      I'm a Full-Stack Developer with a sharp eye for clean design and a love
      for building things that just work front to back. Whether I'm styling
      pixels or wiring up APIs, I enjoy turning complex problems into smooth,
      scalable solutions.
    </p>

    <!-- Learn More Button -->
    <a href="#about"
      ><button
        class="w-150px h-50px bg-accent text-main my-5 bg-opacity-70 hover:bg-main hover:bg-opacity-30 hover:text-accent"
        >Learn More</button
      ></a
    >
  </div>
</template>

<script>
import TypeWriter from "../typeWriter.vue";

export default {
  name: "hero",
  components: { TypeWriter },
};
</script>
