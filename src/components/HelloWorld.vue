<template>
  <div @click="test">跳转</div>
</template>


<script setup>
  const test = ()=>{
      location.pathname = 'wujiao/index.html'
  }
</script>
