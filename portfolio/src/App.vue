<script setup>
import { initFlowbite } from 'flowbite'
import { onMounted } from 'vue'
import navbar from './components/navbar.vue';
import mainView from './views/main-view.vue'

onMounted(() => {
    initFlowbite();
})
</script>

<template>
  <navbar />
  <mainView />
</template>

<style scoped>

</style>
