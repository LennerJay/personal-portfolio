<template>
    <div class="container">
      <NavBar/>
      <router-view v-slot="{Component}">
        <transition name="fade" mode="out-in">
            <component :is="Component"/>
        </transition>
    </router-view> 
      <Footer></Footer>
    </div>
</template>

<script setup>
import NavBar from './components/NavBar.vue';
import Footer from './components/Footer.vue';
</script>


<style scoped>
.container{
  @apply w-full bg-blue-100 min-h-screen p-2 flex flex-col justify-center items-center dark:bg-[#0F172A] duration-500 transition-all ease-in-out;
}
.fade-enter-active,
.fade-leave-active {
  transition: opacity 0.5s ease;
}

.fade-enter-from,  
.fade-leave-to {
  opacity: 0;
}
</style>