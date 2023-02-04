<template>
    <Link href="/">Main Page</Link>&nbsp;
    <Link href="/show">Show Page</Link>

    <div>Time remaining {{ timer }}</div>
    <!-- for persistent layout -->
    <slot>Default</slot>
</template>

<script setup>
import { Link } from "@inertiajs/inertia-vue3";
import { ref } from "vue";

const timer = ref(1000000);
setInterval(() => timer.value--, 1000);
</script>
