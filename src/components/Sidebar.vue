<script>
  import SidebarElement from "./SidebarElement.vue"
  
  export default {
    components: {
      SidebarElement, 
    }
  }
</script>

<template>
  <div class="flex flex-col w-1/5 md:w-60 h-screen bg-neutral-300 p-4 justify-center gap-1">
    <SidebarElement content="Haha" />
    <SidebarElement content="Hoho" />
    <SidebarElement />
  </div>
</template>