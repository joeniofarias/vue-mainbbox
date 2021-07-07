<template>
  <b-container>

    <b-row align-v="center">
      <b-col>10</b-col>
      <b-col>20</b-col>
      <b-col>30</b-col>
    </b-row>

    <div>
      <b-carousel
        id="carousel-fade"
        style="text-shadow: 0px 0px 2px #000"
        fade
        indicators
        img-width="1024"
        img-height="480"
      >
        <b-carousel-slide
          caption="First slide"
          img-src="https://picsum.photos/1024/480/?image=10"
        ></b-carousel-slide>
        <b-carousel-slide
          caption="Second Slide"
          img-src="https://picsum.photos/1024/480/?image=12"
        ></b-carousel-slide>
        <b-carousel-slide
          caption="Third Slide"
          img-src="https://picsum.photos/1024/480/?image=22"
        ></b-carousel-slide>
      </b-carousel>
    </div>
  </b-container>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",
  components: {},
};
</script>
