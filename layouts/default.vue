<template>
  <div>
    <header>
      <nav>
        <NuxtLink to="/">
          Home
        </NuxtLink>
        <NuxtLink to="/accommodations">
          Accommodation
        </NuxtLink>
        <NuxtLink to="/">
          Rates & Reservations
        </NuxtLink>
        <NuxtLink to="/">
          Location & Maps
        </NuxtLink>
      </nav>
    </header>
    <main>
      <slot />
    </main>
    <footer class="bg-blue-500 text-white p-4">
      <p class="text-center">
        &copy; 2024 Daphnes Villas and Apartments. All rights reserved.
      </p>
    </footer>
  </div>
</template>

<script setup>

</script>

<style scoped>

</style>