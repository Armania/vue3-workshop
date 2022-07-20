<script setup>
import HelloWorld from "@/components/HelloWorld.vue";
import VideoPlayer from "./components/VideoPlayer.vue";
</script>

<template>
  <div id="app">
    <HelloWorld msg="Rick & Morty Characters" />
    <VideoPlayer
      style="width: 800px; margin: 0 auto"
      src="../public/Dog on the beach.mp4"
    />
  </div>
</template>
