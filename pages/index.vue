<template>
  <div class="">
    <section>
      <nav class="relative px-6 py-6 bg-gray-900">
        <div class="flex items-center">
          <ul class="hidden lg:flex lg:items-center lg:w-auto lg:space-x-5">
            <li>
              <a class="text-sm text-gray-300 hover:text-white" href="#"
                >Start</a
              >
            </li>
            <li class="text-gray-800">
              <svg
                class="w-4 h-4 current-fill"
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewbox="0 0 24 24"
                stroke="currentColor"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M12 5v.01M12 12v.01M12 19v.01M12 6a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2z"
                ></path>
              </svg>
            </li>
            <li>
              <a class="text-sm text-white font-bold" href="#">About Us</a>
            </li>
            <li class="text-gray-800">
              <svg
                class="w-4 h-4 current-fill"
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewbox="0 0 24 24"
                stroke="currentColor"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M12 5v.01M12 12v.01M12 19v.01M12 6a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2zm0 7a1 1 0 110-2 1 1 0 010 2z"
                ></path>
              </svg>
            </li>
            <li>
              <a class="text-sm text-gray-300 hover:text-white" href="#"
                >Services</a
              >
            </li>
          </ul>
          <div
            class="lg:absolute lg:top-1/2 lg:left-1/2 lg:transform lg:-translate-y-1/2 lg:-translate-x-1/2"
          >
            <a class="text-white text-3xl font-bold leading-none" href="#"
              >Brand</a
            >
          </div>
          <a
            class="hidden lg:inline-block lg:ml-auto lg:mr-3 py-2 px-6 text-sm text-white font-bold border-2 border-gray-800 hover:border-gray-700 rounded-l-xl rounded-t-xl transition duration-200"
            href="#"
            >Sign In</a
          ><a
            class="hidden lg:inline-block py-2 px-6 bg-green-500 hover:bg-green-600 text-sm text-white font-bold rounded-l-xl rounded-t-xl transition duration-200"
            href="#"
            >Sign up</a
          >
          <div class="lg:hidden ml-auto">
            <button class="navbar-burger flex items-center text-white p-3">
              <svg
                class="block h-4 w-4 fill-current"
                viewbox="0 0 20 20"
                xmlns="http://www.w3.org/2000/svg"
              >
                <title>Mobile menu</title>
                <path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"></path>
              </svg>
            </button>
          </div>
        </div>
      </nav>
      <div class="hidden navbar-menu relative z-50">
        <div class="navbar-backdrop fixed inset-0 bg-gray-800 opacity-25"></div>
        <nav
          class="fixed top-0 left-0 bottom-0 flex flex-col w-5/6 max-w-sm py-6 px-6 bg-white border-r overflow-y-auto"
        >
          <div class="flex items-center mb-8">
            <a class="mr-auto text-3xl font-bold leading-none" href="#"
              >Brand</a
            >
            <button class="navbar-close">
              <svg
                class="h-6 w-6 text-gray-400 cursor-pointer hover:text-gray-500"
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewbox="0 0 24 24"
                stroke="currentColor"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M6 18L18 6M6 6l12 12"
                ></path>
              </svg>
            </button>
          </div>
          <div>
            <ul>
              <li class="mb-1">
                <a
                  class="block p-4 text-sm font-semibold text-gray-400 hover:bg-green-50 hover:text-green-600 rounded"
                  href="#"
                  >Start</a
                >
              </li>
              <li class="mb-1">
                <a
                  class="block p-4 text-sm font-semibold text-gray-400 hover:bg-green-50 hover:text-green-600 rounded"
                  href="#"
                  >About Us</a
                >
              </li>
              <li class="mb-1">
                <a
                  class="block p-4 text-sm font-semibold text-gray-400 hover:bg-green-50 hover:text-green-600 rounded"
                  href="#"
                  >Services</a
                >
              </li>
            </ul>
          </div>
          <div class="mt-auto">
            <div class="pt-6">
              <a
                class="block px-4 py-3 mb-3 text-xs text-center font-semibold leading-none bg-gray-50 hover:bg-gray-100 rounded-l-xl rounded-t-xl"
                href="#"
                >Sign in</a
              ><a
                class="block px-4 py-3 mb-2 leading-loose text-xs text-center text-white font-semibold bg-green-600 hover:bg-green-700 rounded-l-xl rounded-t-xl"
                href="#"
                >Sign Up</a
              >
            </div>
            <p class="my-4 text-xs text-center text-gray-400">
              <span>&copy; 2020 All rights reserved.</span>
            </p>
            <div class="text-center">
              <a class="inline-block px-1" href="#"
                ><img src="@/assets/social/facebook.svg" alt="" /></a
              ><a class="inline-block px-1" href="#"
                ><img src="@/assets/social/twitter.svg" alt="" /></a
              ><a class="inline-block px-1" href="#"
                ><img src="@/assets/social/instagram.svg" alt=""
              /></a>
            </div>
          </div>
        </nav>
      </div>
    </section>

    <section>
      <div class="skew skew-top mr-for-radius">
        <svg
          class="h-8 md:h-12 lg:h-20 w-full text-gray-50"
          viewbox="0 0 10 10"
          preserveaspectratio="none"
        >
          <polygon fill="currentColor" points="0 0 10 10 0 10"></polygon>
        </svg>
      </div>
      <div class="skew skew-top ml-for-radius">
        <svg
          class="h-8 md:h-12 lg:h-20 w-full text-gray-50"
          viewbox="0 0 10 10"
          preserveaspectratio="none"
        >
          <polygon fill="currentColor" points="0 10 10 0 10 10"></polygon>
        </svg>
      </div>
      <div class="py-20 bg-gray-50 radius-for-skewed">
        <div class="container mx-auto px-4">
          <div class="mb-16 flex flex-wrap items-center">
            <div class="w-full lg:w-1/2 text-center lg:text-left">
              <span class="text-green-600 font-bold">Insights</span>
              <h2 class="text-4xl lg:text-5xl font-bold font-heading">
                Latest news
              </h2>
            </div>
            <div class="hidden lg:block text-right w-1/2">
              <a
                class="inline-block py-2 px-6 rounded-l-xl rounded-t-xl bg-green-600 hover:bg-green-700 text-gray-50 font-bold leading-loose transition duration-200"
                href="#"
                >View More Articles</a
              >
            </div>
          </div>
          <div class="mb-8 flex flex-wrap rounded-lg shadow overflow-hidden">
            <div class="w-full lg:w-1/2 rounded-l">
              <img
                class="object-cover"
                src="https://images.unsplash.com/photo-1559827291-72ee739d0d9a?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;ixlib=rb-1.2.1&amp;auto=format&amp;fit=crop&amp;w=968&amp;q=80"
                alt=""
              />
            </div>
            <div class="w-full lg:w-1/2 py-6 lg:pt-10 px-6 rounded-r bg-white">
              <span class="text-sm text-gray-400">24 Jan, 2021</span>
              <h2 class="my-4 text-2xl font-bold">
                Morbi scelerisque nulla et lectus dignissim eleifend nulla eu
                nulla a metus
              </h2>
              <p class="mb-4 text-gray-400 leading-loose">
                Quisque id sagittis turpis. Nulla sollicitudin rutrum eros eu
                dictum. Integer sit amet erat sit amet lectus lacinia mattis.
                Donec est tortor, fermentum at urna a, accumsan suscipit sem.
              </p>
              <a class="text-green-600 hover:text-green-700 font-bold" href="#"
                >Learn More</a
              >
            </div>
          </div>
          <div class="mb-8 flex flex-wrap rounded-lg shadow overflow-hidden">
            <div
              class="w-full lg:w-1/2 py-6 lg:pt-10 px-6 rounded-r bg-white order-1 lg:order-0"
            >
              <span class="text-sm text-gray-400">24 Jan, 2021</span>
              <h2 class="my-4 text-2xl font-bold">
                Morbi scelerisque nulla et lectus dignissim eleifend nulla eu
                nulla a metus
              </h2>
              <p class="mb-4 text-gray-400 leading-loose">
                Quisque id sagittis turpis. Nulla sollicitudin rutrum eros eu
                dictum. Integer sit amet erat sit amet lectus lacinia mattis.
                Donec est tortor, fermentum at urna a, accumsan suscipit sem.
              </p>
              <a class="text-green-600 hover:text-green-700 font-bold" href="#"
                >Learn More</a
              >
            </div>
            <div class="w-full lg:w-1/2 rounded-l order-0 lg:order-1">
              <img
                class="object-cover"
                src="https://images.unsplash.com/photo-1559827291-72ee739d0d9a?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;ixlib=rb-1.2.1&amp;auto=format&amp;fit=crop&amp;w=968&amp;q=80"
                alt=""
              />
            </div>
          </div>
          <div class="mb-8 flex flex-wrap rounded-lg shadow overflow-hidden">
            <div class="w-full lg:w-1/2 rounded-l">
              <img
                class="object-cover"
                src="https://images.unsplash.com/photo-1559827291-72ee739d0d9a?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;ixlib=rb-1.2.1&amp;auto=format&amp;fit=crop&amp;w=968&amp;q=80"
                alt=""
              />
            </div>
            <div class="w-full lg:w-1/2 py-6 lg:pt-10 px-6 rounded-r bg-white">
              <span class="text-sm text-gray-400">24 Jan, 2021</span>
              <h2 class="my-4 text-2xl font-bold">
                Morbi scelerisque nulla et lectus dignissim eleifend nulla eu
                nulla a metus
              </h2>
              <p class="mb-4 text-gray-400 leading-loose">
                Quisque id sagittis turpis. Nulla sollicitudin rutrum eros eu
                dictum. Integer sit amet erat sit amet lectus lacinia mattis.
                Donec est tortor, fermentum at urna a, accumsan suscipit sem.
              </p>
              <a class="text-green-600 hover:text-green-700 font-bold" href="#"
                >Learn More</a
              >
            </div>
          </div>
          <div class="mb-8 flex flex-wrap rounded-lg shadow overflow-hidden">
            <div
              class="w-full lg:w-1/2 py-6 lg:pt-10 px-6 rounded-r bg-white order-1 lg:order-0"
            >
              <span class="text-sm text-gray-400">24 Jan, 2021</span>
              <h2 class="my-4 text-2xl font-bold">
                Morbi scelerisque nulla et lectus dignissim eleifend nulla eu
                nulla a metus
              </h2>
              <p class="mb-4 text-gray-400 leading-loose">
                Quisque id sagittis turpis. Nulla sollicitudin rutrum eros eu
                dictum. Integer sit amet erat sit amet lectus lacinia mattis.
                Donec est tortor, fermentum at urna a, accumsan suscipit sem.
              </p>
              <a class="text-green-600 hover:text-green-700 font-bold" href="#"
                >Learn More</a
              >
            </div>
            <div class="w-full lg:w-1/2 rounded-l order-0 lg:order-1">
              <img
                class="object-cover"
                src="https://images.unsplash.com/photo-1559827291-72ee739d0d9a?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;ixlib=rb-1.2.1&amp;auto=format&amp;fit=crop&amp;w=968&amp;q=80"
                alt=""
              />
            </div>
          </div>
          <div class="mb-16 flex flex-wrap rounded-lg shadow overflow-hidden">
            <div class="w-full lg:w-1/2 rounded-l bg-white">
              <img
                class="object-cover"
                src="https://images.unsplash.com/photo-1559827291-72ee739d0d9a?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&amp;ixlib=rb-1.2.1&amp;auto=format&amp;fit=crop&amp;w=968&amp;q=80"
                alt=""
              />
            </div>
            <div class="w-full lg:w-1/2 py-6 lg:pt-10 px-6 rounded-r bg-white">
              <span class="text-sm text-gray-400">24 Jan, 2021</span>
              <h2 class="my-4 text-2xl font-bold">
                Morbi scelerisque nulla et lectus dignissim eleifend nulla eu
                nulla a metus
              </h2>
              <p class="mb-4 text-gray-400 leading-loose">
                Quisque id sagittis turpis. Nulla sollicitudin rutrum eros eu
                dictum. Integer sit amet erat sit amet lectus lacinia mattis.
                Donec est tortor, fermentum at urna a, accumsan suscipit sem.
              </p>
              <a class="text-green-600 hover:text-green-700 font-bold" href="#"
                >Learn More</a
              >
            </div>
          </div>
          <div class="flex justify-center">
            <nav
              class="flex items-center bg-white shadow rounded"
              aria-label="Pagination"
            >
              <a class="px-4 text-gray-400 hover:text-gray-500" href="#">
                <svg
                  class="w-4 h-4"
                  xmlns="http://www.w3.org/2000/svg"
                  fill="none"
                  viewbox="0 0 24 24"
                  stroke="currentColor"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M10 19l-7-7m0 0l7-7m-7 7h18"
                  ></path></svg
              ></a>
              <div class="p-2 border-r border-l text-gray-500">
                <a
                  class="mx-1 px-2 rounded hover:bg-gray-50 hover:text-gray-800"
                  href="#"
                  >1</a
                ><a
                  class="mx-1 px-2 rounded bg-gray-50 text-gray-800 font-bold"
                  href="#"
                  >2</a
                ><a
                  class="mx-1 px-2 rounded hover:bg-gray-50 hover:text-gray-800"
                  href="#"
                  >3</a
                ><a
                  class="mx-1 px-2 rounded hover:bg-gray-50 hover:text-gray-800"
                  href="#"
                  >4</a
                >
                <span class="mx-3">...</span>
                <a
                  class="mx-1 px-2 rounded hover:bg-gray-50 hover:text-gray-800"
                  href="#"
                  >16</a
                ><a
                  class="mx-1 px-2 rounded hover:bg-gray-50 hover:text-gray-800"
                  href="#"
                  >17</a
                ><a
                  class="mx-1 px-2 rounded hover:bg-gray-50 hover:text-gray-800"
                  href="#"
                  >18</a
                >
              </div>
              <a class="px-4 text-gray-400 hover:text-gray-500" href="#">
                <svg
                  class="w-4 h-4"
                  xmlns="http://www.w3.org/2000/svg"
                  fill="none"
                  viewbox="0 0 24 24"
                  stroke="currentColor"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M14 5l7 7m0 0l-7 7m7-7H3"
                  ></path></svg
              ></a>
            </nav>
          </div>
        </div>
      </div>
      <div class="skew skew-bottom mr-for-radius">
        <svg
          class="h-8 md:h-12 lg:h-20 w-full text-gray-50"
          viewbox="0 0 10 10"
          preserveaspectratio="none"
        >
          <polygon fill="currentColor" points="0 0 10 0 0 10"></polygon>
        </svg>
      </div>
      <div class="skew skew-bottom ml-for-radius">
        <svg
          class="h-8 md:h-12 lg:h-20 w-full text-gray-50"
          viewbox="0 0 10 10"
          preserveaspectratio="none"
        >
          <polygon fill="currentColor" points="0 0 10 0 10 10"></polygon>
        </svg>
      </div>
    </section>
  </div>
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
