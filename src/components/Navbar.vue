<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <a class="navbar-brand" href="#">ALHAMBRA</a>
    <button
      class="navbar-toggler"
      type="button"
      data-toggle="collapse"
      data-target="#navbarNavAltMarkup"
      aria-controls="navbarNavAltMarkup"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
      <div class="navbar-nav">
        <a class="nav-item nav-link active" href="#">MENU </a>
        <a class="nav-item nav-link" href="#">Collections</a>
        <a class="nav-item nav-link" href="#">Design</a>
        <a class="nav-item nav-link" href="#">Product search</a>
        <a class="nav-item nav-link" href="#">About</a>
        <hr class="d-lg-none" />
        <div class="d-flex flex-column d-lg-none">
          <a class="nav-item nav-link" href="#">News</a>
          <a class="nav-item nav-link" href="#">Download</a>
          <a class="nav-item nav-link" href="#">Trade Area</a>
          <a class="nav-item nav-link" href="#">English | Spanish</a>
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Navbar",
  components: {},
};
</script>
<style lang="scss" scoped>
.navbar {
    hr {
    border: 1px solid black;
    width: 20%;
    margin: 0px;
    margin-top: 10px;
    margin-bottom: 10px;
    background: black;
  }
}
</style>
