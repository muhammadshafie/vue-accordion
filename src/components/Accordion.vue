<template lang="">
  <div>
    <div class="accordion" id="accordionExample">
      <div class="accordion-item">
        <h2 class="accordion-header">
          <button
            class="accordion-button collapsed"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#collapseOne"
            aria-expanded="false"
            aria-controls="collapseOne"
          >
            <i class="bx bxs-zap accordion-icon"></i>
            Efficient
          </button>
        </h2>
        <div
          id="collapseOne"
          class="accordion-collapse collapse"
          data-bs-parent="#accordionExample"
        >
          <div class="accordion-body">
            We handle our clients professionally and put 100% of our effort into
            every service we provide using the knowledge and skills we have in
            this area of the logistics industry.
          </div>
        </div>
      </div>
      <div class="accordion-item">
        <h2 class="accordion-header">
          <button
            class="accordion-button collapsed"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#collapseTwo"
            aria-expanded="false"
            aria-controls="collapseTwo"
          >
            <i class="bx bxs-check-square accordion-icon"></i>
            Guaranted for Best Services
          </button>
        </h2>
        <div
          id="collapseTwo"
          class="accordion-collapse collapse"
          data-bs-parent="#accordionExample"
        >
          <div class="accordion-body">
            We will make certain that we recruit qualified, industrious,
            creative, customer-focused individuals that are eager to contribute
            to the success of our company (owner, workforce and customers).
          </div>
        </div>
      </div>
      <div class="accordion-item">
        <h2 class="accordion-header">
          <button
            class="accordion-button collapsed"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#collapseThree"
            aria-expanded="false"
            aria-controls="collapseThree"
          >
            <i class="bx bxs-purchase-tag accordion-icon"></i>
            Provide Best Prices
          </button>
        </h2>
        <div
          id="collapseThree"
          class="accordion-collapse collapse"
          data-bs-parent="#accordionExample"
        >
          <div class="accordion-body">
            Price we provides is the best for you, we guarantee no price changes
            on every service that we provide.
          </div>
        </div>
      </div>
      <div class="accordion-item">
        <h2 class="accordion-header">
          <button
            class="accordion-button collapsed"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#collapseFour"
            aria-expanded="false"
            aria-controls="collapseFour"
          >
            <i class="bx bx-shield-quarter accordion-icon"></i>
            We protect your Privacy
          </button>
        </h2>
        <div
          id="collapseFour"
          class="accordion-collapse collapse"
          data-bs-parent="#accordionExample"
        >
          <div class="accordion-body">
            In every CargoFast service, we care about your privacy and we will
            take 100% responsible for it.
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import "bootstrap/dist/css/bootstrap.min.css";
import "bootstrap";

export default {
  name: "Accordion",
};
</script>
<style scoped>
.accordion-button:focus {
  z-index: 3;
  border-color: unset;
  box-shadow: unset;
}
.accordion-button:not(.collapsed) {
  color: unset;
  background-color: transparent;
  box-shadow: unset;
}
</style>
