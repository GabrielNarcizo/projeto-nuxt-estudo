<template>
  <div>
    <div class="bg-gray-100">
      <div class="container mx-auto flex items-center space-x-4 h-10 mb-10">
        <NuxtLink :to="{ name: 'a-empresa' }">A empresa</NuxtLink>
        <NuxtLink :to="{ name: 'servicos' }">Serviços</NuxtLink>
      </div>
    </div>

    <div>
      <div class="container mx-auto">
        <h1 class="text-lg font-bold">Serviços</h1>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Debitis,
          beatae culpa eligendi laborum expedita ad numquam porro dolores, quam
          laboriosam itaque cum quia corporis consectetur voluptate molestiae
          neque dicta nostrum.
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style></style>
