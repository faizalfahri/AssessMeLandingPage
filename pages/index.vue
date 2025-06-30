<script lang="ts" setup>
definePageMeta({
  layout: "landingpage",
});
</script>

<template>
  <div
    class="min-h-screen bg-gradient-to-br from-purple-50 to-white font-inter"
  >
    <!-- Navbar -->
    <nav class="flex items-center justify-between p-6 container mx-auto">
      <div class="flex items-center space-x-2">
        <div
          class="w-8 h-8 bg-purple-200 rounded-full flex items-center justify-center"
        >
          <!-- Placeholder for logo/icon -->
          <svg
            class="w-5 h-5 text-purple-600"
            fill="none"
            stroke="currentColor"
            viewBox="0 0 24 24"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M13 10V3L4 14h7v7l9-11h-7z"
            ></path>
          </svg>
        </div>
        <span class="text-lg font-semibold text-gray-800"></span>
      </div>

      <!-- Navbar -->
      <div class="hidden md:flex items-center space-x-8">
        <a href="#" class="text-gray-600 hover:text-pink-600 rounded-md"
          >Home</a
        >
        <a href="#" class="text-gray-600 hover:text-pink-600 rounded-md"
          >About us</a
        >
        <div class="relative group">
          <button
            class="flex items-center text-gray-600 hover:text-pink-600 focus:outline-none rounded-md"
          >
            Features
          </button>
        </div>
      </div>
      <!-- Akhir Navbar -->

      <div class="flex items-center space-x-4">
        <a href="#" class="text-gray-600 hover:text-blue-600 rounded-md"
          >Log in</a
        >
        <!-- This button seems to be for login in the image, but it's not a button, more like a text link -->
        <button class="md:hidden text-gray-600 focus:outline-none">
          <svg
            class="w-6 h-6"
            fill="none"
            stroke="currentColor"
            viewBox="0 0 24 24"
            xmlns="http://www.w3.org/2000/svg"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M4 6h16M4 12h16M4 18h16"
            ></path>
          </svg>
        </button>
      </div>
    </nav>

    <!-- Main Content -->
    <main
      class="flex flex-col items-center justify-center text-center px-4 py-50 pt-35"
    >
      <!-- Announcement Banner -->
      <div
        class="bg-purple-100 text-pink-400 px-4 py-2 rounded-full text-sm mb-8 flex items-center"
      >
        Assessment is now available with new version!
        <a
          href="#"
          class="ml-2 font-medium underline text-pink-400 hover:text-pink-500"
          >Read more →</a
        >
      </div>

      <h1
        class="text-5xl md:text-6xl font-bold text-gray-900 mb-6 leading-tight"
      >
        Assess Me
      </h1>
      <p class="text-lg md:text-xl text-gray-600 mb-10 max-w-2xl">
        Simple UI Assessment with Accurate Conclusion for employee performance.
      </p>

      <div
        class="flex flex-col sm:flex-row space-y-4 sm:space-y-0 sm:space-x-4"
      >
        <button
          class="bg-pink-600 hover:bg-pink-700 text-white font-medium py-3 px-8 rounded-xl shadow-lg transition duration-300 ease-in-out transform hover:-translate-y-1"
        >
          Get started
        </button>
        <button
          class="bg-gray-200 hover:bg-gray-300 text-gray-800 font-medium py-3 px-8 rounded-xl shadow-lg transition duration-300 ease-in-out transform hover:-translate-y-1"
        >
          View Product →
        </button>
      </div>
    </main>

    <!-- New Section: Develop Faster -->
    <section
      class="container mx-auto px-6 py-20 grid grid-cols-1 md:grid-cols-2 gap-16 items-start"
    >
      <div class="text-left">
        <h3 class="text-pink-600 font-semibold text-sm uppercase mb-3">
          Develop Faster
        </h3>
        <h2
          class="text-4xl md:text-5xl font-bold text-gray-900 mb-6 leading-tight"
        >
          Everything you need to create your app
        </h2>
        <p class="text-lg text-gray-600 mb-10">
          Includes everything you need to build your app, including a
          customizable UI kit, authentication, and more.
        </p>

        <div class="space-y-6">
          <div class="flex items-start">
            <div
              class="flex-shrink-0 w-8 h-8 rounded-full bg-purple-100 flex items-center justify-center mt-1 mr-4"
            >
              <svg
                class="w-5 h-5 text-purple-600"
                fill="none"
                stroke="currentColor"
                viewBox="0 0 24 24"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.001 12.001 0 002.944 12c.045 4.381 2.923 8.167 6.643 10.024A11.955 11.955 0 0112 21.056a11.955 11.955 0 018.618-3.04A12.001 12.001 0 0021.056 12c-.045-4.381-2.923-8.167-6.643-10.024z"
                ></path>
              </svg>
            </div>
            <div>
              <p class="font-semibold text-gray-900">Nuxt 3</p>
              <p class="text-gray-600 text-sm">
                The latest and greatest version of Nuxt.js, with a new file
                system based routing system and a new way to write your
                components.
              </p>
            </div>
          </div>

          <div class="flex items-start">
            <div
              class="flex-shrink-0 w-8 h-8 rounded-full bg-purple-100 flex items-center justify-center mt-1 mr-4"
            >
              <svg
                class="w-5 h-5 text-purple-600"
                fill="none"
                stroke="currentColor"
                viewBox="0 0 24 24"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M7 21a4 4 0 01-4-4V5a2 2 0 012-2h4a2 2 0 012 2v12a4 4 0 01-4 4zm0 0h12a2 2 0 002-2V5a2 2 0 00-2-2h-2.586a1 1 0 01-.707-.293l-1.121-1.121A1 1 0 009.172 2H7m0 0H4a2 2 0 00-2 2v14a3 3 0 003 3h15a3 3 0 003-3V5a2 2 0 00-2-2h-4a2 2 0 00-2 2v12a4 4 0 00-4 4z"
                ></path>
              </svg>
            </div>
            <div>
              <p class="font-semibold text-gray-900">Tailwind CSS</p>
              <p class="text-gray-600 text-sm">
                A utility-first CSS framework packed with classes that can be
                composed to build any design, directly in your markup.
              </p>
            </div>
          </div>

          <div class="flex items-start">
            <div
              class="flex-shrink-0 w-8 h-8 rounded-full bg-purple-100 flex items-center justify-center mt-1 mr-4"
            >
              <svg
                class="w-5 h-5 text-purple-600"
                fill="none"
                stroke="currentColor"
                viewBox="0 0 24 24"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M10 20l4-16m4 4l4 4-4 4M6 16l-4-4 4-4"
                ></path>
              </svg>
            </div>
            <div>
              <p class="font-semibold text-gray-900">Headless UI</p>
              <p class="text-gray-600 text-sm">
                Completely unstyled, fully accessible UI components, designed to
                integrate beautifully with Tailwind CSS.
              </p>
            </div>
          </div>

          <div class="flex items-start">
            <div
              class="flex-shrink-0 w-8 h-8 rounded-full bg-purple-100 flex items-center justify-center mt-1 mr-4"
            >
              <svg
                class="w-5 h-5 text-purple-600"
                fill="none"
                stroke="currentColor"
                viewBox="0 0 24 24"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M11 4a2 2 0 100 4m-4 8a2 2 0 100 4m4-4a2 2 0 100 4m4-4a2 2 0 100 4M6 11h2m4 0h2m4 0h2M7 15h10M4 7h2m4 0h2m4 0h2"
                ></path>
              </svg>
            </div>
            <div>
              <p class="font-semibold text-gray-900">Built-in Components</p>
              <p class="text-gray-600 text-sm">
                A collection of UI components built with Tailwind CSS and
                Headless UI, ready to be used in your projects.
              </p>
            </div>
          </div>
        </div>
      </div>

      <div class="md:sticky md:top-20 flex justify-center items-center">
        <div
          class="bg-gray-100 rounded-xl shadow-lg w-full max-w-lg h-96 flex items-center justify-center overflow-hidden"
        >
          <p class="text-gray-500">Product screenshot</p>
          <!-- Placeholder for product screenshot -->
          <!-- You can replace this with an actual image or more complex content later -->
        </div>
      </div>
    </section>
  </div>
</template>

<style>
/* Import Google Font - Inter */
@import url("https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap");

/* Basic global styles if necessary, though Tailwind handles most of it */
body {
  margin: 0;
  font-family: "Inter", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
