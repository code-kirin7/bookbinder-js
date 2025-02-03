<script setup>
import IntroHeader from './components/IntroHeader.vue'
import FileUpload from './components/FileUpload.vue'
// import SourceManip from './components/SourceManip.vue'
</script>

<template>
  <div class="wrapper">
    <IntroHeader />
  </div>

  <form id="bookbinder" name="bookbinder">
    <FileUpload />
    <!-- <SourceManip /> -->
  </form>
</template>

<style scoped></style>
