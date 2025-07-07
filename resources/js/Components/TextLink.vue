<script  setup>
defineProps({
    routeName: String,
    label: String
})
</script>
<template>
    <Link :href="router(routeName)">{{ label }}</Link>
</template>
