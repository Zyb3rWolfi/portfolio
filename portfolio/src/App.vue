<script setup>
import { initFlowbite } from 'flowbite'
import { onMounted } from 'vue'
import navbar from './components/navbar.vue';
import mainView from './views/main-view.vue'
import rightVar from './components/right-var.vue';

onMounted(() => {
    initFlowbite();
})
</script>

<template>
  <navbar />
  <div class="grid grid">
    <mainView />
    <rightVar />
  </div>
</template>

<style scoped>

</style>
