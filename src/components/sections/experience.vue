<template>
  <!-- Header -->
  <Heading tempID="experience" heading="Experience" headingNum="02"></Heading>

  <!-- Place Special Tiles Here </ -->
  <div class="nav-sm:w-[80%] ssm:w-[85%] w-2/3 h-full mx-auto max-w-screen-xl">
    <ExTile
      title="Mid-Level Full-Stack Developer"
      employer="Kenrow Online"
      date="July 2024 – Present"
      description1="Developed core features for an enterprise-level e-commerce platform using React.js and Tailwind CSS on the frontend, and Node.js with MongoDB on the backend, ensuring responsiveness, data integrity, and performance across the stack."
      description2="Built dynamic interfaces with React components, designed efficient APIs in Node.js, and managed real-time data flow using MongoDB; collaborated with UI/UX designers to refine visuals and integrated SEO best practices for improved discoverability."
      description3="Resulted in a 25% increase in user engagement, a 10% boost in conversion rates, and a 15% improvement in Lighthouse performance scores, while reducing bounce rate by 20% through a streamlined and responsive user experience."
    ></ExTile>
    <ExTile
      title="Front-End Developer"
      employer="KanemTrade Online Ecommerce"
      date="August 2023 – June 2024"
      description1="Built the front end of a custom e-commerce platform using Bootstrap CSS for responsive layout, JavaScript for dynamic interactivity, and connected it to a PHP/Laravel backend with a MySQL database."
      description2="Used these technologies to design and implement product listing, cart, and checkout pages, enabling real-time data updates and seamless integration with backend logic via Laravel routes and controllers."
      description3="Resulted in a 20% improvement in page load speed, a 15% decrease in cart abandonment, and a 25% increase in average session duration, contributing to a smoother and more efficient user experience."
    ></ExTile>
    <ExTile
      title="Web Developer Intern"
      employer="KanemTrade Online Ecommerce"
      date="February 2022 – July 2023"
      description1="Assisted in the development of core web features using PHP, Laravel, and MySQL, while learning to implement front-end layouts with Bootstrap CSS and JavaScript under the guidance of senior developers."
      description2="Supported the integration of backend logic with database-driven content and helped test and debug UI components, ensuring functionality across devices and browsers."
      description3="Contributed to a 10% reduction in reported bugs during release cycles by proactively identifying layout inconsistencies and minor logic flaws in staging environments."
    ></ExTile>
  </div>

  <!-- /> Place Normal Tiles Here -->
</template>

<script>
import Heading from "../heading.vue";
import ExTile from "../exTile.vue";

export default {
  name: "experience",
  components: {
    Heading,
    ExTile,
  },
};
</script>
