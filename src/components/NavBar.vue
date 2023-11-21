<template>
    <nav class="flex bg-gray-400 shadow-xl px-6 py-5">
        <h1 class="font-serif text-2xl text-shadow-md">Portfolio</h1>
        <ul class="flex w-full space-x-5 font-bold text-lg justify-end">
            <li class="hover:text-blue-600 hover:underline transition">
                <router-link to="/">Home</router-link>
            </li>
            <li class="hover:text-blue-600 hover:underline transition">
                <router-link to="/about">À propos</router-link>
            </li>
        </ul>
    </nav>
</template>
