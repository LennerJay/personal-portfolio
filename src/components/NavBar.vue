<template>
    <nav>
        <router-link :to="{name:'home'}">Home</router-link>
        <router-link :to="{name:'about'}">About</router-link>
        <router-link :to="{name:'project'}">Project</router-link>
    </nav>
</template>

<style scoped>
    /* nav{
        @apply border border-black 
    } */
    a{
        @apply m-4 px-3 py-1  bg-cyan-500 hover:bg-cyan-600 rounded-full  text-white
    }
    .router-link-active{
        @apply font-bold scale-0
    }
</style>
