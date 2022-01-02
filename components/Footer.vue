<template>
  <footer class="kf__footer">
    <div class="container">
      <div class="row">
        <div class="col-12">
          <div class="kf__footer--wrapper">
            <div class="company">
              <nuxt-link class="logo" to="/">
                <!-- <img src="~/static/kafinnew.png" alt="Kafin" /> -->
                missioncoffeeusa
              </nuxt-link>
            </div>
            <div class="links">
              <ul class="links__list">
                <li class="links__list--item">
                  <nuxt-link to="/">About</nuxt-link>
                </li>
                <li class="links__list--item">
                  <nuxt-link to="/">Tea</nuxt-link>
                </li>
                <li class="links__list--item">
                  <nuxt-link to="/">Coffee</nuxt-link>
                </li>
                <li class="links__list--item">
                  <nuxt-link to="/">Subscription</nuxt-link>
                </li>
              </ul>
            </div>
            <div class="social">
              <ul class="social__list">
                <li class="social__list--item">
                  <a href="https://www.facebook.com/Kafin-101071312376121"
                    ><i class="bi bi-facebook"></i
                  ></a>
                </li>
                <li class="social__list--item">
                  <a href="https://www.instagram.com/kafinindia/"
                    ><i class="bi bi-instagram"></i
                  ></a>
                </li>
                <li class="social__list--item">
                  <a href="/"><i class="bi bi-linkedin"></i></a>
                </li>
                <li class="social__list--item">
                  <nuxt-link to="/"><i class="bi bi-whatsapp"></i></nuxt-link>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>