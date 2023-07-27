<template lang="">
  <div>
    <div class="value__container container grid">
      <div
        class="value__images"
        data-sr-id="15"
        style="
          visibility: visible;
          opacity: 1;
          transform: matrix3d(1, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1);
          transition: opacity 2.5s cubic-bezier(0.5, 0, 0, 1) 0.4s,
            transform 2.5s cubic-bezier(0.5, 0, 0, 1) 0.4s;
        "
      >
        <div class="value__orbe"></div>
        <div class="value__img">
          <img
            src="https://drive.google.com/uc?id=1smU4lS3ce-VuS_HiHb_IKSNjfqicINiO"
            alt=""
          />
        </div>
      </div>
      <div class="value__content">
        <div class="value__data">
          <span class="section__subtitle">Our Value</span>
          <h2 class="section__title">Value We Give To You<span>.</span></h2>
          <p class="value__description">
            We always ready to help by providing the best service for you. We
            believe a satisfied customer is the best business strategy of all.
          </p>
        </div>
        <Accordion />
      </div>
    </div>
  </div>
</template>
<script>
import Accordion from "./Accordion.vue";

export default {
  name: "AboutUs",
  components: {
    Accordion,
  },
};
</script>
<style lang=""></style>
