<script setup>
import HelloWorld from "@/components/HelloWorld.vue";
</script>

<template>
  <div id="app">
    <VideoPlayer
      style="width: 800px; margin: 0 auto"
      src="../public/Dog on the beach.mp4"
    />
    <HelloWorld msg="Rick & Morty Characters" />
  </div>
</template>
