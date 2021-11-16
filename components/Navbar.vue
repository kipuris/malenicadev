<template>
  <header class="bg-gray-800">
    <nav class="relative">
      <div class="flex py-8 px-4 lg:px-8 justify-between items-center">
        <a class="text-2xl text-whiteAlpha-900 font-bold" href="#">
          <img
            class="h-7"
            src="@/assets/images/malenicadev logo.png"
            alt=""
            width="auto"
        /></a>
        <div class="lg:hidden">
          <button class="p-2 navbar-burger">
            <svg
              class="w-10 h-3"
              width="39"
              height="13"
              viewbox="0 0 39 13"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
            >
              <rect width="39" height="2" rx="1" fill="#C4C4C4"></rect>
              <rect
                x="19"
                y="11"
                width="20"
                height="2"
                rx="1"
                fill="#C4C4C4"
              ></rect>
            </svg>
          </button>
        </div>
        <div
          class="hidden lg:block absolute top-1/2 left-1/2 transform -translate-y-1/2 -translate-x-1/2"
        >
          <ul class="flex items-center text-whiteAlpha-900 space-x-10">
            <li>
              <a class="text-whiteAlpha-900 font-bold text-lg" href="#"
                >About</a
              >
            </li>
            <span>
              <svg
                width="5"
                height="5"
                viewbox="0 0 5 5"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <circle cx="2.5" cy="2.5" r="2.5" fill="#726B6B"></circle></svg
            ></span>
            <li>
              <a class="text-whiteAlpha-900 font-bold text-lg" href="#"
                >Projects</a
              >
            </li>
            <span>
              <svg
                width="5"
                height="5"
                viewbox="0 0 5 5"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <circle cx="2.5" cy="2.5" r="2.5" fill="#726B6B"></circle></svg
            ></span>
            <li>
              <a class="text-whiteAlpha-900 font-bold text-lg" href="#"
                >Services</a
              >
            </li>
            <span>
              <svg
                width="5"
                height="5"
                viewbox="0 0 5 5"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <circle cx="2.5" cy="2.5" r="2.5" fill="#726B6B"></circle></svg
            ></span>
            <li>
              <a class="text-whiteAlpha-900 font-bold text-lg" href="#">Blog</a>
            </li>
          </ul>
        </div>
        <div class="hidden lg:block">
          <a
            class="inline-block px-12 py-4 text-whiteAlpha-900 font-bold border border-gray-200 hover:border-white rounded-full"
            href="#"
            >Work with us</a
          >
        </div>
      </div>
    </nav>
    <div
      class="hidden navbar-menu fixed top-0 left-0 bottom-0 w-5/6 max-w-sm z-50"
    >
      <div class="navbar-backdrop fixed inset-0 bg-gray-800 opacity-80"></div>
      <nav
        class="relative flex flex-col py-8 h-full w-full bg-white overflow-y-auto"
      >
        <div class="flex items-center mb-16 pr-6">
          <a class="ml-10 mr-auto text-2xl text-gray-800 font-bold" href="#">
            <img
              class="h-7"
              src="@/assets/images/malenicadev logo.png"
              alt=""
              width="auto"
          /></a>
        </div>
        <div>
          <ul>
            <li class="mb-1 px-10">
              <a
                class="block pl-8 py-4 text-xl text-gray-800 hover:bg-blueGray-50 rounded-xl"
                href="#"
                >About</a
              >
            </li>
            <li class="mb-1 px-10">
              <a
                class="block pl-8 py-4 text-xl text-gray-800 hover:bg-blueGray-50 rounded-xl"
                href="#"
                >Projects</a
              >
            </li>
            <li class="mb-1 px-10">
              <a
                class="block pl-8 py-4 text-xl text-gray-800 hover:bg-blueGray-50 rounded-xl"
                href="#"
                >Services</a
              >
            </li>
            <li class="mb-1 px-10">
              <a
                class="block pl-8 py-4 text-xl text-gray-800 hover:bg-blueGray-50 rounded-xl"
                href="#"
                >Blog</a
              >
            </li>
          </ul>
        </div>
        <div class="mt-auto px-10">
          <div class="pt-6">
            <a
              class="block mb-4 py-4 px-12 text-gray-800 text-center font-bold border border-gray-50 hover:border-gray-100 rounded-full"
              href="#"
              >Sign in</a
            ><a
              class="block py-4 px-12 text-whiteAlpha-900 text-center font-bold bg-blue-500 hover:bg-blue-600 rounded-full transition duration-200"
              href="#"
              >Work with us</a
            >
          </div>
          <p class="mt-6 mb-4 text-lg text-center">
            <span>2021 © Zospace. All rights reserved.</span>
          </p>
        </div>
      </nav>
    </div>
  </header>
</template>

<script>
export default {
  mounted() {
    // Burger menus
    // open
    const burger = document.querySelectorAll('.navbar-burger')
    const menu = document.querySelectorAll('.navbar-menu')

    if (burger.length && menu.length) {
      for (let i = 0; i < burger.length; i++) {
        burger[i].addEventListener('click', function () {
          for (let j = 0; j < menu.length; j++) {
            menu[j].classList.toggle('hidden')
          }
        })
      }
    }

    // close
    const close = document.querySelectorAll('.navbar-close')
    const backdrop = document.querySelectorAll('.navbar-backdrop')

    if (close.length) {
      for (let i = 0; i < close.length; i++) {
        close[i].addEventListener('click', function () {
          for (let j = 0; j < menu.length; j++) {
            menu[j].classList.toggle('hidden')
          }
        })
      }
    }

    if (backdrop.length) {
      for (let i = 0; i < backdrop.length; i++) {
        backdrop[i].addEventListener('click', function () {
          for (let j = 0; j < menu.length; j++) {
            menu[j].classList.toggle('hidden')
          }
        })
      }
    }
  },
}
</script>

<style></style>
