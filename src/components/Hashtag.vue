<template>
  <div class="hashtagComponent container">
    <div class="hashtags">
      #ikaria <span>#sintra </span>#jimena <span>#sade </span> #candela <span>#aspen </span>#brazilia <span>#gatsby </span>#palma <span>#manhattan </span>#haiku <span>#toscana </span>#atlantida <span>#magara</span> 
    </div>    
  </div>
</template>

<script>
export default {
  name: "Hashtag",
  components: {},
};
</script>

<style lang="scss" scoped>
.hashtagComponent {
  width: 60%;
  margin-top: 80px; 
  color: #0d3444;    
  font-weight: 500;  
  font-size: 1.75rem;
  text-transform: uppercase;
  text-align: center; 

  span{
    color:gray;
  } 
}
</style>