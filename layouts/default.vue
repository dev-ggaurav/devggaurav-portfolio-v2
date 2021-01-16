<template>
  <div class="flex flex-col h-screen justify-between">
    <div class="">
      <Header />
    </div>
    <div class="mb-auto">
      <Nuxt />
    </div>
    <div class="h-10">
      <hr class="h-px mt-6 border-gray-300 wrapper-small">
      <Footer />
    </div>
  </div>
</template>

<style>
  .wrapper{
    @apply max-w-screen-xl mx-auto;
  }

  .wrapper-small{
    @apply max-w-screen-lg mx-auto px-10;
  }

  .flex-center{
    @apply flex justify-center items-center;
  }
</style>
