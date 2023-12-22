<template>
    <div class="  min-w-full max-w-md">
        <hr class="hr-top">
        <div class="flex justify-center items-center mb-3">
            <span class="text-xs text-center ">Projects from </span>
            <img src="../assets/github-mark.svg" alt="" class="w-3 h-3 ml-1">
        </div>
        <div class="max-h-[50vh] overflow-auto mx-auto w-11/12 pr-3">
            <div class="box">
                <a href="https://github.com/LennerJay/todoApp" target="_blank">
                    <h2 class="font-semibold">1. Todo App</h2>
                    <p class="pl-6 py-3 text-base  max-w-prose">This is a common Todo application system but it was made by 2 frameworks which are the vue 3 js and laravel 10 (api)</p>
                </a>
            </div>
            <div class="box">
                <a href="https://github.com/LennerJay/calculator" target="_blank">
                    <h2 class="font-semibold">2. Calculator</h2>
                    <p class="pl-6 py-3 text-base  max-w-prose">This was my first simple application I made using vue 3</p>
                </a>
            </div>
            <div class="box">
                <a href="https://github.com/LennerJay/" target="_blank">
                    <h2 class="font-semibold">3.  Evalution System</h2>
                    <p class="pl-6 pt-3 text-base  max-w-prose">This is our CAPSTONE PROJECT, we are using Vue 3 js as frontend and Laravel api for the Backend</p>
                    <a class="pl-6 pt-3 text-xs underline" href="https://github.com/LennerJay/frontend" target="_blank">Front-End</a>
                    <a class="pl-2 pt-3 text-xs underline" href="https://github.com/LennerJay/backend" target="_blank">Back-End</a>
                    <p class="pl-6 pb-3 text-base  max-w-prose">expected to be finished: 3rd week of November </p>
                </a>
            </div>
            <div class="box">
                <a href="https://github.com/LennerJay/Chat-Application" target="_blank">
                    <h2 class="font-semibold">4. Chat Application</h2>
                    <p class="pl-6 pt-3 text-base  max-w-prose">This project is still ongoing </p>
                    <p class="pl-6 pb-3 text-base  max-w-prose">expected to be finished: 1st week of January </p>
                </a>
            </div>
            <div class="box">
                <a href="https://github.com/LennerJay/finalProject_2ndSem" target="_blank">
                    <h2 class="font-semibold">5. Online Computer Shop</h2>
                    <p class="pl-6 py-3 text-base  max-w-prose">This was our first big project </p>
                </a>
            </div>
        </div>
        <hr class="hr-btm">
    </div>
</template>


<style scoped>
.hr-top, .hr-btm{
    @apply my-4 border border-gray-400 sm:w-11/12 mx-auto
}
.box{
    @apply border border-black px-5 mb-3 rounded-lg
}
h2{
    @apply mt-2
}
</style>