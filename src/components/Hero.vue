<script setup lang="ts">
import { ref } from 'vue'

const clients = ref([
  {
    name: 'Ayroui',
    logo: 'https://cdn.tailgrids.com/2.0/image/assets/images/brands/ayroui.svg',
    link: 'javascript:void(0)'
  },
  {
    name: 'GrayGrids',
    logo: 'https://cdn.tailgrids.com/2.0/image/assets/images/brands/graygrids.svg',
    link: 'javascript:void(0)'
  },
  {
    name: 'UIdeck',
    logo: 'https://cdn.tailgrids.com/2.0/image/assets/images/brands/uideck.svg',
    link: 'javascript:void(0)'
  }
])
</script>

<template>
  <!-- ====== Hero Section Start -->
  <div class=" bg-white dark:bg-dark pt-[120px] pb-[110px] lg:pt-[40px]">
    <div class="container mx-auto">
      
      <div class="flex flex-wrap items-center -mx-4">
        <div class="w-full px-4 lg:w-5/12">
          <div class="hero-content">
            <h1
              class="mb-5 text-4xl font-bold !leading-[1.208] text-dark dark:text-white sm:text-[42px] lg:text-[40px] xl:text-5xl"
            >
              The Greatest <br />
              Journey Of Online <br />
              Payment.
            </h1>
            <p class="mb-8 max-w-[480px] text-base text-body-color dark:text-dark-6">
              With TailGrids, business and students thrive together. Business can perfectly match
              their staffing to changing demand throughout the dayed.
            </p>
            <ul class="flex flex-wrap items-center">
              <li>
                <a
                  href="javascript:void(0)"
                  class="inline-flex items-center justify-center px-6 py-3 text-base font-medium text-center text-white rounded-md bg-primary hover:bg-blue-dark lg:px-7"
                >
                  Get Started
                </a>
              </li>
              <li>
                <a
                  href="javascript:void(0)"
                  class="inline-flex items-center justify-center py-3 px-5 text-center text-base font-medium text-[#464646] dark:text-white hover:text-primary"
                >
                  <span class="mr-2">
                    <svg
                      width="24"
                      height="25"
                      viewBox="0 0 24 25"
                      fill="none"
                      xmlns="http://www.w3.org/2000/svg"
                    >
                      <circle cx="12" cy="12.6152" r="12" fill="#3758F9" />
                      <rect x="7.99893" y="14.979" width="8.18182" height="1.63636" fill="white" />
                      <rect x="11.2717" y="7.61523" width="1.63636" height="4.09091" fill="white" />
                      <path
                        d="M12.0898 14.1606L14.9241 11.0925H9.25557L12.0898 14.1606Z"
                        fill="white"
                      />
                    </svg>
                  </span>
                  Download App
                </a>
              </li>
            </ul>
            <div class="clients pt-16">
              <h6
                class="flex items-center mb-6 text-xs font-normal text-body-color dark:text-dark-6"
              >
                Some Of Our Clients
                <span class="inline-block w-8 h-px ml-3 bg-body-color"></span>
              </h6>
              <div class="flex items-center gap-4 xl:gap-[50px]">
                <a
                  v-for="(client, index) in clients"
                  :key="index"
                  :href="client.link"
                  class="block py-3"
                >
                  <img :src="client.logo" :alt="client.name" />
                </a>
              </div>
            </div>
          </div>
        </div>
        <div class="hidden px-4 lg:block lg:w-1/12"></div>
        <div class="w-full px-4 lg:w-6/12">
          <div class="lg:ml-auto lg:text-right">
            <div class="z-10 inline-block pt-11 lg:pt-0">
              
<div class="relative mx-auto border-gray-800 dark:border-gray-800 bg-gray-800 border-[8px] rounded-t-xl h-[172px] max-w-[401px] md:h-[294px] md:max-w-[712px]">
  <div class="rounded-lg overflow-hidden h-[156px] md:h-[278px] bg-white dark:bg-gray-800">
      <img src="https://flowbite.s3.amazonaws.com/docs/device-mockups/laptop-screen.png" class="dark:hidden h-[156px] md:h-[278px] w-full rounded-xl" alt="">
      <img src="https://flowbite.s3.amazonaws.com/docs/device-mockups/laptop-screen-dark.png" class="hidden dark:block h-[156px] md:h-[278px] w-full rounded-lg" alt="">
  </div>
</div>
<div class="relative mx-auto bg-gray-900 dark:bg-gray-700 rounded-b-xl rounded-t-sm h-[17px] max-w-[351px] md:h-[21px] md:max-w-[597px]">
  <div class="absolute left-1/2 top-0 -translate-x-1/2 rounded-b-xl w-[56px] h-[5px] md:w-[96px] md:h-[8px] bg-gray-800"></div>
</div>

              <span class="absolute -left-8 -bottom-8 z-[-1]">
                <svg
                  width="93"
                  height="93"
                  viewBox="0 0 93 93"
                  fill="none"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <circle cx="2.5" cy="2.5" r="2.5" fill="#3056D3" />
                  <circle cx="2.5" cy="24.5" r="2.5" fill="#3056D3" />
                  <circle cx="2.5" cy="46.5" r="2.5" fill="#3056D3" />
                  <circle cx="2.5" cy="68.5" r="2.5" fill="#3056D3" />
                  <circle cx="2.5" cy="90.5" r="2.5" fill="#3056D3" />
                  <circle cx="24.5" cy="2.5" r="2.5" fill="#3056D3" />
                  <circle cx="24.5" cy="24.5" r="2.5" fill="#3056D3" />
                  <circle cx="24.5" cy="46.5" r="2.5" fill="#3056D3" />
                  <circle cx="24.5" cy="68.5" r="2.5" fill="#3056D3" />
                  <circle cx="24.5" cy="90.5" r="2.5" fill="#3056D3" />
                  <circle cx="46.5" cy="2.5" r="2.5" fill="#3056D3" />
                  <circle cx="46.5" cy="24.5" r="2.5" fill="#3056D3" />
                  <circle cx="46.5" cy="46.5" r="2.5" fill="#3056D3" />
                  <circle cx="46.5" cy="68.5" r="2.5" fill="#3056D3" />
                  <circle cx="46.5" cy="90.5" r="2.5" fill="#3056D3" />
                  <circle cx="68.5" cy="2.5" r="2.5" fill="#3056D3" />
                  <circle cx="68.5" cy="24.5" r="2.5" fill="#3056D3" />
                  <circle cx="68.5" cy="46.5" r="2.5" fill="#3056D3" />
                  <circle cx="68.5" cy="68.5" r="2.5" fill="#3056D3" />
                  <circle cx="68.5" cy="90.5" r="2.5" fill="#3056D3" />
                  <circle cx="90.5" cy="2.5" r="2.5" fill="#3056D3" />
                  <circle cx="90.5" cy="24.5" r="2.5" fill="#3056D3" />
                  <circle cx="90.5" cy="46.5" r="2.5" fill="#3056D3" />
                  <circle cx="90.5" cy="68.5" r="2.5" fill="#3056D3" />
                  <circle cx="90.5" cy="90.5" r="2.5" fill="#3056D3" />
                </svg>
              </span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- ====== Hero Section End -->
</template>
