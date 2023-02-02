<template>
    <div>This is the Show page</div>
    <Link href="/">to main page</Link>
    <div>{{ tryagain }}</div>
</template>

<script setup>
import { Link } from "@inertiajs/inertia-vue3";

defineProps({
    tryagain: String,
});
</script>
