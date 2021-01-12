<template>
  <div class="text-center">
    <h1>Home</h1>
  </div>
</template>

<script>
    export default {
      head() {
        return {
          script: [{ src: 'https://identity.netlify.com/v1/netlify-identity-widget.js' }],
        };
      },
    };
</script>

<style>

</style>