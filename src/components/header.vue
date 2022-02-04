<template>
  <div id="background">
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <div class="container-fluid">
        <img id="logo" src="@/assets/45.jpg" />
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <a class="nav-link" aria-current="page" href="#">About_us</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Trending</a>
            </li>
            <li class="nav-item dropdown">
              <a class="nav-link" href="#">Local News</a>
            </li>
            <li class="nav-item dropdown">
              <a class="nav-link" href="#">International News</a>
            </li>
          </ul>
          <form class="d-flex">
            <input
              class="form-control me-2"
              type="search"
              placeholder="Search Preferred News"
              aria-label="Search"
            />
            <button class="btn btn-outline-success" type="submit" id="btn">
              Click
            </button>
          </form>
        </div>
      </div>
    </nav>
  </div>
  <!-- <div class="container">
    <h1 class="text"> My Ghana News App</h1>
    <h3 class="text1"> Your Relaible News Source..!</h3>
  </div> -->
  <!-- Brand and toggle get grouped for better mobile display -->
</template>
<script>
export default {
  name: "Header",
};
</script>
<style scoped>
#logo {
  width: 200px;
  height: 70px;
}
#background {
  color: orangered;
}
</style>
