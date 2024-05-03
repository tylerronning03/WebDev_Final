<template>
    <header class="comfortaa bg-slate-800 py-5 px-2">
        <main class="flex flex-row justify-between">
            <div class=" text-white text-xl font-black flex-1">
                <nuxt-link class="flex flex-row font-black items-center" to="/">
                    <img src="public/Logo.png" class="h-12 px-3" alt="PlaceHolder">
                    <div class="hover:text-emerald-500">Tomorrow Coding</div>
                </nuxt-link>
                
            </div>
            
                <nav class="flex-1 flex flex-row items-center justify-end gap-6 text-white px-3">
                    <nuxt-link to="/page1" class="hover:text-emerald-500">My Story</nuxt-link>
                    <nuxt-link to="/page2" class="hover:text-emerald-500">Portfolio</nuxt-link>
                    <nuxt-link to="/page3" class="hover:text-emerald-500">Services</nuxt-link>
                    <nuxt-link to="/page4" class="hover:text-emerald-500">Contact</nuxt-link>
                </nav>
        </main>

    </header>
</template>