<template>
     <div class="content">
        <hr class="hr-top">
        <img src="../assets/profile.jpg" alt="profile image" class="profileImage">
        <h1 class="name">
            Lenner Jay S. Soliano
        </h1>
        <hr class="border-1 my-4 border-gray-800 w-14 mx-auto">
        <p class="work">Web Developer</p>
        <hr class="hr-btm">
     </div>
</template>

<style scoped>
.hr-top, .hr-btm{
    @apply my-4 border border-gray-400 sm:w-11/12 mx-auto md:w-7/12
}
.profileImage{
    @apply w-[180px] h-[180px] sm:w-[200px] sm:h-[200px] mx-auto rounded-full shadow-md
}
.content{
    @apply m-1
}
.name{
    @apply  mt-8 mb-4 text-center text-3xl sm:text-4xl uppercase font-bold dark:text-white
}
.work{
    @apply text-center text-xl sm:text-2xl text-gray-700 dark:text-gray-300
}

/* h1{
  @apply text-3xl font-bold underline;
} */
/* h1{
    width: max-content;
    font-size: 100px;
    position: relative;
    cursor: pointer;
    margin: 100px auto;
    
}
h1::after{
    content: "";
    position: absolute;
    bottom: -5px;
    height: 4px;
    width: 100%;
    left: 0;
    background-color: #000;
    transition: 0.3s ease-in-out;
    transform: scaleX(0);
}
h1:hover::after{
    transform: scaleX(1);
} */
</style>