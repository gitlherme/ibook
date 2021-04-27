<template>
  <div class="box">
    <HomeTemplate />
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import { books } from '@/store/index'

export default Vue.extend({
  layout: 'ibook',
  async asyncData() {
    await books.index()
  },
})
</script>

<style lang="scss" scoped></style>
