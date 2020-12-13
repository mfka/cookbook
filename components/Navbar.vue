<template>
  <div class="w-full h-screen">
    <section
      id="bottom-navigation"
      class="md:hidden block fixed inset-x-0 bottom-0 z-10 bg-white shadow"
    >
      <section class="block fixed inset-x-0 bottom-0 z-10 bg-white shadow">
        <div class="flex justify-between">
          <NuxtLink
            class="w-full focus:text-teal-500 hover:text-teal-500 justify-center inline-block text-center pt-2 pb-1"
            to="/"
          >
            <svg
              width="25"
              height="25"
              viewBox="0 0 24 24"
              class="inline-block mb-1"
              stroke="currentColor"
              fill="none"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M3 12l2-2m0 0l7-7 7 7M5 10v10a1 1 0 001 1h3m10-11l2 2m-2-2v10a1 1 0 01-1 1h-3m-6 0a1 1 0 001-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 001 1m-6 0h6"
              />
            </svg>
            <span class="block text-xs">Home</span>
          </NuxtLink>
          <NuxtLink
            class="w-full focus:text-teal-500 hover:text-teal-500 justify-center inline-block text-center pt-2 pb-1"
            to="/search"
          >
            <svg
              width="25"
              height="25"
              class="inline-block mb-1"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"
              />
            </svg>
            <span class="block text-xs">Search</span>
          </NuxtLink>
          <NuxtLink
            class="w-full focus:text-teal-500 hover:text-teal-500 justify-center inline-block text-center pt-2 pb-1"
            to="/categories"
          >
            <svg
              width="25"
              height="25"
              class="inline-block mb-1"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M4 6a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2H6a2 2 0 01-2-2V6zM14 6a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2h-2a2 2 0 01-2-2V6zM4 16a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2H6a2 2 0 01-2-2v-2zM14 16a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2h-2a2 2 0 01-2-2v-2z"
              />
            </svg>
            <span class="block text-xs">Categories</span>
          </NuxtLink>
        </div>
      </section>
    </section>
  </div>
</template>
