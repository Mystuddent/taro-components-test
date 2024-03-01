<template>
  <view class="index">
    <w-record @onEnd="handleRecordEnd" />
  </view>
</template>

<script setup>
import { ref } from "vue";
import "./index.scss";
</script>
