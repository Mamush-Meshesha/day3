<template>
  <div>
    <div class="max-h-screen w-[15%] fixed">
      <!-- profile -->
      <div class="h-[150px] bg-[#214162] flex gap-10 items-center px-[11%]">
        <img
          src="../assets/css/profile/photo_2023-10-30_09-05-42.jpg"
          alt=""
          class="w-[80px] h-[80px] rounded-full object-cover"
        />
        <div class="flex flex-col gap-2">
          <h1 class="text-2xl text-white">Mamush</h1>
          <div class="flex gap-3 items-center">
            <div class="w-2 h-2 rounded-full bg-[#38b61f]"></div>
            <h1 class="text-xs text-[#38b61f]">Online</h1>
          </div>
        </div>
      </div>
      <!-- end of profile -->
      <div class="h-screen bg-[#15283C]">
        <div class="pt-10">
          <div class="border-b-2 pb-4 border-[#8f3e3e]">
            <div class="pl-[9%]">
              <h1 class="text-white text-2xl">General</h1>
            </div>
          </div>
          <div class="pl-[9%] pt-7">
            <!-- inside general -->
            <div class="flex flex-col gap-6">
              <div class="flex gap-5 items-center">
                <svg
                  class="w-6 h-6 text-red-600 dark:text-white"
                  aria-hidden="true"
                  xmlns="http://www.w3.org/2000/svg"
                  fill="currentColor"
                  viewBox="0 0 24 24"
                >
                  <path
                    d="M12 6.2 7 9.4l5 3.2-5 3.2-5-3.3 5-3.1-5-3.2L7 3l5 3.2ZM7 17.8l5-3.2 5 3.2-5 3.2-5-3.2Z"
                  />
                  <path
                    d="m12 12.5 5-3.1-5-3.2L17 3l5 3.2-5 3.2 5 3.2-5 3.2-5-3.3Z"
                  />
                </svg>

                <NuxtLink to="/" class="text-[#CED2D6] text-xl"
                  >Dashboard</NuxtLink
                >
              </div>
              <div class="flex gap-5 items-center">
                <svg
                  class="w-6 h-6 text-green-500 dark:text-white"
                  aria-hidden="true"
                  xmlns="http://www.w3.org/2000/svg"
                  fill="none"
                  viewBox="0 0 24 24"
                >
                  <path
                    stroke="currentColor"
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M12 8v4l3 3m6-3a9 9 0 1 1-18 0 9 9 0 0 1 18 0Z"
                  />
                </svg>
                <NuxtLink to="/" class="text-[#CED2D6] text-xl"
                  >Widgets</NuxtLink
                >
              </div>
              <div class="flex gap-5 items-center">
                <svg
                  class="w-6 h-6 text-pink-500 dark:text-white"
                  aria-hidden="true"
                  xmlns="http://www.w3.org/2000/svg"
                  fill="none"
                  viewBox="0 0 24 24"
                >
                  <path
                    fill="currentColor"
                    d="M12 17a2 2 0 0 1 2 2h-4a2 2 0 0 1 2-2Z"
                  />
                  <path
                    stroke="currentColor"
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M13.8 9h2.7a2 2 0 1 0-1-3.7 1.9 1.9 0 0 0-.4-1.4 2 2 0 0 0-3.1-.2 2 2 0 0 0-3.5 1.6 2 2 0 1 0-1 3.7h3.4m3-1v3.6M10.1 9v2.6M15 16h0m-6 0h0m12-4.4a1.8 1.8 0 0 1-1.8 1.3 1.9 1.9 0 0 1-1.8-1.3 1.9 1.9 0 0 1-3.6 0 1.8 1.8 0 0 1-1.7 1.3 2 2 0 0 1-2-1.3 1.8 1.8 0 0 1-1.6 1.3 2 2 0 0 1-2-1.3 1.9 1.9 0 0 1-1.8 1.3A1.8 1.8 0 0 1 3 11.6v.4a9 9 0 0 0 18 0v-.4Z"
                  />
                </svg>
                <NuxtLink to="/" class="text-[#CED2D6] text-xl"
                  >Elements</NuxtLink
                >
              </div>
              <div class="flex gap-5 items-center">
                <svg
                  class="w-6 h-6 text-yellow-500 dark:text-white"
                  aria-hidden="true"
                  xmlns="http://www.w3.org/2000/svg"
                  fill="none"
                  viewBox="0 0 24 24"
                >
                  <path
                    stroke="currentColor"
                    stroke-width="2"
                    d="M3 11h18m-9 0v8m-8 0h16c.6 0 1-.4 1-1V6c0-.6-.4-1-1-1H4a1 1 0 0 0-1 1v12c0 .6.4 1 1 1Z"
                  />
                </svg>
                <NuxtLink to="/" class="text-[#CED2D6] text-xl"
                  >Tables</NuxtLink
                >
              </div>
              <div class="flex gap-5 items-center">
                <svg
                  class="w-6 h-6 text-blue-800 dark:text-white"
                  aria-hidden="true"
                  xmlns="http://www.w3.org/2000/svg"
                  fill="currentColor"
                  viewBox="0 0 24 24"
                >
                  <path
                    d="M17.5 12.6a4.4 4.4 0 0 0 2.7 4c-.3 1-.8 2-1.4 3-.8 1.1-1.7 2.3-3 2.4-1.4 0-1.8-.8-3.3-.8-1.6 0-2 .7-3.3.8-1.3 0-2.3-1.3-3.2-2.5-1.7-2.5-3-7-1.2-10.1a4.9 4.9 0 0 1 4.1-2.5c1.3 0 2.5.9 3.3.9.8 0 2.3-1.1 3.8-1a4.7 4.7 0 0 1 3.7 2 4.5 4.5 0 0 0-2.2 3.8M15 5.2c.8-.9 1.1-2 1-3.2a4.5 4.5 0 0 0-3.7 3c-.2.5-.3 1-.2 1.6a3.7 3.7 0 0 0 3-1.4Z"
                  />
                </svg>

                <NuxtLink to="/" class="text-[#CED2D6] text-xl">Apps</NuxtLink>
              </div>
              <div class="flex gap-5 items-center">
                <svg
                  class="w-6 h-6 text-[#2c84b8] dark:text-white"
                  aria-hidden="true"
                  xmlns="http://www.w3.org/2000/svg"
                  fill="none"
                  viewBox="0 0 24 24"
                >
                  <path
                    stroke="currentColor"
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M9 10V6a3 3 0 0 1 3-3v0a3 3 0 0 1 3 3v4m3-2 1 12c0 .5-.5 1-1 1H6a1 1 0 0 1-1-1L6 8h12Z"
                  />
                </svg>
                <NuxtLink to="/" class="text-[#CED2D6] text-xl"
                  >Pricing Tables</NuxtLink
                >
              </div>
              <div class="flex gap-5 items-center">
                <svg
                  class="w-6 h-6 text-[#aa2fdb] dark:text-white"
                  aria-hidden="true"
                  xmlns="http://www.w3.org/2000/svg"
                  fill="currentColor"
                  viewBox="0 0 24 24"
                >
                  <path
                    d="M8 4a2.6 2.6 0 0 0-2 .9 6.2 6.2 0 0 0-1.8 6 12 12 0 0 0 3.4 5.5 12 12 0 0 0 5.6 3.4 6.2 6.2 0 0 0 6.6-2.7 2.6 2.6 0 0 0-.7-3L18 12.9a2.7 2.7 0 0 0-3.8 0l-.6.6a.8.8 0 0 1-1.1 0l-1.9-1.8a.8.8 0 0 1 0-1.2l.6-.6a2.7 2.7 0 0 0 0-3.8L10 4.9A2.6 2.6 0 0 0 8 4Z"
                  />
                </svg>

                <NuxtLink to="/" class="text-[#CED2D6] text-xl"
                  >Contacts</NuxtLink
                >
              </div>
              <div class="flex gap-5 items-center">
                <svg
                  class="w-6 h-6 text-[#855121] dark:text-white"
                  aria-hidden="true"
                  xmlns="http://www.w3.org/2000/svg"
                  fill="currentColor"
                  viewBox="0 0 24 24"
                >
                  <path
                    fill-rule="evenodd"
                    d="M6.5 3.9c0-.5.4-.9.9-.9h5.2c.5 0 .9.4.9.9h1.8c1 0 1.7.7 1.7 1.6V6h-1l-2.4.1a4 4 0 0 0-1 .3h-.8V4.7H8.2v1.7h-.8c-.5 0-.9.4-.9.8 0 .5.4.9.9.9h3.3L9.1 9.9a4 4 0 0 0-1 1.5L8 14v5c0 .7.2 1.4.5 2H4.7c-1 0-1.7-.8-1.7-1.7V5.5C3 4.7 3.8 4 4.8 4h1.7Z"
                    clip-rule="evenodd"
                  />
                  <path
                    fill-rule="evenodd"
                    d="M14 8v4h-4l.5-.8L13 8.6a2 2 0 0 1 1-.6Zm2 0v4a2 2 0 0 1-2 2h-4v5c0 1.1.9 2 2 2h7a2 2 0 0 0 2-2v-9a2 2 0 0 0-2-2h-3Z"
                    clip-rule="evenodd"
                  />
                </svg>

                <NuxtLink to="/" class="text-[#CED2D6] text-xl"
                  >Additional Pages</NuxtLink
                >
              </div>
              <div class="flex gap-5 items-center">
                <svg
                  class="w-6 h-6 text-[#7bb124] dark:text-white"
                  aria-hidden="true"
                  xmlns="http://www.w3.org/2000/svg"
                  fill="currentColor"
                  viewBox="0 0 24 24"
                >
                  <path
                    fill-rule="evenodd"
                    d="M12 2a8 8 0 0 1 6.6 12.6l-.1.1-.6.7-5.1 6.2a1 1 0 0 1-1.6 0L6 15.3l-.3-.4-.2-.2v-.2A8 8 0 0 1 11.8 2Zm3 8a3 3 0 1 1-6 0 3 3 0 0 1 6 0Z"
                    clip-rule="evenodd"
                  />
                </svg>

                <NuxtLink to="/" class="text-[#CED2D6] text-xl">Maps</NuxtLink>
              </div>
              <div class="flex gap-5 items-center">
                <svg
                  class="w-6 h-6 text-[#a72264] dark:text-white"
                  aria-hidden="true"
                  xmlns="http://www.w3.org/2000/svg"
                  fill="currentColor"
                  viewBox="0 0 24 24"
                >
                  <path
                    d="M13.5 2a7 7 0 0 0-.5 0 1 1 0 0 0-1 1v8c0 .6.4 1 1 1h8c.5 0 1-.4 1-1v-.5A8.5 8.5 0 0 0 13.5 2Z"
                  />
                  <path
                    d="M11 6a1 1 0 0 0-1-1 8.5 8.5 0 1 0 9 9 1 1 0 0 0-1-1h-7V6Z"
                  />
                </svg>

                <NuxtLink to="/" class="text-[#CED2D6] text-xl"
                  >Charts</NuxtLink
                >
              </div>
              <div class="flex gap-5 items-center">
                <svg
                  class="w-6 h-6 text-[#7ec9aa] dark:text-white"
                  aria-hidden="true"
                  xmlns="http://www.w3.org/2000/svg"
                  fill="currentColor"
                  viewBox="0 0 24 24"
                >
                  <path
                    fill-rule="evenodd"
                    d="M9.6 2.6A2 2 0 0 1 11 2h2a2 2 0 0 1 2 2l.5.3a2 2 0 0 1 2.9 0l1.4 1.3a2 2 0 0 1 0 2.9l.1.5h.1a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2l-.3.5a2 2 0 0 1 0 2.9l-1.3 1.4a2 2 0 0 1-2.9 0l-.5.1v.1a2 2 0 0 1-2 2h-2a2 2 0 0 1-2-2l-.5-.3a2 2 0 0 1-2.9 0l-1.4-1.3a2 2 0 0 1 0-2.9l-.1-.5H4a2 2 0 0 1-2-2v-2a2 2 0 0 1 2-2l.3-.5a2 2 0 0 1 0-2.9l1.3-1.4a2 2 0 0 1 2.9 0l.5-.1V4c0-.5.2-1 .6-1.4ZM8 12a4 4 0 1 1 8 0 4 4 0 0 1-8 0Z"
                    clip-rule="evenodd"
                  />
                </svg>

                <NuxtLink to="/" class="text-[#CED2D6] text-xl"
                  >Settings</NuxtLink
                >
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup></script>
