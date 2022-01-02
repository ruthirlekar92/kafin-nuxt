<template>
  <div id="kf-home">
    <HomeBanner />
    <section class="section about">
      <div class="about__wrapper">
        <div class="about__image">
          <img src="~/static/about.jpeg" alt="Kafin" />
        </div>
        <div class="container">
          <div class="row">
            <div class="col-12">
              <div class="about__content">
                <h1 class="title light-brown">TOP QUALITY COFFEE BEANS</h1>
                <p class="gray2">
                  Aptent sociosqu vehicula tellus mauris molestie neque et
                  venenatis, congue cubilia justo aliquam habitasse risus
                  quisque sed semper montes.Aptent sociosqu vehicula tellus
                  mauris molestie neque et venenatis, congue cubilia justo
                  aliquam habitasse risus quisque sed semper montes.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <img class="about__background" src="~/static/bg.webp" alt="kafin" />
    </section>
    <section class="section services">
      <div class="container">
        <div class="row">
          <div class="col-12">
            <div class="text-center">
              <h3 class="cyan">What We Do</h3>
              <h1 class="title light-brown">Speciality Coffee Roastery</h1>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-3">
            <div class="kf__card">
              <div class="kf__card--image">
                <img src="~/static/coffee-beans.jpeg" alt="Kafin" />
              </div>
              <div class="kf__card--content">
                <h4 class="cyan">Sourching</h4>
                <p class="gray2">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
              </div>
            </div>
          </div>
          <div class="col-3">
            <div class="kf__card">
              <div class="kf__card--image">
                <img src="~/static/rosting.jpeg" alt="Kafin" />
              </div>
              <div class="kf__card--content">
                <h4 class="cyan">Roasting</h4>
                <p class="gray2">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
              </div>
            </div>
          </div>
          <div class="col-3">
            <div class="kf__card">
              <div class="kf__card--image">
                <img src="~/static/packaging.jpeg" alt="Kafin" />
              </div>
              <div class="kf__card--content">
                <h4 class="cyan">Packaging</h4>
                <p class="gray2">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
              </div>
            </div>
          </div>
          <div class="col-3">
            <div class="kf__card">
              <div class="kf__card--image">
                <img src="~/static/delivery.jpeg" alt="Kafin" />
              </div>
              <div class="kf__card--content">
                <h4 class="cyan">Delivery</h4>
                <p class="gray2">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <Products/>
  </div>
</template>

<script>
export default {
  name: "IndexPage",
  data() {
    return {};
  },
};
</script>
ß