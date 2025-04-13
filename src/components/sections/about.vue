<template>
  <div>
    <Heading tempID="about" heading="About" headingNum="01"></Heading>

    <div
      class="nav-sm:w-[80%] ssm:w-[85%] w-2/3 flex justify-center flex-col select-none h-full mx-auto max-w-screen-xl"
    >
      <h1 class="text-accent text-[40px] font-bold text-center">Who am I?</h1>

      <p
        class="w-full text-justify sm:text-left text-base ssm:text-base-sm text-main"
      >
        I am <strong class="text-accent">Umar Usman</strong>. I build digital
        experiences that are as refined under the hood as they are on the
        surface. With a focus on modern web technologies like React.js, Node.js,
        and MongoDB, I craft full-stack solutions that prioritize clarity,
        performance, and elegance. Whether its a seamless interface or a robust
        backend system, I approach each project with the intention of making it
        intuitive, scalable, and impactful.<br /><br />

        My strength lies in seeing both the big picture and the smallest pixel.
        From real-time applications to custom e-commerce platforms, I bring a
        designer's eye to development, delivering interfaces that resonate, and
        functionality that performs. I also maintain a small open-source
        presence, including an npm package I published to simplify everyday UI
        logic. Born from a desire to give back to the developer community and
        reduce friction for others where I once had it myself.
        <br /><br />

        Great products are rarely built in isolation. They require clarity,
        strategic focus, and the right people in the room. That's what I bring.
        If you're aiming to build something that's not just functional but
        intentional and well-executed, I'd be honored to contribute my
        expertise, precision, and technical insight to your team.<br /><br />
      </p>
    </div>
  </div>
</template>

<script>
import Heading from "../heading.vue";

export default {
  name: "about",
  components: { Heading },
};
</script>
