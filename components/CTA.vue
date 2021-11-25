<template>
  <section class="py-20">
    <div class="container mx-auto px-4 xl:px-0 shadow-glow-pink">
      <div class="cta-box">
        <div class="flex flex-wrap items-center">
          <div class="w-full flex flex-col lg:flex-row justify-between items-center mb-8">
            <h3 class="font-bold text-4xl text-gray-800">Book a call</h3>
            <div class="inline-flex lg:flex lg:flex-col items-end mt-2 lg:mt-0">
              <svg
                class="h-6 w-6 lg:h-9 lg:w-9"
                viewBox="0 0 139 187"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M42.1889 54.4026C42.1889 39.316 54.444 27.0608 69.509 27.0608C84.574 27.0608 96.8508 39.316 96.8508 54.4026V83.2574H123.912V54.4026C123.912 24.4023 99.5093 0 69.509 0C39.5087 0 15.1064 24.4023 15.1064 54.4026V83.2574H42.1672V54.4026H42.1889Z"
                  fill="#78A3AD"
                />
                <path
                  d="M96.8526 83.2791V83.6033H42.1906V83.2791H15.1082V83.6033H11.6932C5.2306 83.6033 0 88.8339 0 95.2749V175.204C0 181.645 5.2306 186.897 11.6932 186.897H127.307C133.769 186.897 139 181.666 139 175.204V95.2749C139 88.8339 133.769 83.6033 127.307 83.6033H123.892V83.2791H96.8526V83.2791Z"
                  fill="#FCC21B"
                />
                <path
                  d="M81.8512 127.588C81.8512 120.78 76.318 115.246 69.5096 115.246C62.7012 115.246 57.168 120.758 57.168 127.588C57.168 132.754 60.3668 137.185 64.8842 139L64.6032 140.167L60.6262 157.178H78.4146L74.4376 140.167L74.1782 139C76.4497 138.08 78.3941 136.502 79.7615 134.468C81.1288 132.435 81.8566 130.039 81.8512 127.588V127.588Z"
                  fill="#2F2F2F"
                />
              </svg>
              <span class="mt-2 ml-2 lg:ml-0 text-sm">Full refund if not satisfied</span>
            </div>
          </div>
          <div class="w-full">
            <p class="text-lg">
              Fully custom blazing fast website with ongoing conversion rate optimization
              schedule to maximize ROI.
            </p>
          </div>
          <ul class="block lg:grid grid-cols-2 gap-4 w-full my-8">
            <li
              v-for="benefit in benefits"
              :key="benefit"
              class="flex items-start lg:items-center my-4 lg:my-2"
            >
              <svg
                width="24"
                height="24"
                viewBox="0 0 512 512"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M448 256C448 150 362 64 256 64C150 64 64 150 64 256C64 362 150 448 256 448C362 448 448 362 448 256Z"
                  stroke="#0FA958"
                  stroke-width="32"
                  stroke-miterlimit="10"
                />
                <path
                  d="M352 176L217.6 336L160 272"
                  stroke="#0FA958"
                  stroke-width="32"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
              </svg>

              <span class="ml-4 text-lg w-5/6">{{ benefit }}</span>
            </li>
          </ul>
          <div class="w-full flex items-center justify-center mt-8">
            <a
              class="inline-block px-12 py-5 text-2xl text-whiteAlpha-900 font-black bg-pink-500 hover:bg-pink-600 rounded-full transition-shadow shadow-glow-pink hover:shadow-glow-pink-intense"
              href="#"
              >Book a call</a
            >
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      benefits: [
        'Design revisions until 100% satisfaction',
        'Incredibly fast website',
        'Scale easy with component based architecture',
        'Secure by default',
        'Conversion rate optimization',
        'Constant iterations based on results',
        'Monitoring and tracking conversions',
        'Cost effective hosting',
      ],
    }
  },
}
</script>

<style scoped>
.cta-box {
  @apply px-8 py-12 rounded-xl shadow-2xl border border-gray-300 relative bg-white bg-opacity-100;
}

.cta-box:before {
  content: '';
  @apply absolute left-0 rounded-t-xl border border-t-8 border-pink-700 block w-full;
  top: -1px;
}

.cta-box--glass {
  backdrop-filter: blur(6px);
}

.cta-box--glass-xl {
  backdrop-filter: blur(36px);
}
</style>
