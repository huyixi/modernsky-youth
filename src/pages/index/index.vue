<template>
  <view class="index">
    <Tabbar />
  </view>
</template>

<script setup>
import { ref } from "vue";
const show = ref(false);
const onClick = () => {
  show.value = true;
};
</script>
