<template>
  <div class="wovenTalesComponent container justify-content-center">
    <div class="row d-flex">
      <h5>Woven tales</h5>
    </div>
    <div class="row d-flex align-items-center">
      
      <div class="col-12 col-md-4 woven">
        <img src="@/assets/image-09.jpg" class="w-100" alt="..." />
        <div class="titleWoven">Sintra collection</div>
        <div class="descriptionWoven">The saudade of times past</div>
      </div>

      <div class="col-12 col-md-4 woven">
        <img src="@/assets/image-10.jpg" class="w-100" alt="..." />
        <div class="titleWoven">Sade collectionn</div>
        <div class="descriptionWoven">Caressed by the atlantic breeze</div>
      </div>
      
      <div class="col-12 col-md-4 woven">
        <img src="@/assets/image-11.jpg" class="w-100" alt="..." />
        <div class="titleWoven">Brazilia collection</div>
        <div class="descriptionWoven">Enhanced by the contrats of colours</div>
      </div>
      
    </div>
    
  </div>
</template>

<script>
export default {
  name: "WovenTales",
  components: {},
};
</script>

<style lang="scss" scoped>
.wovenTalesComponent {
  width: 80%;
  margin-top: 80px; 
  color: #0d3444;

   h5{   
    font-weight: 300;
    line-height: 1.2;
    font-size: 2.50rem;
    text-transform: uppercase;
    margin:0 auto;
    margin-bottom: 20px;
  }
  .titleWoven{
    text-transform: uppercase;
    margin-top: 10px;
  }
  .descriptionWoven{
    font-size: 2.00rem;
  }
  .woven:hover{
    opacity:0.5;
    -webkit-transform: scale(1.05);
        -ms-transform: scale(1.05);
        transform: scale(1.05);
  }

  
}
</style>