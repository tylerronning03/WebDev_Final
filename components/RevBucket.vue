<template>
    <div class="flex flex-row text-gray-100">
        <div class="rounded-xl border border-grey-100 p-4 flex-1 w-[50vh]">
            <div class="font-semibold text-xl md:text-4xl text-center"> {{ title }}</div>
            <div class="text-xl text-center"> {{ body }}</div>
        </div>
        <div class="rounded-xl border border-grey-100 p-1 flex-1 w-[50vh]">
            <img :src="`${src}`" alt="Its here" class="" v-if="src != ''">
        </div>
    </div>
</template>
<script setup>
    const props = defineProps({
        title: {
            default: ""
        },
        src: {
            default: ''
        },
        body: {
            default: ''
        }
    })
</script>