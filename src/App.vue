<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div>
    <a href="">
      <img src="https://media.licdn.com/dms/image/C560BAQFxC-WYcsu6AQ/company-logo_200_200/0/1597869493103?e=2147483647&v=beta&t=XM-X-bXf0Hj2zHFBZSDdNA694ostnFh0HjeXXLt3Wtc" alt="">
    </a>
  </div>
  <HelloWorld msg="Hello World" />
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
