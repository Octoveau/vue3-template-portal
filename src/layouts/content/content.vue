<template>
  <!-- BreadCreamb -->
  <div class="main-container">
    <bread-crumb />
    <div class="main-content">
      <router-view />
    </div>
  </div>
</template>

<script setup lang="ts">
import BreadCrumb from '@/components/BreadCrumb/breadCrumb.vue'
</script>

<style lang="less" scoped>
.main-container {
  margin: 0px 0px 0.15rem 0.3rem;
  width: calc(100% - 0.6rem);
  height: calc(100% - 0.3rem);
  position: relative;

  .main-content {
    width: 100%;
    height: calc(100% - 36px);
    border-radius: 5px;
  }
}
</style>