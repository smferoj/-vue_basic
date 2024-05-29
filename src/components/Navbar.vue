<script setup>
 import {RouterLink} from 'vue-router';
</script>


<template>

   <header class="flex justify-between items-center bg-white shadow-md h-[80px] px-5 lg:px-24 "> 
    <div class="text-3xl font-extrabold text-blue-600 hover:text-blue-700 cursor-pointer">
        <router-link to="/"> BasicVue </router-link>
    </div>
    <nav class="">
        <router-link to="/" class-slate-500 hover:text-slate-700 text-xl font-medium> Home </router-link>
        <router-link to="/about" class-slate-500 hover:text-slate-700 text-xl font-medium> About </router-link>
        <router-link to="/services" class-slate-500 hover:text-slate-700 text-xl font-medium> Services </router-link>
    </nav>
   </header>
</template>


<style>

</style>