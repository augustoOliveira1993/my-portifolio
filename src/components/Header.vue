<template>
  <header class="masthead bg-primary text-white text-center">
    <div class="container d-flex align-items-center flex-column">
      <!-- Masthead Avatar Image-->
      <img
        class="masthead-avatar mb-5"
        src="../assets/img/avataaars.svg"
        alt="avatar"
      />
      <!-- Masthead Heading-->
      <h1 class="masthead-heading text-uppercase mb-0">Augusto Oliveira</h1>
      <!-- Icon Divider-->
      <div class="divider-custom divider-light">
        <div class="divider-custom-line"></div>
        <div class="divider-custom-icon"><i class="fas fa-star"></i></div>
        <div class="divider-custom-line"></div>
      </div>
      <!-- Masthead Subheading-->
      <p class="masthead-subheading font-weight-light mb-0">
        Desenvolvedor Junior - NodeJS - VueJS
      </p>
    </div>
  </header>
</template>

<script>
export default {};
</script>

<style>
.masthead {
  padding-top: calc(6rem + 74px);
  padding-bottom: 6rem;
}
.masthead .masthead-heading {
  font-size: 2.75rem;
  line-height: 2.75rem;
}
.masthead .masthead-subheading {
  font-size: 1.25rem;
}
.masthead .masthead-avatar {
  width: 15rem;
}

@media (min-width: 992px) {
  .masthead {
    padding-top: calc(6rem + 104px);
    padding-bottom: 6rem;
  }
  .masthead .masthead-heading {
    font-size: 4rem;
    line-height: 3.5rem;
  }
  .masthead .masthead-subheading {
    font-size: 1.5rem;
  }
}
</style>
