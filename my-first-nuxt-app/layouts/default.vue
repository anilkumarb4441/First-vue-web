<template>
  <div>
    <TheHeader />
    <nuxt />
  </div>
</template>

<script>
import TheHeader from '@/components/TheHeader.vue';
export default {
    components: TheHeader,
}
</script>

<style >
html, body {
  margin:0;
}
</style>