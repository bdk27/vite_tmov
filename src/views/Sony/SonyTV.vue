<script setup>
  import { useRoute } from 'vue-router';
  import BaseCardComponent from '../../components/BaseCardComponent.vue';

  const route = useRoute();
</script>

<template>
  <h3 class="title">熱門影集</h3>
  <BaseCardComponent :queryParam="route.query"></BaseCardComponent>
  <h1>查無相關資料</h1>
</template>

<style lang="scss" scoped>
  @import url(../../scss/_title.scss);
</style>