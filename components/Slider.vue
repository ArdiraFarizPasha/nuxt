<template>
  <div>
    <div>
      <hr>
      <div class="title-problem">
        Dapatkan jawaban untuk apa saja dan segalanya
      </div>
      <div class="subtitle-problem">
        Konsultasikan masalah Anda dengan tim konselor kami yang berpengalaman
        dalam menangani masalah berikut
      </div>
    </div>
    <div ref="slider" class="keen-slider">
      <div class="keen-slider__slide number-slide1">
        <img src="~/assets/icon-sample.jpeg" class="icon-sample" />
      </div>

      <div class="keen-slider__slide number-slide1">
        <img src="~/assets/icon-sample.jpeg" class="icon-sample" />
      </div>

      <div class="keen-slider__slide number-slide1">
        <img src="~/assets/icon-sample.jpeg" class="icon-sample" />
      </div>
      <div class="keen-slider__slide number-slide1">
        <img src="~/assets/icon-sample.jpeg" class="icon-sample" />
      </div>

      <div class="keen-slider__slide number-slide1">
        <img src="~/assets/icon-sample.jpeg" class="icon-sample" />
      </div>

      <div class="keen-slider__slide number-slide1">
        <img src="~/assets/icon-sample.jpeg" class="icon-sample" />
      </div>
      <div class="keen-slider__slide number-slide1">
        <img src="~/assets/icon-sample.jpeg" class="icon-sample" />
      </div>

      <div class="keen-slider__slide number-slide1">
        <img src="~/assets/icon-sample.jpeg" class="icon-sample" />
      </div>

      <div class="keen-slider__slide number-slide1">
        <img src="~/assets/icon-sample.jpeg" class="icon-sample" />
      </div>
      <div class="keen-slider__slide number-slide1">
        <img src="~/assets/icon-sample.jpeg" class="icon-sample" />
      </div>
    </div>
  </div>
</template>

<script>
import "keen-slider/keen-slider.min.css";
import KeenSlider from "keen-slider";

export default {
  name: "Slider",
  mounted() {
    this.slider = new KeenSlider(this.$refs.slider, {
      slidesPerView: 9,
      mode: "free",
      spacing: 0,
      loop: true,
    });
  },
  beforeDestroy() {
    if (this.slider) this.slider.destroy();
  },
};
</script>

<style>
[class^="number-slide"],
[class*=" number-slide"] {
  /* background: grey; */
  /* display: flex;
  align-items: center;
  justify-content: center;
  font-size: 50px;
  color: #fff;
  font-weight: 500;
  height: 300px;
  max-height: 100vh; */
}

.keen-slider {
  margin: 20px 0px;
}

.icon-sample {
  width: 100px;
  height: auto;
}

.keen-slider__slide number-slide1 {
  min-height: 200px !important;
}

.title-problem {
  font-family: Nunito;
  font-style: normal;
  font-weight: bold;
  font-size: 36px;
  line-height: 49px;
  text-align: center;
}

.subtitle-problem {
  font-family: Nunito;
  font-style: normal;
  font-weight: normal;
  font-size: 20px;
  line-height: 25px;
  /* or 125% */

  display: flex;
  align-items: center;
  text-align: center;
  justify-content: center;

  color: #505766;
}
</style>
