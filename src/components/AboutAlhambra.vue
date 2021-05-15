<template>
  <div class="aboutAlhambraComponent container">
    <div class="d-flex justify-content-end containerImage">
      <img src="@/assets/image-08.jpg" class="col-md-9" alt="..." />
      <h5 class="title d-none d-sm-block">
        Alhambra Brand was established in Alicante, Spain, in 1977. Yo can find
        us all around the world.
      </h5>
      <h4 class="findYourStyle d-none d-sm-block">This is who we are</h4>
    </div>
    <a class="findYourStyleSm d-block d-sm-none">This is who we are</a>
  </div>
</template>

<script>
export default {
  name: "AboutAlhambra",
  components: {},
};
</script>

<style lang="scss" scoped>
.aboutAlhambraComponent {
  width: 80%;
  margin-top: 220px;
  display: flex;
  flex-direction: column;
  color: #0d3444;

  .containerImage {
    position: relative;
    display: inline-block;

    .title {
      position: absolute;
      top: -8%;
      left: 32%;
      transform: translate(-50%, -50%);
      font-weight: 300;
      font-size: 2rem;
      width: 355px;
    }
    .findYourStyle {
      border-bottom: 1px solid #0d3444;
      text-transform: uppercase;
      letter-spacing: 3px;
      position: absolute;
      bottom: 117px;
      right: -168px;
      margin-left: -30px;
      transform: rotate(-90deg);
      cursor: pointer;
    }
  }
  .findYourStyleSm {
    text-decoration: underline;
    text-transform: uppercase;
    letter-spacing: 3px;
    margin: 10px;
    font-size: 1.5rem;
    
  }
}
@media (max-width: 580px) {
  .aboutAlhambraComponent {
    margin-top: 120px;
  }
}
</style>