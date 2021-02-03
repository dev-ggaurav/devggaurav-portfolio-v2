<template>
  <div class="wrapper-small">
    <div class="header mt-10">
      <Hero />
      <Social />
    </div>
    <div>
      <Projects />
    </div>
  </div>
</template>

<script>
  import Hero from '../components/Hero.vue'
  import Social from '../components/Social.vue'
  import Projects from '../components/Projects.vue'
    export default {
      components:{
        Hero, Social, Projects
      },
      head() {
        return {
          script: [{ src: 'https://identity.netlify.com/v1/netlify-identity-widget.js' }],
        };
      },
    };
</script>

<style>

</style>