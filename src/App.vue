<template>
  <!-- navigation -->
  <header>
    <h1
      class="text-3xl font-bold font-freckle p-5 text-yellow-100 bg-yellow-500"
    >
      siggi_ai
    </h1>
  </header>

  <!-- first slide -->
  <div
    class="sticky h-screen flex flex-col items-center justify-center bg-gradient-to-b from-orange-500 to-orange-700"
  >
    <p class="text-2xl font-bold -mt-72 p-7 text-fuchsia-800 w-11/12">
      web-development <br />+ design 🌳
    </p>

    <h1
      class="font-mono font-semibold text-xl subpixel-antialiased md:text-3xl p-7 -mb-8 text-yellow-200 w-4/5 md:w-2/4"
    >
      Hello World!
    </h1>
    <h2
      class="text-xl font-mono md:text-2xl p-7 text-yellow-100 w-4/5 md:w-2/4"
    >
      I am
      <a href="https://github.com/siggi-ai"
        ><b class="text-yellow-300">siggi_ai</b></a
      >, a web-developer based in Hamburg.<br />
      <br />
      And I love combining logic and creative design, to make
      <b class="text-lime-700">sustainable, accessible</b>, and
      <b class="text-lime-700">user-friendly</b> websites and applications.
    </h2>
  </div>

  <!-- second slide -->
  <div
    class="sticky top-0 h-screen flex flex-col items-center justify-center bg-gradient-to-b from-indigo-800 to-purple-800 text-white"
  >
    <ul class="circles">
      <li></li>
      <li></li>
      <li></li>
      <li></li>
      <li></li>
      <li></li>
      <li></li>
      <li></li>
      <li></li>
      <li></li>
    </ul>
    <!-- triangle -->
    <div
      class="mt-16 w-0 h-0 border-l-[100px] border-l-transparent border-t-[150px] border-t-green-500 border-r-[100px] border-r-transparent"
    ></div>
    <p class="text-yellow-100 text-2xl font-mono">Vue.js</p>
    <p
      class="text-1xl md:text-2xl font-mono p-7 text-yellow-100 w-3/4 md:w-2/4"
    >
      I use HTML, CSS, JavaScript, Vue.js and tailwind to build dynamic websites
      and applications.
    </p>
    <!-- circle -->
    <div class="flex">
      <button
        class="rounded-full w-44 h-44 bg-pink-700 text-1xl font-bold text-yellow-100"
      >
        HTML CSS JavaScript
      </button>
    </div>
  </div>

  <!-- third slide -->
  <div
    class="sticky top-0 h-screen flex flex-col items-center justify-center bg-gradient-to-b from-slate-800 to-pink-800 text-white"
  >
    <button
      class="p-10 sh-100 w-44 h-44 bg-yellow-100 font-bold text-gray-500 mb-28"
    >
      projects
    </button>
  </div>

  <!-- fourth slide -->
  <div
    class="sticky top-0 h-screen flex flex-col items-center justify-center bg-gradient-to-b from-purple-800 to-pink-800 text-white"
  >
    <!-- LOGOS -->
    <a href="https://github.com/siggi-ai"
      ><img src="/images/Github.png" alt="Logo" class="w-20 mb-10"
    /></a>
    <a href="https://vuejs.org/"
      ><img src="/images/Vue-Logo.png" alt="Logo" class="w-20 mb-10"
    /></a>
    <a href="https://tailwindcss.com/"
      ><img src="/images/tailwind-icon.png" alt="Logo" class="w-20 mb-10"
    /></a>
    <a href="https://hamburgcodingschool.com/"
      ><img src="/images/hcs.png" alt="Logo" class="w-44 mb-10"
    /></a>
  </div>

  <footer class="w-full text-center bg-black text-teal-400 p-3 mt-28">
    created with ♥ by siggi_ai in 2024
  </footer>
</template>

<script>
export default {
  setup() {
    return {};
  },
};
</script>

<style scoped></style>
