<template>
  <div class="cardsComponent container">
    <div class="row d-flex align-items-center mt-4">
      <div class="col col-md-6 containerImage">
        <img src="@/assets/image-03.jpg" class="w-100" alt="..." />
        <div class="centerTitle">Curtains</div>
      </div>
      <div class="col-12 col-md-6 containerImage mt-4">
        <img src="@/assets/image-04.jpg" class="w-100" alt="..." />
        <div class="centerTitle">Decoration</div>
      </div>
      <div class="col-12 col-md-6 containerImage mt-4">
        <img src="@/assets/image-05.jpg" class="w-100" alt="..." />
        <div class="centerTitle">Upholstery</div>
      </div>
      <div class="col-12 col-md-6 containerImage mt-4">
        <img src="@/assets/image-06.jpg" class="w-100" alt="..." />
        <div class="centerTitle">Decor</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Cards",
  components: {},
};
</script>

<style lang="scss" scoped>
.cardsComponent {
  width: 80%;
  margin-top: 80px;

  .containerImage {
    position: relative;
    display: inline-block;
    text-align: center;
    opacity:1;

    .centerTitle {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      font-weight: 300;
      font-size: 2.75rem;
      color: #fff;
      text-transform: uppercase;
    }
    @media (max-width: 580px) {
      .centerTitle {
        font-size: 2.00rem;       
      }
    }
  }
  .containerImage:hover{
    opacity:0.5;
    -webkit-transform: scale(1.05);
        -ms-transform: scale(1.05);
        transform: scale(1.05);
  }
  
}
</style>