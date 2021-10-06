<template>
  <section class="page-section" id="contato">
    <div class="container">
      <!-- contato Section Heading-->
      <h2
        class="page-section-heading text-center text-uppercase text-secondary mb-0"
      >
        Contrate-Me
      </h2>
      <!-- Icon Divider-->
      <div class="divider-custom">
        <div class="divider-custom-line"></div>
        <div class="divider-custom-icon"><i class="fas fa-star"></i></div>
        <div class="divider-custom-line"></div>
      </div>
      <!-- contato Section Form-->
      <div class="row justify-content-center">
        <div class="col-lg-8 col-xl-7">
          <form id="contactForm" data-sb-form-api-token="API_TOKEN">
            <!-- Name input-->
            <div class="form-floating mb-3">
              <input
                class="form-control"
                id="name"
                type="text"
                placeholder="Enter your name..."
                data-sb-validations="required"
              />
              <label for="name">Nome Sobrenome</label>
              <div class="invalid-feedback" data-sb-feedback="name:required">
                Insira seu nome.
              </div>
            </div>
            <!-- Email address input-->
            <div class="form-floating mb-3">
              <input
                class="form-control"
                id="email"
                type="email"
                placeholder="name@example.com"
                data-sb-validations="required,email"
              />
              <label for="email">E-Mail</label>
              <div class="invalid-feedback" data-sb-feedback="email:required">
                Insira seu email.
              </div>
              <div class="invalid-feedback" data-sb-feedback="email:email">
                Email is not valid.
              </div>
            </div>
            <!-- Phone number input-->
            <div class="form-floating mb-3">
              <input
                class="form-control"
                id="phone"
                type="tel"
                placeholder="(XX) XXXXX-XXXX"
                data-sb-validations="required"
              />
              <label for="phone">Numero Celular</label>
              <div class="invalid-feedback" data-sb-feedback="phone:required">
                Insira seu numero telefonico.
              </div>
            </div>
            <!-- Message input-->
            <div class="form-floating mb-3">
              <textarea
                class="form-control"
                id="message"
                type="text"
                placeholder="Enter your message here..."
                style="height: 10rem"
                data-sb-validations="required"
              ></textarea>
              <label for="message">Mensagem</label>
              <div class="invalid-feedback" data-sb-feedback="message:required">
                Precisa inserir algo na mensagem
              </div>
            </div>
            <div class="d-none" id="submitSuccessMessage">
              <div class="text-center mb-3">
                <div class="fw-bolder">Form submission successful!</div>
                To activate this form, sign up at
                <br />
                <a href="https://startbootstrap.com/solution/contact-forms"
                  >https://startbootstrap.com/solution/contact-forms</a
                >
              </div>
            </div>
            <div class="d-none" id="submitErrorMessage">
              <div class="text-center text-danger mb-3">
                Error sending message!
              </div>
            </div>
            <!-- Submit Button-->
            <button
              class="btn btn-primary btn-xl disabled"
              id="submitButton"
              type="submit"
            >
              Send
            </button>
          </form>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style></style>
