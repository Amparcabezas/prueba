<template>
    <div class="carouselComponent">
      <div
        id="carouselExampleCaptions"
        class="carousel slide"
        data-ride="carousel"
        data-interval="3000"
        
      >
        <ol class="carousel-indicators">
          <li
            data-target="#carouselExampleCaptions"
            data-slide-to="0"
            class="active"
          ></li>
          <li data-target="#carouselExampleCaptions" data-slide-to="1"></li>
          <li data-target="#carouselExampleCaptions" data-slide-to="2"></li>
        </ol>
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="@/assets/image-01.jpg" class="d-block w-100" alt="..." />
            <div class="carousel-caption d-none d-md-block">
              <h5>A UNIVERSE OF TEXTIL</h5>
              <p class="pCarouselDiscover">DISCOVER</p>
            </div>
          </div>
          <div class="carousel-item">
            <img src="@/assets/image-01.jpg" class="d-block w-100" alt="..." />
            <div class="carousel-caption d-none d-md-block">
              <h5>A UNIVERSE OF TEXTIL</h5>
              <p class="pCarouselDiscover">DISCOVER</p>
            </div>
          </div>
          <div class="carousel-item">
            <img src="@/assets/image-01.jpg" class="d-block w-100" alt="..." />
            <div class="carousel-caption d-none d-md-block">
              <h5>A UNIVERSE OF TEXTIL</h5>
              <p class="pCarouselDiscover"> DISCOVER
              </p>
            </div>
          </div>
        </div>
        <a
          class="carousel-control-prev"
          href="#carouselExampleCaptions"
          role="button"
          data-slide="prev"
        >

                  
        </a>
        <a
          class="carousel-control-next"
          href="#carouselExampleCaptions"
          role="button"
          data-slide="next"
        >
          
        </a>
      </div>
    </div>
  
</template>

<script>
// @ is an alias to /src

export default {
  name: "Carousel",
  components: {},
};
</script>
<style lang="scss" scoped>

.carouselComponent{
  

  .carousel-indicators li{
    width: 10px;
    height: 10px;
    border-radius: 50%;
  }
  
  h5{
    margin-bottom: 12.5rem;
    font-weight: 300;
    line-height: 1.2;
    font-size: 3.25rem;
  }
  .pCarouselDiscover{
    margin: 0 auto;
    margin-bottom: 1rem;
    border-bottom: 1px solid white;
    width: 20%;
  }

}
  

</style>
