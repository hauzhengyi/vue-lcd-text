<template>
  <div class="background"></div>
</template>

<script setup lang="ts"></script>

<style scoped lang="sass">
.background
  width: 500px
  height: 500px
  background-image: linear-gradient(to bottom, transparent 15px, black 15px), linear-gradient(to right, #ff0000 5px, #00ff00 5px, #00ff00 10px, #0000ff 10px, #0000ff 15px, black 15px)
  background-size: 20px 20px
  background-position: 0 0
</style>
