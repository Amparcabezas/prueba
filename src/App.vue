<template>
  <div id="nav">
    <Page />
    
  </div>
  <router-view/>
</template>
<script>

import Page from '@/views/Page'

export default {
  name: 'App',
  components: { 
    Page  
    
  },
  setup(){
    
    return {
      
      
    }
  }
}

</script>

<style lang="scss" scoped>
.principalPage {
  font-family: "Space Grotesk", Helvetica, Arial, sans-serif;
  color: black;
}

</style>
