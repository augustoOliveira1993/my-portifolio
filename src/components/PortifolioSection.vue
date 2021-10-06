<template>
  <div>
    <section class="page-section portfolio" id="portfolio">
      <div class="container">
        <!-- Portfolio Section Heading-->
        <h2
          class="page-section-heading text-center text-uppercase text-secondary mb-0"
        >
          Portfolio
        </h2>
        <!-- Icon Divider-->
        <div class="divider-custom">
          <div class="divider-custom-line"></div>
          <div class="divider-custom-icon"><i class="fas fa-star"></i></div>
          <div class="divider-custom-line"></div>
        </div>
        <!-- Portfolio Grid Items-->
        <div class="row justify-content-center">
          <!-- Portfolio Item 1-->
          <div class="col-md-6 col-lg-4 mb-5">
            <div
              class="portfolio-item mx-auto"
              data-bs-toggle="modal"
              data-bs-target="#portfolioModal1"
            >
              <div
                class="portfolio-item-caption d-flex align-items-center justify-content-center h-100 w-100"
              >
                <div
                  class="portfolio-item-caption-content text-center text-white"
                >
                  <i class="fas fa-plus fa-3x"></i>
                </div>
              </div>
              <img
                class="img-fluid"
                src="../assets/img/portfolio/crud-vue.png"
                alt="..."
              />
            </div>
          </div>
          <!-- Portfolio Item 2-->
          <div class="col-md-6 col-lg-4 mb-5">
            <div
              class="portfolio-item mx-auto"
              data-bs-toggle="modal"
              data-bs-target="#portfolioModal2"
            >
              <div
                class="portfolio-item-caption d-flex align-items-center justify-content-center h-100 w-100"
              >
                <div
                  class="portfolio-item-caption-content text-center text-white"
                >
                  <i class="fas fa-plus fa-3x"></i>
                </div>
              </div>
              <img
                class="img-fluid"
                src="../assets/img/portfolio/log-dev.png"
                alt="..."
              />
            </div>
          </div>
          <!-- Portfolio Item 3-->
          <div class="col-md-6 col-lg-4 mb-5">
            <div
              class="portfolio-item mx-auto"
              data-bs-toggle="modal"
              data-bs-target="#portfolioModal3"
            >
              <div
                class="portfolio-item-caption d-flex align-items-center justify-content-center h-100 w-100"
              >
                <div
                  class="portfolio-item-caption-content text-center text-white"
                >
                  <i class="fas fa-plus fa-3x"></i>
                </div>
              </div>
              <img
                class="img-fluid"
                src="../assets/img/portfolio/cadastro-pessoa.png"
                alt="..."
              />
            </div>
          </div>
          <!-- Portfolio Item 4-->
          <div class="col-md-6 col-lg-4 mb-5 mb-lg-0">
            <div
              class="portfolio-item mx-auto"
              data-bs-toggle="modal"
              data-bs-target="#portfolioModal4"
            >
              <div
                class="portfolio-item-caption d-flex align-items-center justify-content-center h-100 w-100"
              >
                <div
                  class="portfolio-item-caption-content text-center text-white"
                >
                  <i class="fas fa-plus fa-3x"></i>
                </div>
              </div>
              <img
                class="img-fluid"
                src="../assets/img/portfolio/embre.png"
                alt="..."
              />
            </div>
          </div>
          <!-- Portfolio Item 5-->
          <div class="col-md-6 col-lg-4 mb-5 mb-md-0">
            <div
              class="portfolio-item mx-auto"
              data-bs-toggle="modal"
              data-bs-target="#portfolioModal5"
            >
              <div
                class="portfolio-item-caption d-flex align-items-center justify-content-center h-100 w-100"
              >
                <div
                  class="portfolio-item-caption-content text-center text-white"
                >
                  <i class="fas fa-plus fa-3x"></i>
                </div>
              </div>
              <img
                class="img-fluid"
                src="../assets/img/portfolio/embre.png"
                alt="..."
              />
            </div>
          </div>
          <!-- Portfolio Item 6-->
          <div class="col-md-6 col-lg-4">
            <div
              class="portfolio-item mx-auto"
              data-bs-toggle="modal"
              data-bs-target="#portfolioModal6"
            >
              <div
                class="portfolio-item-caption d-flex align-items-center justify-content-center h-100 w-100"
              >
                <div
                  class="portfolio-item-caption-content text-center text-white"
                >
                  <i class="fas fa-plus fa-3x"></i>
                </div>
              </div>
              <img
                class="img-fluid"
                src="../assets/img/portfolio/embre.png"
                alt="..."
              />
            </div>
          </div>
        </div>
      </div>
    </section>

    <ModalPorti />
  </div>
</template>

<script>
import ModalPorti from "../components/modal/ModalPorti.vue";
export default {
  name: "PortifolioSection",
  components: { ModalPorti },
  data() {
    return {};
  },
};
</script>

<style>
.portfolio .portfolio-item {
  cursor: pointer;
  position: relative;
  display: block;
  max-width: 25rem;
  border-radius: 0.5rem;
  overflow: hidden;
}
.portfolio .portfolio-item .portfolio-item-caption {
  position: absolute;
  top: 0;
  left: 0;
  transition: all 0.2s ease-in-out;
  opacity: 0;
  background-color: rgba(26, 188, 156, 0.9);
}
.portfolio .portfolio-item .portfolio-item-caption:hover {
  opacity: 1;
}
.portfolio
  .portfolio-item
  .portfolio-item-caption
  .portfolio-item-caption-content {
  font-size: 1.5rem;
}

.portfolio-modal .btn-close {
  color: #1abc9c;
  font-size: 2rem;
  padding: 1rem;
}
.portfolio-modal .portfolio-modal-title {
  font-size: 2.25rem;
  line-height: 2rem;
}
@media (min-width: 992px) {
  .portfolio-modal .portfolio-modal-title {
    font-size: 3rem;
    line-height: 2.5rem;
  }
}
</style>
