<template>
  <div
    class="min-h-screen flex flex-col items-center justify-center bg-gray-100 px-4"
  >
    <!-- Hero Section -->
    <section class="text-center">
      <h1 class="text-4xl font-extrabold text-gray-900 sm:text-5xl">
        Find Your Dream Car Today
      </h1>
      <p class="mt-4 text-gray-600 max-w-xl mx-auto">
        Browse through our extensive collection of new and used cars at
        unbeatable prices. Drive home your perfect car with ease.
      </p>
    </section>

    <!-- Featured Cars -->
    <section
      class="mt-10 grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8 w-full max-w-4xl"
    >
      <div class="p-6 bg-white shadow-md rounded-lg text-center">
        <img
          src="../assets/car1.jpg"
          alt="Sports Car"
          class="w-full h-40 object-cover rounded"
        />
        <h2 class="text-xl font-semibold text-gray-800 mt-4">🏎️ Sports Cars</h2>
        <p class="text-gray-600 mt-2">
          Experience speed and luxury with our premium sports cars.
        </p>
      </div>

      <div class="p-6 bg-white shadow-md rounded-lg text-center">
        <img
          src="../assets/car2.jpg"
          alt="SUV"
          class="w-full h-40 object-cover rounded"
        />
        <h2 class="text-xl font-semibold text-gray-800 mt-4">
          🚙 SUVs & Family Cars
        </h2>
        <p class="text-gray-600 mt-2">
          Spacious and comfortable cars for your family trips.
        </p>
      </div>

      <div class="p-6 bg-white shadow-md rounded-lg text-center">
        <img
          src="../assets/car3.jpg"
          alt="Luxury Car"
          class="w-full h-40 object-cover rounded"
        />
        <h2 class="text-xl font-semibold text-gray-800 mt-4">🚗 Luxury Cars</h2>
        <p class="text-gray-600 mt-2">
          Drive in style with our premium selection of luxury vehicles.
        </p>
      </div>
    </section>

    <!-- Call to Action -->
    <section class="mt-10 text-center">
      <router-link
        to="/about"
        class="px-6 py-2 bg-blue-600 text-white text-lg font-medium rounded shadow-md hover:bg-blue-700 transition"
      >
        Explore More About Us
      </router-link>
    </section>
  </div>
</template>

