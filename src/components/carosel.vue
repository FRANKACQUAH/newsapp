<template>
  <div id="new">
    <div id="demo" class="carousel slide" data-ride="carousel">
      <!-- Indicators -->
      <ul class="carousel-indicators">
        <li data-target="#demo" data-slide-to="0" class="active"></li>
        <li data-target="#demo" data-slide-to="1"></li>
      </ul>

      <!-- The slideshow -->
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img
            src="@/assets/gh.jpg"
            alt="Los Angeles"
            width="1300"
            height="600"
          />
        </div>
        <div class="carousel-next">
          <img
            src="@/assets/img2.png"
            alt="Chicago"
            width="1100"
            height="500"
          />
        </div>
      </div>
      <!-- Left and right controls -->
      <a class="carousel-control-prev" href="#demo" data-slide="prev">
        <span class="carousel-control-prev-icon"></span>
      </a>
      <a class="carousel-control-next" href="#demo" data-slide="next">
        <span class="carousel-control-next-icon"></span>
      </a>
    </div>
  </div>
</template>
<script>
// var myCarouselEl = document.getElementById("myCarousel");
// var carousel = bootstrap.Carousel.getInstance(myCarouselEl); // Retrieve a Carousel instance

// myCarouselEl.addEventListener("slid.bs.carousel", function (event) {
//   carousel.to("2"); // Will slide to the slide 2 as soon as the transition to slide 1 is finished
// });
// carousel.to("1"); // Will start sliding to the slide 1 and returns to the caller
// carousel.to("2"); // !! Will be ignored, as the transition to the slide 1 is not finished !!
export default {
  name: "Carosel",
};
</script>
<style scoped>
#new {
  text-align: center;
}
</style>
