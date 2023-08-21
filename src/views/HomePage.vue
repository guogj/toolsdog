<script setup>
const handleClickMini = () => {
  AMessage.info('hello isboyjc, click mini AButton!')
};
</script>
<template>
  <div>hello isboyjc, This is toolsdog home page!</div>
  <a-space>
    <a-button type="primary" size="mini" @click="handleClickMini">Mini</a-button>
    <a-button type="primary" size="small">Small</a-button>
    <a-button type="primary">Medium</a-button>
    <a-button type="primary" size="large">Large</a-button>
    <icon-ep-alarm-clock class=""/>
    <icon-fe-add-cart class=""/>
    <icon-home-copy class="text-20px"/>
    <icon-home-download class="text-50px"/>
    <button class="bg-blue-400 hover:bg-blue-500 text-sm text-white font-mono font-light py-2 px-4 rounded border-2 border-blue-200 dark:bg-blue-500 dark:hover:bg-blue-600">
        Button
      </button>  
      <button class="btn-style">
        Button22
      </button>    
  </a-space>
  <HelloWorld />
</template>
<style scoped>
.btn-style{
    @apply bg-blue-400 text-sm text-white font-mono font-light py-2 px-4 rounded border-2 border-blue-200;
    @apply hover:bg-blue-500;
    @apply dark:bg-blue-500 dark:hover:bg-blue-600;
  }
</style>