<script setup lang="ts">
definePageMeta({
    layout: 'default',
    layoutTransition: {
        name: 'layout',
    },
})
onMounted(() => {
    const body = document.querySelector('body')
    body.scrollTo({ top: 0, behavior: 'smooth' })
})
</script>
<template>
    <div>
        <p>Init</p>
    </div>
</template>
