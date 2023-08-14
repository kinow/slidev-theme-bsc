<template>
  <div class="bsc-cover">
    <div class="slidev-layout cover my-title">
      <h1 class="title">{{ props.slidesTitle }}</h1>
    </div>
    <footer>
      <div class="date">{{ props.slidesDate }}</div>
      <div class="venue">{{ props.slidesVenue }}</div>
    </footer>
  </div>
</template>

<script setup lang="ts">
const props = defineProps({
  slidesTitle: {
    type: String,
  },
  slidesDate: {
    type: String,
  },
  slidesVenue: {
    type: String,
  }
})
</script>
