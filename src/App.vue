<template>
  <nav class="bg-white shadow p-4 flex justify-between">
    <h1 class="text-lg font-bold text-blue-600">Vue SPA</h1>
    <div class="space-x-4">
      <router-link to="/" class="text-gray-700 hover:text-blue-500"
        >Home</router-link
      >
      <router-link to="/about" class="text-gray-700 hover:text-blue-500"
        >About</router-link
      >
    </div>
  </nav>
  <router-view />
</template>
