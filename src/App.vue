<script>
  import Sidebar from "./components/Sidebar.vue"
  import Content from "./components/Content.vue"
  import Footer from "./components/Footer.vue"

  export default {
    components: {
      Sidebar,
      Content,
      Footer,
    },
  };
</script>

<template>
  <div class="flex flex-row bg-neutral-100">
    <!-- <Sidebar v-on:hover="alert('hehe')"/> -->
    <Content />
  </div> 
</template>

<style>
</style>  
