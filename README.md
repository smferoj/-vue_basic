npm init vite my-project
cd my-project
npm install
npm install -D tailwindcss@latest postcss@latest autoprefixer@latest 
npx tailwindcss init -p
/** @type {import('tailwindcss').Config} */
export default {
  content: [
    "./index.html",
    "./src/**/*.{vue,js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}

<script setup>
 
</script>


<template>
  
</template>


<style>

</style>

