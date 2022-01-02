<template>
  <section class="section products">
    <div class="container">
      <div class="row">
        <div class="col-12">
          <div class="text-center">
            <h3 class="cyan">Products</h3>
            <h1 class="light-brown">OUR POPULAR PRODUCTS</h1>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-4" v-for="(item, index) in 6 " v-bind:key="index">
          <div class="kf__card">
            <a href="" class="product">
              <div class="product__image">
                <img src="~/static/robusta.webp" alt="Kafin" />
              </div>
              <div class="product__content">
                <h2 class="cyan">Robusta Coffee</h2>
                <span class="price"> RS 1500/- </span>
              </div>
            </a>
            <kf-buttons text="Shop" color="cyan" type="link"></kf-buttons>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>