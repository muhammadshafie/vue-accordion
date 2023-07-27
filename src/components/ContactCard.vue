<template lang="">
  <div>
    <swiper :spaceBetween="30" :slidesPerView="2">
      <swiper-slide class="card">
        <div class="image-content">
          <span class="overlay"></span>
          <div class="card-image"></div>
        </div>
        <div class="card-content">
          <h2 class="name">Asyraf</h2>
          <p class="description">
            The lorem text the section that contains header with having open
            functionality. Lorem dolor sit amet consectetur adipisicing elit.
          </p>
          <div class="buttons">
            <a href="#" class="btn">Call</a>
            <a href="#" class="btn">Email</a>
          </div>
        </div>
      </swiper-slide>
      <swiper-slide class="card">
        <div class="image-content">
          <span class="overlay"></span>
          <div class="card-image"></div>
        </div>
        <div class="card-content">
          <h2 class="name">Asyari</h2>
          <p class="description">RORO Service</p>
          <div class="buttons">
            <a href="#" class="btn">Call</a>
            <a href="#" class="btn">Email</a>
          </div>
        </div>
      </swiper-slide>
      <swiper-slide class="card">
        <div class="image-content">
          <span class="overlay"></span>
          <div class="card-image"></div>
        </div>
        <div class="card-content">
          <h2 class="name">Azman</h2>
          <p class="description">RORO Service</p>
          <div class="buttons">
            <a href="tel:+60172892082" class="btn">Call</a>
            <a href="mailto:azsh@cargofast.com.my" class="btn">Email</a>
          </div>
        </div>
      </swiper-slide>
      <swiper-slide class="card">
        <div class="image-content">
          <span class="overlay"></span>
          <div class="card-image"></div>
        </div>
        <div class="card-content">
          <h2 class="name">Customer Service</h2>
          <p class="description">Email Only</p>
          <div class="buttons">
            <a
              href="mailto:enquiry@cargofast.com.my?Subject=Request%20for%20Quotation&body=I%20would%20like%20to%20have%20a%20quotation%20of%20your%20service"
              class="btn"
              >Email</a
            >
          </div>
        </div>
      </swiper-slide>
    </swiper>
  </div>
</template>
<script>
// Import Swiper Vue.js components
import { Swiper, SwiperSlide } from "swiper/vue";

// Import Swiper styles
import "swiper/css";

export default {
  components: {
    Swiper,
    SwiperSlide,
  },
  setup() {
    return {
      modules: [Navigation],
    };
  },
};
</script>
<style lang="css">
.swiper {
  width: 600px !important;
}

.card {
  border-radius: 25px;
  background-color: #fff;
}

.image-content,
.card-content {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 10px 14px;
}
.image-content {
  position: relative;
  row-gap: 5px;
  padding: 25px 0;
}
.overlay {
  position: absolute;
  left: 0;
  top: 0;
  height: 100%;
  width: 100%;
  background-color: #4070f4;
  border-radius: 25px 25px 0 25px;
}
.overlay::before,
.overlay::after {
  content: "";
  position: absolute;
  right: 0;
  bottom: -40px;
  height: 40px;
  width: 40px;
  background-color: #4070f4;
}
.overlay::after {
  border-radius: 0 25px 0 0;
  background-color: #fff;
}
.card-image {
  position: relative;
  height: 150px;
  width: 150px;
  border-radius: 50%;
  background: #fff;
  padding: 3px;
}
.card-image .card-img {
  height: 100%;
  width: 100%;
  object-fit: cover;
  border-radius: 50%;
  border: 4px solid #4070f4;
}
.name {
  font-size: 18px;
  font-weight: 500;
  color: #333;
}
.description {
  font-size: 14px;
  color: #707070;
  text-align: center;
}
.buttons {
  display: flex;
  align-items: center;
  margin-top: 30px;
  transition: 0.3s;
  cursor: pointer;
  gap: 20px;
}
.buttons .btn {
  font-size: var(--small-font-size);
  padding: 14px;
  /* width: 100%; */
  border-radius: 0.25rem;
  background: var(--first-color-lighten);
  color: var(--first-color);
  font-weight: var(--font-semi-bold);
  box-shadow: none;
}
.buttons .btn:hover {
  background-color: var(--first-color);
  color: #fff;
}
</style>
