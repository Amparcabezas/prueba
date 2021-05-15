<template>
  <div class="carouselComponent2">
    <div
      id="carouselExampleCaptions"
      class="carousel slide"
      data-ride="carousel"
      data-interval="3000"
    >
     
      <ol class="carousel-indicators d-none">
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
          <img src="@/assets/image-07.jpg" class="d-block w-100" alt="..." />
          <div
            class="carousel-caption d-flex align-items-center justify-content-around"
          >
            <h5>
              The fruit of a detailed and constant work of investigation,
              development and disign.
            </h5>
            <button>VIEW ALL</button>
          </div>
        </div>
        <div class="carousel-item">
          <img src="@/assets/image-07.jpg" class="d-block w-100" alt="..." />
          <div
            class="carousel-caption d-none d-flex align-items-center justify-content-around"
          >
            <h5>
              The fruit of a detailed and constant work of investigation,
              development and disign.
            </h5>
            <button>VIEW ALL</button>
          </div>
        </div>
        <div class="carousel-item">
          <img src="@/assets/image-07.jpg" class="d-block w-100" alt="..." />
          <div
            class="carousel-caption d-none d-flex align-items-center justify-content-around"
          >
            <h5>
              The fruit of a detailed and constant work of investigation,
              development and disign.
            </h5>
            <button>VIEW ALL</button>
          </div>
        </div>
      </div>
      <a
        class="carousel-control-prev"
        href="#carouselExampleCaptions2"
        role="button"
        data-slide="prev"
      >
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
      </a>
      <a
        class="carousel-control-next"
        href="#carouselExampleCaptions2"
        role="button"
        data-slide="next"
      >
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
      </a>
    </div>
  </div>
</template>

<script>
export default {
  name: "Carousel2",
  components: {},
};
</script>
<style lang="scss" scoped>
.carouselComponent2 {
  margin-top: 80px;

  .carousel-control-next-icon,
  .carousel-control-prev-icon {
    width: 50px;
    height: 50px;
  }

  h5 {
    margin-bottom: 2.5rem;
    margin-right: 0.3rem;
    font-weight: 300;
    line-height: 1.2;
    font-size: 2.25rem;
    width: 580px;
    text-align: left;
  }
  button {
    width: 170px;
    height: 50px;
    border: none;
    border: solid 2px white;
    color: rgba(255, 255, 255, 0.952);
    background: rgba(255, 255, 255, 0);
    font-size: 25px;
  }

  button:hover {
    background: rgba(255, 255, 255, 0.432);
    color: #0d3444;
    border: solid 2px #0d3444;
  }
  @media (max-width: 760px) {
    h5 {
      font-size: 1.75rem;
    }
    button {
    width: 170px;
    height: 50px;
    border: none;
    border: solid 2px white;
    color: rgba(255, 255, 255, 0.952);
    background: rgba(255, 255, 255, 0);
    font-size: 15px;
  }
  }
  @media (max-width: 576px) {
    h5 {
      margin-bottom: 0.5rem;
      font-size: 1.25rem;
    }
  }
}
</style>
