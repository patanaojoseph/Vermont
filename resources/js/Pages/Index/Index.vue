<template>
    <div>This is the Index page</div>
    <Link href="/show">to Show page</Link>
    <div>{{ mensahe }}</div>
</template>

<script setup>
import { Link } from "@inertiajs/inertia-vue3";

defineProps({
    mensahe: String,
});
</script>
