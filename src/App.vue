<template>

  <div>
  <!-- navigation -->
    <header class="">
      <h1
        class="text-3xl font-bold font-freckle p-5 text-yellow-500 bg-yellow-800 flex flex-row"
      >
        <div>siggi_ai</div>&nbsp;&nbsp;&nbsp;
        <div class="flex flex-row">
        <a href="https://github.com/siggi-ai"
          ><img src="/images/Github.png" alt="Logo-github" class="w-10"
        /></a>&nbsp;&nbsp;
        <a href="https://vuejs.org/"
          ><img src="/images/Vue-Logo.png" alt="Logo-Vue.js" class="w-10 mt-1"
        /></a>&nbsp;&nbsp;
        <a href="https://tailwindcss.com/"
          ><img src="/images/tailwind-icon.png" alt="Logo-tailwind" class="w-10 mt-2"
        /></a>&nbsp;&nbsp;
        <a href="https://hamburgcodingschool.com/"
          ><img src="/images/hcs.png" alt="Logo-coding-school" class="w-20 mt-1"
        /></a>
      </div>
      </h1>
      
    </header>
    <!-- first slide -->
    <div
      class="sticky h-screen flex flex-col items-center justify-center bg-gradient-to-b from-yellow-500 to-orange-600 w-screen"
    >
        <p class="text-2xl font-bold -mt-[550px] absolute p-7 text-fuchsia-800 w-11/12">
          web-development <br />+ design 🌳
        </p>
      <h1
        class="font-mono font-semibold text-xl subpixel-antialiased md:text-3xl p-7 -mb-8 text-yellow-200 w-4/5 md:w-2/4 md:-mt-[150px]"
      >
        Hello World!
      </h1>
      <h2
        class="text-xl font-mono md:text-2xl p-7 text-yellow-100 w-4/5 md:w-2/4"
      >
        I am
        <a href="https://github.com/siggi-ai"
          ><b class="text-yellow-300">siggi_ai</b></a
        >, a web-developer based in Hamburg.
        <a href="mailto:smiley.face@gmx.de"  class="text-red-700 md:text-2xl font-mono font-bold">--> mail ✉️</a>
        <br />
        <br />
        And I love combining logic and creative design, to make
         websites and applications.
         
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
        Among other tools, I use HTML, CSS, JavaScript, Vue.js and tailwind to build
        <span
          class="text-red-500 mx-1 font-extrabold text-2xl relative inline-block stroke-current"
        >
          dynamic
          <svg
            class="absolute -bottom-0.5 w-full max-h-1.5"
            viewBox="0 0 55 5"
            xmlns="http://www.w3.org/2000/svg"
            preserveAspectRatio="none"
          >
            <path
              d="M0.652466 4.00002C15.8925 2.66668 48.0351 0.400018 54.6853 2.00002"
              stroke-width="2"
            ></path>
          </svg>
        </span>
        websites and applications.
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
    
    <footer class="w-full text-center bg-black text-teal-400 font-mono p-3">
      created with ♥ by siggi_ai in 2024
    </footer>

  </div>
</template>

<script>
import Three from "./components/Three.vue";
export default {
  name: "Home",
  components: { Three },
};
</script>

<style scoped>
.three-animation {
  margin-top: 170px;
  margin-left: 180px;
}

/* really cool ghost-css to find error in layout!!! */
/* * {
  background: #000 !important;
  color: #0f0 !important;
  outline: solid #f00 1px !important;
} */
</style>
