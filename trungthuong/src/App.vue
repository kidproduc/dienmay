<script>
import LuckyWheel from './components/LuckyWheel.vue'
import LuckyPrize from './components/LuckyPrize.vue';
import LuckyHeader from './components/LuckyHeader.vue';

import { NGrid, NGi } from 'naive-ui'
export default {
  components: {
    LuckyWheel,
    LuckyPrize,
    NGrid,
    NGi,
    LuckyHeader
  }
}
</script>

<template>
  <LuckyHeader />
  <n-grid x-gap="12" :cols="2">
    <n-gi>
      <LuckyPrize firstPlace="First" secondPlace="Second" thirdPlace="Third" />
    </n-gi>
    <n-gi>
      <LuckyWheel />
    </n-gi>
  </n-grid>
</template>

<style scoped></style>
