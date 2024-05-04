<template>
    <!-- Intoduction, Brief Bio, links to portfolio -->
    <Introduction>
        <section class="flex flex-col bg-cover bg-center h-[40vh] bg-[url('public/Tecky.jpeg')] border border-black justify-center items-center">
            <div class="comfortaa font-bold py-5 text-lg md:text-4xl lg:text-7xl text-center text-emerald-500">
                The Future of Development is Here
            </div>
            <LanguageDropdown class="hidden md:block"/>
            <LanguageBar class="md:hidden"/>
        </section>
       
        <div class="hero min-h-[80vh] bg-slate-700">
            <div class="hero-content flex-col lg:flex-row">
                <img src="public/Logo.png" class="max-w-[45vh] rounded-lg shadow-2xl" />
                <div>
                    <h1 class="text-5xl font-bold comfortaa text-emerald-500">Welcome to Tommorow Coding</h1>
                    <p class="py-6 text-xl text-slate-200">From Game Design, Backend Development, Databases, and Web Design <br> It's all done here!</p>
                    <nuxt-link to="/page2"><button class="btn btn-primary border border-black hover:bg-white bg-emerald-500 text-xl">Learn More</button></nuxt-link>
                    
                </div>
            </div>
        </div>
    </Introduction> 
</template>
<script setup>
useHead ({
    title: 'Tomorrow Coding',
    meta: [
    { name: 'About, projects, and more', content: 'Home of Tomorrow Coding' }
  ],
});
</script>