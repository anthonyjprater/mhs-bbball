<script setup lang="ts">
  import site from '~~/site'
  const { name, logo } = site
</script>
<template>
  <NuxtLink data-pg-name="Logo" class="flex items-center sm:flex-row" to="/">
    <!-- <BaseIcon height="40" class="mt-2" :name="logo" /> -->
    <!-- <svg
      version="1.0"
      xmlns="http://www.w3.org/2000/svg"
      width="2.5em"
      xml:space="preserve"
      fill="currentColor"
      viewBox="0 0 240 240"
      height="2.5em"
      class="mr-2"
    >
      <g transform="translate(17.704 -9.215)">
        <path
          d="M92.45 183.38a61.38 61.38 0 00-30.07 15.35 9.84 9.84 0 01-15.9-3.73 61.65 61.65 0 11115.83-.18 9.87 9.87 0 01-16 3.9 61.43 61.43 0 00-30.07-15.35"
          fill="#99cd31"
          stroke="#475f17"
          stroke-miterlimit="10"
          stroke-width="12"
        />
        <circle
          cx="17.18"
          cy="17.18"
          r="17.18"
          transform="rotate(-22.39 282.115 44.556)"
          fill="#99cd31"
          stroke="#475f17"
          stroke-miterlimit="10"
          stroke-width="12"
        />
        <circle
          cx="17.18"
          cy="17.18"
          r="17.18"
          transform="rotate(-22.39 179.693 -83.499)"
          fill="#99cd31"
          stroke="#475f17"
          stroke-miterlimit="10"
          stroke-width="12"
        />
        <circle
          cx="17.18"
          cy="17.18"
          r="17.18"
          transform="rotate(-67.61 176.48 -54.394)"
          fill="#99cd31"
          stroke="#475f17"
          stroke-miterlimit="10"
          stroke-width="12"
        />
        <circle
          cx="17.18"
          cy="17.18"
          r="17.18"
          transform="rotate(-67.61 119.616 -48.074)"
          fill="#99cd31"
          stroke="#475f17"
          stroke-miterlimit="10"
          stroke-width="12"
        />
        <circle
          cx="3.19"
          cy="3.19"
          r="3.19"
          transform="translate(101.16 179.05)"
          fill="#475f17"
        />
        <path
          d="M89.72 137a20.84 20.84 0 00-20.84 20.84v.16"
          fill="none"
          stroke="#475f17"
          stroke-miterlimit="10"
          stroke-width="12"
        />
        <path
          d="M15.7 47.82h-2.75v-2.76a3.4 3.4 0 00-6.79 0v2.76H3.4a3.4 3.4 0 000 6.79h2.75v2.76a3.4 3.4 0 006.79 0v-2.76h2.76a3.4 3.4 0 000-6.79zm172.43 9.55h-2.76v-2.76a3.4 3.4 0 00-6.79 0v2.76h-2.76a3.4 3.4 0 000 6.79h2.76v2.76a3.4 3.4 0 006.79 0v-2.76h2.76a3.4 3.4 0 000-6.79zM25.25 203.82H22.5v-2.76a3.4 3.4 0 00-6.79 0v2.76h-2.76a3.4 3.4 0 000 6.79h2.75v2.76a3.4 3.4 0 006.79 0v-2.76h2.76a3.4 3.4 0 000-6.79z"
          fill="#475f17"
        />
      </g>
    </svg> -->
    <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="500" zoomAndPan="magnify" viewBox="0 0 375 374.999991" height="500" preserveAspectRatio="xMidYMid meet" version="1.0"><defs><g/><clipPath id="d742f20c70"><path d="M 221.246094 214.484375 L 244.144531 214.484375 L 244.144531 237.382812 L 221.246094 237.382812 Z M 221.246094 214.484375 " clip-rule="nonzero"/></clipPath><clipPath id="246f8b6e04"><path d="M 130.855469 214.484375 L 153.753906 214.484375 L 153.753906 237.382812 L 130.855469 237.382812 Z M 130.855469 214.484375 " clip-rule="nonzero"/></clipPath><clipPath id="571ec5f4b5"><path d="M 130.855469 156.351562 L 153.753906 156.351562 L 153.753906 179.25 L 130.855469 179.25 Z M 130.855469 156.351562 " clip-rule="nonzero"/></clipPath><clipPath id="aff22df5cb"><path d="M 221.246094 156.351562 L 244.144531 156.351562 L 244.144531 179.25 L 221.246094 179.25 Z M 221.246094 156.351562 " clip-rule="nonzero"/></clipPath><clipPath id="6d98928582"><path d="M 148.199219 215.558594 L 165.980469 215.558594 L 165.980469 237.382812 L 148.199219 237.382812 Z M 148.199219 215.558594 " clip-rule="nonzero"/></clipPath><clipPath id="0686fdb071"><path d="M 207.308594 215.15625 L 226.125 215.15625 L 226.125 236.984375 L 207.308594 236.984375 Z M 207.308594 215.15625 " clip-rule="nonzero"/></clipPath></defs><g fill="#040a82" fill-opacity="1"><g transform="translate(130.856247, 237.576078)"><g><path d="M 79.796875 0 L 79.796875 -29.765625 C 79.796875 -33.441406 79.9375 -37.21875 80.21875 -41.09375 C 80.5 -44.976562 80.796875 -48.238281 81.109375 -50.875 C 81.429688 -53.519531 81.632812 -55.203125 81.71875 -55.921875 L 81.234375 -55.921875 L 66 0 L 45.234375 0 L 29.875 -55.796875 L 29.40625 -55.796875 C 29.476562 -55.078125 29.691406 -53.414062 30.046875 -50.8125 C 30.410156 -48.21875 30.753906 -44.976562 31.078125 -41.09375 C 31.398438 -37.21875 31.5625 -33.441406 31.5625 -29.765625 L 31.5625 0 L 7.203125 0 L 7.203125 -82.5625 L 44.640625 -82.5625 L 57.125 -34.921875 L 57.59375 -34.921875 L 69.953125 -82.5625 L 106.078125 -82.5625 L 106.078125 0 Z M 79.796875 0 "/></g></g></g><g clip-path="url(#d742f20c70)"><path fill="#040a82" d="M 221.246094 214.484375 L 244.144531 214.484375 L 244.144531 237.382812 L 221.246094 237.382812 Z M 221.246094 214.484375 " fill-opacity="1" fill-rule="nonzero"/></g><g clip-path="url(#246f8b6e04)"><path fill="#040a82" d="M 130.855469 214.484375 L 153.753906 214.484375 L 153.753906 237.382812 L 130.855469 237.382812 Z M 130.855469 214.484375 " fill-opacity="1" fill-rule="nonzero"/></g><g clip-path="url(#571ec5f4b5)"><path fill="#040a82" d="M 130.855469 156.351562 L 153.753906 156.351562 L 153.753906 179.25 L 130.855469 179.25 Z M 130.855469 156.351562 " fill-opacity="1" fill-rule="nonzero"/></g><g clip-path="url(#aff22df5cb)"><path fill="#040a82" d="M 221.246094 156.351562 L 244.144531 156.351562 L 244.144531 179.25 L 221.246094 179.25 Z M 221.246094 156.351562 " fill-opacity="1" fill-rule="nonzero"/></g><path stroke-linecap="butt" transform="matrix(0, 0.75, -0.75, 0, 138.162197, 179.532365)" fill="none" stroke-linejoin="miter" d="M -0.00148668 1.997513 L 46.034975 1.997513 " stroke="#f6d451" stroke-width="4" stroke-opacity="1" stroke-miterlimit="4"/><path stroke-linecap="butt" transform="matrix(0.75, -0.000000000000000837, 0.000000000000000837, 0.75, 206.88566, 236.995355)" fill="none" stroke-linejoin="miter" d="M 0.00141205 2.000985 L 49.678499 2.000985 " stroke="#f6d451" stroke-width="4" stroke-opacity="1" stroke-miterlimit="4"/><path stroke-linecap="butt" transform="matrix(0.75, 0, 0, 0.75, 129.754479, 154.850423)" fill="none" stroke-linejoin="miter" d="M -0.000763906 2.001519 L 63.99924 2.001519 " stroke="#f6d451" stroke-width="4" stroke-opacity="1" stroke-miterlimit="4"/><path stroke-linecap="butt" transform="matrix(0.75, 0, 0, 0.75, 197.661496, 154.850423)" fill="none" stroke-linejoin="miter" d="M -0.00178569 2.001519 L 63.998219 2.001519 " stroke="#f6d451" stroke-width="4" stroke-opacity="1" stroke-miterlimit="4"/><path stroke-linecap="butt" transform="matrix(0.75, -0.000000000000001674, 0.000000000000001674, 0.75, 129.754479, 237.383612)" fill="none" stroke-linejoin="miter" d="M -0.000763906 1.998934 L 50.030489 1.998934 " stroke="#f6d451" stroke-width="4" stroke-opacity="1" stroke-miterlimit="4"/><path stroke-linecap="butt" transform="matrix(0, 0.75, -0.75, 0, 245.643754, 155.248658)" fill="none" stroke-linejoin="miter" d="M 0.00178959 1.998964 L 32.001792 1.998964 " stroke="#f6d451" stroke-width="4" stroke-opacity="1" stroke-miterlimit="4"/><path stroke-linecap="butt" transform="matrix(0.75, 0, 0, 0.75, 175.265691, 236.98538)" fill="none" stroke-linejoin="miter" d="M -0.0000874545 1.99866 L 32.255123 1.99866 " stroke="#f6d451" stroke-width="4" stroke-opacity="1" stroke-miterlimit="4"/><path stroke-linecap="butt" transform="matrix(0, 0.75, -0.75, 0, 132.754479, 156.350423)" fill="none" stroke-linejoin="miter" d="M 0.00151889 2.000764 L 32.001521 2.000764 " stroke="#f6d451" stroke-width="4" stroke-opacity="1" stroke-miterlimit="4"/><path stroke-linecap="butt" transform="matrix(0, 0.75, -0.75, 0, 132.754479, 214.485382)" fill="none" stroke-linejoin="miter" d="M -0.00134255 2.000764 L 31.99866 2.000764 " stroke="#f6d451" stroke-width="4" stroke-opacity="1" stroke-miterlimit="4"/><path stroke-linecap="butt" transform="matrix(0, 0.75, -0.75, 0, 244.143754, 214.883599)" fill="none" stroke-linejoin="miter" d="M -0.00104932 1.998964 L 31.998953 1.998964 " stroke="#f6d451" stroke-width="4" stroke-opacity="1" stroke-miterlimit="4"/><path stroke-linecap="butt" transform="matrix(-0.75, 0.000000001309, -0.000000001309, -0.75, 138.133385, 181.850422)" fill="none" stroke-linejoin="miter" d="M 0.000763369 1.998479 L 11.188264 1.998479 " stroke="#f6d451" stroke-width="4" stroke-opacity="1" stroke-miterlimit="4"/><path stroke-linecap="butt" transform="matrix(-0.172504, 0.729892, -0.729892, -0.172504, 200.510396, 156.650805)" fill="none" stroke-linejoin="miter" d="M -0.00149025 2.000121 L 66.998219 2.001282 " stroke="#f6d451" stroke-width="4" stroke-opacity="1" stroke-miterlimit="4"/><path stroke-linecap="butt" transform="matrix(0.159335, 0.732879, -0.732879, 0.159335, 178.184803, 155.299502)" fill="none" stroke-linejoin="miter" d="M -0.0013654 2.000105 L 67.657923 1.999058 " stroke="#f6d451" stroke-width="4" stroke-opacity="1" stroke-miterlimit="4"/><path stroke-linecap="butt" transform="matrix(-0.173493, 0.729658, -0.729658, -0.173493, 212.999184, 182.360496)" fill="none" stroke-linejoin="miter" d="M -0.00207515 2.001599 L 76.307006 2.000501 " stroke="#f6d451" stroke-width="4" stroke-opacity="1" stroke-miterlimit="4"/><path stroke-linecap="butt" transform="matrix(0.18549, 0.7267, -0.7267, 0.18549, 163.215476, 181.164787)" fill="none" stroke-linejoin="miter" d="M -0.000906707 2.000259 L 78.387057 2.001787 " stroke="#f6d451" stroke-width="4" stroke-opacity="1" stroke-miterlimit="4"/><path stroke-linecap="butt" transform="matrix(0, 0.75, -0.75, 0, 239.434486, 179.650565)" fill="none" stroke-linejoin="miter" d="M 0.00237166 2.00119 L 46.033625 2.00119 " stroke="#f6d451" stroke-width="4" stroke-opacity="1" stroke-miterlimit="4"/><path stroke-linecap="butt" transform="matrix(-0.75, 0.000000001309, -0.000000001309, -0.75, 244.23888, 215.674863)" fill="none" stroke-linejoin="miter" d="M 0.000798945 1.998775 L 10.651841 1.998775 " stroke="#f6d451" stroke-width="4" stroke-opacity="1" stroke-miterlimit="4"/><path stroke-linecap="butt" transform="matrix(-0.75, -0.000000001309, 0.000000001309, -0.75, 138.142699, 215.556665)" fill="none" stroke-linejoin="miter" d="M -0.00244243 1.997429 L 11.424642 1.997429 " stroke="#f6d451" stroke-width="4" stroke-opacity="1" stroke-miterlimit="4"/><path stroke-linecap="butt" transform="matrix(-0.749974, 0.0061909, -0.0061909, -0.749974, 245.668378, 181.574988)" fill="none" stroke-linejoin="miter" d="M -0.00034747 2.001091 L 11.599034 1.99788 " stroke="#f6d451" stroke-width="4" stroke-opacity="1" stroke-miterlimit="4"/><g clip-path="url(#6d98928582)"><path fill="#040a82" d="M 148.199219 215.558594 L 165.980469 215.558594 L 165.980469 237.363281 L 148.199219 237.363281 Z M 148.199219 215.558594 " fill-opacity="1" fill-rule="nonzero"/></g><g clip-path="url(#0686fdb071)"><path fill="#040a82" d="M 207.308594 215.15625 L 226.125 215.15625 L 226.125 236.984375 L 207.308594 236.984375 Z M 207.308594 215.15625 " fill-opacity="1" fill-rule="nonzero"/></g><path stroke-linecap="butt" transform="matrix(0, 0.75, -0.75, 0, 168.281888, 214.540474)" fill="none" stroke-linejoin="miter" d="M -0.00188188 2.000851 L 34.451245 2.000851 " stroke="#f6d451" stroke-width="4" stroke-opacity="1" stroke-miterlimit="4"/><path stroke-linecap="butt" transform="matrix(0, 0.75, -0.75, 0, 209.558384, 214.10798)" fill="none" stroke-linejoin="miter" d="M 0.00186061 1.99972 L 34.454988 1.99972 " stroke="#f6d451" stroke-width="4" stroke-opacity="1" stroke-miterlimit="4"/><path stroke-linecap="butt" transform="matrix(0.75, -0.000000000000006511, 0.000000000000006511, 0.75, 206.762129, 213.27126)" fill="none" stroke-linejoin="miter" d="M -0.00054743 1.997695 L 6.535911 1.997695 " stroke="#f6d451" stroke-width="4" stroke-opacity="1" stroke-miterlimit="4"/><path stroke-linecap="butt" transform="matrix(0.75, -0.000000000000006511, 0.000000000000006511, 0.75, 162.214359, 214.442945)" fill="none" stroke-linejoin="miter" d="M 0.000645736 1.997948 L 6.537104 1.997948 " stroke="#f6d451" stroke-width="4" stroke-opacity="1" stroke-miterlimit="4"/><path stroke-linecap="butt" transform="matrix(0, -0.75, 0.75, 0, 209.759302, 216.418198)" fill="none" stroke-linejoin="miter" d="M 0.000305385 1.998014 L 45.0576 1.998014 " stroke="#f6d451" stroke-width="4" stroke-opacity="1" stroke-miterlimit="4"/><path stroke-linecap="butt" transform="matrix(0, -0.75, 0.75, 0, 159.861601, 217.402896)" fill="none" stroke-linejoin="miter" d="M 0.000736499 2.00224 L 47.193448 2.00224 " stroke="#f6d451" stroke-width="4" stroke-opacity="1" stroke-miterlimit="4"/>
    </svg>
    <h6
      class="text-primary-600 dark:text-primary-200 font-extrabold font-serif ml-2 mt-4 text-2xl"
    >
      {{ name }}
    </h6>
  </NuxtLink>
</template>
<style scoped>

svg {
  width: 50%;
}

</style>
