<template>
  <div>This is the Index page</div>
  <div>{{ message }}</div>
</template>

<script setup>
defineProps({ message: String })
</script>
