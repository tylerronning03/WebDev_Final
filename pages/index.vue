<template>
    <!-- Intoduction, Brief Bio, links to portfolio -->
    <Introduction class="">
        <section class="bg-cover bg-center h-[25vh] bg-[url('public/placeHolder.jpg')] border border-black">
            <div class="flex comfortaa font-bold py-5 text-8xl justify-around">
            The Future of Development is Here
            </div>
        </section>
    
        
        <section class="flex flex-row">
            <div class="flex-1">
                <img src="public/placeHolder.jpg" alt="PlaceHolder">
            </div>
        <!--Insert Short Bio-->
            <div class="flex-1 border-2 border-black comfortaa text-xl text-green-600">
            From Game Design, Backend Development, and Web Design I do it all <br>
            C++ C# JavaScript HTML CSS SQL MySQL Git GitHub Unity Unreal
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