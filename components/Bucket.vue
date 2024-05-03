<template>
    <div class="text-gray-100 rounded-xl border border-grey-100 p-4 flex-1">
        <img :src="`${src}`" alt="Its here" class="h-auto" v-if="src != ''">
        <div class="font-bold text-3sl"
        :class="`bg-${src}`"> {{ title }}</div>
    </div>
</template>
<script setup>
    const props = defineProps({
        title: {
            default: ""
        },
        src: {
            default: ''
        }
    })
</script>