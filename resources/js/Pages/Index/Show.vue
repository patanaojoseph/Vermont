<template>
    <div>This is the Show page</div>

    <div>{{ greetings }}</div>
</template>

<script setup>
defineProps({
    greetings: String,
});
</script>
