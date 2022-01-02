<template>
  <header class="kf-header"  :class="[isWhite ? 'solid' : '']">
    <div class="container">
      <b-navbar toggleable="lg" type="dark">
        <b-navbar-brand href="#">
          missioncoffeeusa
        </b-navbar-brand>

        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

        <b-collapse id="nav-collapse" is-nav>
          <b-navbar-nav>
            <b-nav-item href="/about">About</b-nav-item>
            <b-nav-item href="/shop">Shop</b-nav-item>
            <b-nav-item href="/contact">Contact</b-nav-item>
          </b-navbar-nav>
        </b-collapse>
      </b-navbar>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header",
  data() {
    return {
        isWhite:false
    };
  },
  methods: {
    toggleTransparency() {
      let currentScrollPos = window.pageYOffset;
      if (currentScrollPos > 50) {
        this.isWhite = true;
      } else {
        if (this.$route.name === null) {
          this.isWhite = true;
        } else {
          this.isWhite = false;
        }
      }
    },
  },
  mounted() {
    document.addEventListener("scroll", this.toggleTransparency);
  },
  destroyed() {
    document.removeEventListener("scroll", this.toggleTransparency);
  },
};
</script>