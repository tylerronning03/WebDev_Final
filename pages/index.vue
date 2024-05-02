<template>
    <!-- Intoduction, Brief Bio, links to portfolio -->
    <Introduction>
        <section class="bg-cover bg-center h-[25vh] bg-[url('public/placeHolder.jpg')] border border-black">
            <div class="flex comfortaa font-bold py-5 text-7xl justify-around text-green-600">
            The Future of Development is Here
            </div>
        </section>
    
        
        <section class="flex flex-row">
            <div class="flex px-5 py-2 justify-between">
                <img src="public/Logo.jpg" class="h-60" alt="PlaceHolder">
            </div>
        <!--Insert Short Bio-->
            <div class="flex-1 border-2 border-black comfortaa text-3xl text-green-600 py-4 px-2">
            From Game Design, Backend Development, Databases, and Web Design I do it all <br>
            <br>
            C++ C# JavaScript HTML CSS SQL Git GitHub Unity Unreal
            </div>
        </section>
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