<template>
  <div class="footerComponent container">
    <hr />
    <div class="row d-flex justify-content-between align-items-center">
      <div class="col-12 col-md-4 d-flex flex-column align-items-center align-items-md-start">
        <a href="">Privacy Policy</a>
        <a href=""> Cookies Policy Legal Notice</a>
      </div>
      <div class="col-12 col-md-4 d-flex justify-content-center">
        <button>Suscribe</button>
      </div>
      <div class="col-12 col-md-4 d-flex flex-column align-items-center align-items-md-end">
        <div>
          <a class="mr-3" href="">Intagram</a>
          <a href="">Facebook</a>
        </div>
        <div>
          <a class="mr-3" href="">Twitter</a>
          <a class="mr-3" href="">Linkedin</a>
          <a href="">Pinterest</a>
        </div>
      </div>
    </div>
    <div class="row rights">
      <div class="col-12 d-flex justify-content-center mt-4">&#169; 2020 All rights reserved</div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Footer",
  components: {},
};
</script>

<style lang="scss" scoped>
.footerComponent {
  width: 80%;
  margin-top: 80px; 
  margin-bottom: 10px;
  color: #0d3444;
  font-weight: 300;
  font-size: 1rem;

  button {
    width: 100px;
    height: 30px;
    border: solid 1px #0d3444;
    color: #0d3444;
    font-weight: 500;
    background: rgba(255, 255, 255, 0);
    font-size: 0.75rem;
  }
  button:hover {
    background: #0d3444;
    color: white;
    border: solid 2px #0d3444;
  }
  a:link,
  a:visited,
  a:active {
    text-decoration: none;
    color: #0d3444;
    line-height: 30px;
  }
  hr{
    margin-bottom: 50px;
  }
  .rights{
    font-size: 0.75rem;
       
  }

}
</style>