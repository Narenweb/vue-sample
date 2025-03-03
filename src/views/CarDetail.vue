<template>
  <div
    class="min-h-screen flex flex-col items-center justify-center bg-white px-4"
  >
    <h1 class="text-3xl font-bold text-gray-900">Car Details</h1>

    <div v-if="car" class="mt-6 text-center">
      <img
        :src="car.image"
        alt="Car Image"
        class="w-80 h-48 object-cover rounded"
      />
      <h2 class="text-2xl font-semibold text-gray-800 mt-4">{{ car.name }}</h2>
      <p class="text-gray-600 mt-2">{{ car.description }}</p>
    </div>

    <p v-else class="text-red-500 mt-4">Car not found!</p>

    <router-link
      to="/"
      class="mt-6 px-6 py-2 bg-blue-600 text-white rounded hover:bg-blue-700 transition"
    >
      Back to Home
    </router-link>
  </div>
</template>

<script>
export default {
  data() {
    return {
      cars: [
        {
          id: 1,
          name: "🏎️ Sports Car",
          description: "Experience speed and luxury.",
          image: require("../assets/car1.jpg"),
        },
        {
          id: 2,
          name: "🚙 SUV",
          description: "Perfect for family trips.",
          image: require("../assets/car2.jpg"),
        },
        {
          id: 3,
          name: "🚗 Luxury Car",
          description: "Drive in style and comfort.",
          image: require("../assets/car3.jpg"),
        },
      ],
    };
  },
  computed: {
    car() {
      return this.cars.find((c) => c.id == this.$route.params.id);
    },
  },
};
</script>
