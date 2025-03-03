<template>
  <div
    class="min-h-screen flex flex-col items-center justify-center bg-gray-100 px-6"
  >
    <!-- Header -->
    <h1 class="text-4xl font-bold text-gray-900">About Us</h1>
    <p class="text-gray-600 mt-3 max-w-2xl text-center">
      Welcome to <span class="font-semibold">AutoHub</span>, your trusted
      destination for buying and selling high-quality vehicles. We offer a
      seamless and secure car-buying experience with a wide range of vehicles to
      match every need.
    </p>

    <!-- About Content -->
    <div class="mt-10 max-w-4xl bg-white shadow-lg rounded-lg p-6">
      <h2 class="text-2xl font-semibold text-gray-800 mb-4">Why Choose Us?</h2>
      <ul class="text-gray-600 space-y-3">
        <li>
          ✅ **Wide Selection** – Choose from sports cars, SUVs, luxury
          vehicles, and more.
        </li>
        <li>
          ✅ **Verified Listings** – All cars are inspected for quality and
          authenticity.
        </li>
        <li>
          ✅ **Affordable Pricing** – Competitive rates with financing options
          available.
        </li>
        <li>
          ✅ **Easy Process** – Browse, compare, and book your car online in
          minutes.
        </li>
        <li>
          ✅ **Trusted by Thousands** – Join a community of satisfied car buyers
          and sellers.
        </li>
      </ul>
    </div>

    <!-- Call to Action -->
    <router-link
      to="/"
      class="mt-6 px-6 py-3 bg-blue-600 text-white text-lg font-medium rounded shadow-md hover:bg-blue-700 transition"
    >
      Browse Cars
    </router-link>
  </div>
</template>
