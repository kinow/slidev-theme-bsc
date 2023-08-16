<template>
  <div class="bsc-thankyou">
    <div class="slidev-layout cover my-title">
      <h1 class="title">Thank you</h1>
    </div>
    <footer>
      <div class="email">{{ props.slidesEmail }}@bsc.es</div>
    </footer>
  </div>
</template>

<script setup lang="ts">
const props = defineProps({
  slidesEmail: {
    type: String,
  }
})
</script>

<style>
.bsc-thankyou {
  height: 100%;
}

.bsc-thankyou > .my-title {
  background-image: url('/images/bsc-bg3.jpg');
  background-size: cover;
  padding-top: 200px;
  padding-left: 400px;
}

.bsc-thankyou > .my-title > .title {
  text-align: left;
  font-weight: bold;
  font-size: 5rem !important;
}

.bsc-thankyou > footer {
  position: absolute;
  bottom: 0;
  margin: 20px 0;
  padding: 5px 0;
  font-weight: bold;
  display: grid;
  grid-template-columns: 100%;
  min-width: 100%;
  background-color: white;
  opacity: 0.8;
}

.bsc-thankyou > footer > div.email {
  color: #004890;
  margin: 0 auto;
  font-size: 1.5rem;
}
</style>
