<template>
    <div class="flex flex-row w-full h-[30vh] md:h-[80vh] px-3 gap-3">
        <div class="flex flex-col items-center justify-center">
          <img :src="`${logo}`" alt="logo">
          <div class="text-xl text-white text-center py-2">{{ body }}</div>
        </div>
        <img :src="`${img}`" alt="Image" class="overflow-hidden w-full h-full object-cover">
      </div>
</template>
<script setup>
    const props = defineprops({
        img: {
            default: ''
        },
        body: {
            default: ''
        },
        logo: {
            default: ''
        }
    })
</script>