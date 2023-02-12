<script>
  export default {
    props: {
      content: String,
    },
    
    setup(props) {
      
    },
  }
</script>

<template>
  <div class="text-neutral-800" v-if="content">
    {{ content.toLowerCase() }}
  </div>
  <div class="text-neutral-400" v-else>
    tough luck
  </div>
</template>