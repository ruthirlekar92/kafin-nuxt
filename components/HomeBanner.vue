<template>
    <section class="banner">
        <video
            class="video"
            aria-label="banner video"
            playsinline="playsinline"
            muted="muted"
            autoplay="autoplay"
            loop="loop"
            src="~/static/rostedcoffee.mp4"
          ></video>
          <div class="banner__wrapper">
                <b-container>
                    <b-row>
                        <b-col cols="12" >
                            <div class="banner__content">
                                <h1 class="title">TOP QUALITY COFFEE BEANS</h1>
                                <p class="">Aptent sociosqu vehicula tellus mauris molestie neque et venenatis, congue cubilia justo aliquam habitasse risus quisque sed semper montes.</p>
                                <kf-buttons text="Shop" color="white" type="link"></kf-buttons>
                            </div>
                        </b-col>
                    </b-row>
                </b-container>
          </div>
    </section>
</template>