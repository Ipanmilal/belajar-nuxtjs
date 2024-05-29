<template>
    <header class="flex items-center bg-black w-full border-state-200 py-6">
        <div class="container">
            <div class="flex justify-between items-center gap-18">
                <div class="gap-6 px-6">
                    <NuxtLink to="/" class="flex items-center text-white text-2xl font-bold">
                        <img src="/asset/images/verb.png" class="h-6 w-15 gap-20" alt="">
                        
                    </NuxtLink>
                </div>
                <nav class="flex items-center gap-6">
                    <NuxtLink to="/" class="text-base text-white">Home</NuxtLink>
                    <NuxtLink to="/product" class="text-base text-white">Info</NuxtLink>
                    <NuxtLink to="/about" class="text-base text-white">About</NuxtLink>
                    <NuxtLink to="/cart" class="text-base text-white">Histori</NuxtLink>
                    <NuxtLink to="/about" class="bg-red-700 hover:bg-red-500 font-bold py-2 px-4 rounded text-white">Play Now</NuxtLink>
                </nav>
            </div>
        </div>
    </header>
</template>