<template>
    <div>This is the Show page</div>

    <div>{{ tryagain }}</div>
</template>

<script setup>
import { Link } from "@inertiajs/inertia-vue3";

defineProps({
    tryagain: String,
});
</script>

<script>
import MainLayout from "../../Layouts/MainLayout.vue";
export default {
    layout: MainLayout,
};
</script>
