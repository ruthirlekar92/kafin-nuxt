<template>
  <div id="contact">
    <section class="banner">
      <img
        class="banner__image"
        src="~/static/coffee banner 3.jpeg"
        alt="missioncoffeeusa"
      />

      <div class="banner__wrapper">
        <div class="container">
          <div class="row">
            <div class="col-12">
              <div class="banner__content">
                <h1 class="title">
                  Coffee <br />
                  Subscription?
                </h1>
                <p class="">
                  Aptent sociosqu vehicula tellus mauris molestie neque et
                  venenatis, congue cubilia justo aliquam habitasse risus
                  quisque sed semper montes.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="section subscription">
      <div class="container">
        <div class="row">
          <div class="col-2"></div>
          <div class="col-8">
            <div class="section__title text-center">
              <h2 class="light-brown">Subscribe to our coffee</h2>
            </div>
            <div class="section__form">
              <form>
                <div class="form-group">
                  <label for="">Name</label>
                  <input
                    type="text"
                    class="form-control"
                    id="name"
                    placeholder="Name"
                  />
                </div>
                <div class="form-group">
                  <label for="exampleInputEmail1">Email address</label>
                  <input
                    type="email"
                    class="form-control"
                    id="exampleInputEmail1"
                    aria-describedby="emailHelp"
                    placeholder="Enter email"
                  />
                </div>
                <div class="form-group">
                  <label for="exampleInputPhone">Phone</label>
                  <input
                    type="phone"
                    class="form-control"
                    id="exampleInputPhone"
                    placeholder="Phone Number"
                  />
                </div>
                <div class="form-group">
                  <label for="product">Choose your product</label>
                  <select class="form-control" id="product">
                    <option>Coffee</option>
                    <option>Tea</option>
                  </select>
                </div>
                <div class="form-group" v-if="true">
                  <label for="tea">Choose your Tea</label>
                  <select class="form-control" id="tea">
                    <option>Gulab</option>
                    <option>Tulsi Adrak</option>
                  </select>
                </div>
                <div class="form-group" v-if="true">
                  <label for="coffee">Choose your coffee</label>
                  <select class="form-control" id="coffee">
                    <option>mysore</option>
                    <option>dark coffee</option>
                  </select>
                </div>
                <div class="form-group form-check">
                  <input
                    type="checkbox"
                    class="form-check-input"
                    id="subscibe"
                  />
                  <label class="form-check-label" for="subscibe"
                    >Subscribe for coffee</label
                  >
                </div>
                <div class="text-center">
                  <button type="submit" class="kf__btn brown">Submit</button>
                </div>
              </form>
            </div>
          </div>
          <div class="col-2"></div>
        </div>
      </div>
    </section>
    <section class="map">
      <div class="">
        <div class="mapouter">
          <div class="gmap_canvas">
            <iframe
              class="gmap_iframe"
              frameborder="0"
              scrolling="no"
              marginheight="0"
              marginwidth="0"
              src="https://maps.google.com/maps?width=600&amp;height=400&amp;hl=en&amp;q=kafin vashi&amp;t=&amp;z=14&amp;ie=UTF8&amp;iwloc=B&amp;output=embed"
            ></iframe
            ><a
              href="https://www.fridaynightfunkin.net/friday-night-funkin-mods-fnf-play-online/"
              >FNF</a
            >
          </div>
          <style>
            .mapouter {
              position: relative;
              text-align: right;
              width: 600px;
              height: 400px;
            }
            .gmap_canvas {
              overflow: hidden;
              background: none !important;
              width: 600px;
              height: 400px;
            }
            .gmap_iframe {
              width: 600px !important;
              height: 400px !important;
            }
          </style>
        </div>
      </div>
    </section>
  </div>
</template>