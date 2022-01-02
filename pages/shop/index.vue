<template>
  <div id="shop">
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
    <section class="section">
      <div class="container">
        <div class="row">
          <div class="col-6">
            <div class="section__image">
              <img src="~/static/about1.jpeg" alt="" />
            </div>
          </div>
          <div class="col-6">
            <div class="about__wrapper">
              <h2 class="section__title light-brown">
                IT ALL STARTED WITH A SIMPLE THOUGHT...
              </h2>
              <div class="section__content">
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                <p>
                  Lorem ipsum dolor sit amet consectetur adipisicing elit.
                  Maxime mollitia, molestiae quas vel sint commodi repudiandae
                  consequuntur voluptatum laborum
                </p>
                <p>
                  Lorem ipsum dolor sit amet consectetur adipisicing elit.
                  Maxime mollitia, molestiae quas vel sint commodi repudiandae
                  consequuntur voluptatum laborum numquam blanditiis harum
                  quisquam eius sed odit fugiat iusto fuga praesentium optio,
                  eaque rerum! Provident similique accusantium nemo autem.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="section">
      <div class="container">
        <div class="row">
          <div class="col-6">
            <div class="about__wrapper">
              <h2 class="section__title light-brown">
                IT ALL STARTED WITH A SIMPLE THOUGHT...
              </h2>
              <div class="section__content">
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                <p>
                  Lorem ipsum dolor sit amet consectetur adipisicing elit.
                  Maxime mollitia, molestiae quas vel sint commodi repudiandae
                  consequuntur voluptatum laborum
                </p>
                <p>
                  Lorem ipsum dolor sit amet consectetur adipisicing elit.
                  Maxime mollitia, molestiae quas vel sint commodi repudiandae
                  consequuntur voluptatum laborum numquam blanditiis harum
                  quisquam eius sed odit fugiat iusto fuga praesentium optio,
                  eaque rerum! Provident similique accusantium nemo autem.
                </p>
              </div>
            </div>
          </div>
          <div class="col-6">
            <div class="section__image">
              <img src="~/static/about1.jpeg" alt="" />
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
  </div>
</template>