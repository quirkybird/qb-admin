<template>
  <div class="main-content">
    <router-view></router-view>
  </div>
</template>

<script setup lang="ts"></script>

<style scoped lang="less">
.main-content {
  height: 100%;
}
.main-content::before {
  content: ' ';
  display: block;
  height: 1px;
}
</style>
