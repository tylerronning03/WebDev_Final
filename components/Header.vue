<template>
    <header class="comfortaa bg-slate-800 py-5 px-2">
        <main class="flex flex-row justify-between">
            <div class="text-green-600 text-lg flex-1">
                <nuxt-link class="font-black "to="/">Tomorrow Coding</nuxt-link>
            </div>
            <nav class="flex-1 flex flex-row items-center justify-end gap-6 text-green-600">
                <nuxt-link to="/page1">My Story</nuxt-link>
                <nuxt-link to="/page2">Portfolio</nuxt-link>
                <nuxt-link to="/page3">Services</nuxt-link>
                <nuxt-link to="/page4">Contact</nuxt-link>
            </nav>
        </main>

    </header>
</template>