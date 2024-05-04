<template>
    <header class="comfortaa bg-slate-800 py-5 px-2">
        <main class="flex flex-row justify-between">
            <div class="text-white text-xl font-black flex-1  max-w-25">
                <nuxt-link class=" flex flex-row font-black items-center" to="/">
                    <img src="public/Logo.png" class="h-12 px-3" alt="PlaceHolder">
                    <div class="hover:text-emerald-500">Tomorrow Coding</div>
                </nuxt-link>
                
            </div>
            <div class="dropdown dropdown-end px-4">
                <div tabindex="0" role="button" class="btn m-1 text-white hover:text-emerald-500">Links</div>
                <ul tabindex="0" class="dropdown-content z-[1] menu p-2 shadow bg-base-100 rounded-box w-52">
                    <li><nuxt-link to="/page1" class="hover:text-emerald-500">Our Story</nuxt-link></li>
                    <li><nuxt-link to="/page2" class="hover:text-emerald-500">Portfolio</nuxt-link></li>
                    <li><nuxt-link to="/page3" class="hover:text-emerald-500">Services</nuxt-link></li>
                    <li><nuxt-link to="/page4" class="hover:text-emerald-500">Contact</nuxt-link></li>
                </ul>
            </div>
        </main>

    </header>
</template>