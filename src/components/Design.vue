<template>
  <div class="designComponent container">
    <div class="d-flex justify-content-end containerImage">
      <img src="@/assets/image-02.jpg" class="col-9" alt="..." />
      <h5 class="title">DESIGN YOUR NARRATIVE</h5>
    </div>
    <div class="d-flex justify-content-end mt-4">
      <div class="d-flex align-items-center findYourStyle">
        <div class="">Find your style &#8594;</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Design",
  components: {},
};
</script>

<style lang="scss" scoped>
.designComponent {
  width: 80%;
  margin-top: 80px;
  display: flex;
  flex-direction: column;
  justify-content: flex-end;
  margin-right: 0px;
  color: #0D3444;
  

  .containerImage {
    position: relative;
    display: inline-block;

    .title {
      position: absolute;
      top: 82%;
      left: 16%;
      transform: translate(-50%, -50%);
      font-weight: 300;
      font-size: 2.75rem;
      text-transform: uppercase;
      width: 150px;
    }
    
  }
  .findYourStyle {
    border-bottom: 1px solid #0d3444;;
    margin-right: 50px;
    cursor: pointer;
    
  }  
  @media (max-width: 580px) {
      .title{
        font-size: 1.75rem !important;        
        width: 100px;
        margin-bottom: 10px;
      }
    }
  
}
</style>