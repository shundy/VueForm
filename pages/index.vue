<script setup lang="ts">
useHead({
    title: useRuntimeConfig().public.title,
    meta: [
        { name: 'description', content: 'Nuxt 3' },
    ],
})
</script>

<template>
    <div>
        こんにちは、{{ $config.public.title }}
    </div>
</template>
