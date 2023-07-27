<template lang="">
  <div>
    <section class="contact section" id="contact">
      <div class="contact__container container grid">
        <div
          class="contact__images"
          data-sr-id="30"
          style="
            visibility: visible;
            opacity: 1;
            transform: matrix3d(1, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1);
            transition: opacity 2.5s cubic-bezier(0.5, 0, 0, 1) 0.4s,
              transform 2.5s cubic-bezier(0.5, 0, 0, 1) 0.4s;
          "
        >
          <div class="contact__orbe"></div>

          <div class="contact__img">
            <img
              src="https://drive.google.com/uc?id=1eMyK4W1s3_uJTQYbczzyKXJr_9cF5QzP"
              alt=""
            />
          </div>
        </div>

        <div
          class="contact__content"
          data-sr-id="16"
          style="
            visibility: visible;
            opacity: 1;
            transform: matrix3d(1, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1);
            transition: opacity 2.5s cubic-bezier(0.5, 0, 0, 1) 0.4s,
              transform 2.5s cubic-bezier(0.5, 0, 0, 1) 0.4s;
          "
        >
          <div class="contact__data">
            <span class="section__subtitle">Contact Us</span>
            <h2 class="section__title">Easy to Contact us<span>.</span></h2>
            <p class="contact__description">
              Please contact us if you would like any further information on our
              logistic moving services.
            </p>
          </div>
          <ContactCard />
        </div>
      </div>
    </section>
  </div>
</template>
<script>
import ContactCard from "./ContactCard.vue";

export default {
  name: "ContactUs",
  components: {
    ContactCard,
  },
};
</script>
<style lang=""></style>
