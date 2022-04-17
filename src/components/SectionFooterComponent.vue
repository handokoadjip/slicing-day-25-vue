<template>
  <section class="p-5 bg-white-80">
    <div class="container d-flex justify-content-center align-items-center">
      <div class="row w-100 pt-5">
        <div class="col-lg-3 mb-5 mb-lg-0">
          <div class="wrapper text-black text-center text-lg-start">
            <h3 class="mb-4 fw-bold text-border-bottom">Our Company Is Here 4u</h3>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit.</p>
            <router-link class="text-decoration-underline text-black fw-medium" to="#">read more</router-link>
          </div>
        </div>
        <div class="col-lg-3 mb-5 mb-lg-0">
          <div class="wrapper text-black text-center text-lg-start">
            <h3 class="fs-6 mb-4 text-uppercase fw-bold text-border-bottom">post</h3>
            <div class="section-1 mb-4">
              <p class="text-black text-decoration-none mb-1 d-block fw-medium" to="#">Lorem ipsum dolor sit amet
                consectetur.</p>
              <p class="text-fade-black-1">23 Dec 2022</p>
            </div>
            <div class="section-1">
              <p class="text-black text-decoration-none mb-1 d-block fw-medium" to="#">Lorem ipsum dolor sit amet
                consectetur.</p>
              <p class="text-fade-black-1">23 Dec 2022</p>
            </div>
          </div>
        </div>
        <div class="col-lg-3 mb-5 mb-lg-0">
          <div class="wrapper text-black text-center text-lg-start">
            <h3 class="fs-6 mb-4 text-uppercase fw-bold text-border-bottom">product</h3>
            <nav class="fw-medium">
              <router-link class="text-black text-decoration-none mb-1 d-block" to="#">Lorem</router-link>
              <router-link class="text-black text-decoration-none mb-1 d-block" to="#">Ipsum</router-link>
              <router-link class="text-black text-decoration-none mb-1 d-block" to="#">Dolor</router-link>
              <router-link class="text-black text-decoration-none mb-1 d-block" to="#">Sit</router-link>
              <router-link class="text-black text-decoration-none mb-1 d-block" to="#">Amet</router-link>
              <router-link class="text-black text-decoration-none mb-1 d-block" to="#">consectetur</router-link>
            </nav>
          </div>
        </div>
        <div class="col-lg-3 mb-5 mb-lg-0">
          <div class="wrapper text-black text-center text-lg-start">
            <h3 class="fs-6 mb-4 text-uppercase fw-bold text-border-bottom">contact</h3>
            <nav class="fw-medium">
              <router-link class="text-black text-decoration-none mb-1 d-block" to="#">Lorem</router-link>
              <router-link class="text-black text-decoration-none mb-1 d-block" to="#">Ipsum</router-link>
              <router-link class="text-black text-decoration-none mb-1 d-block" to="#">Dolor</router-link>
              <router-link class="text-black text-decoration-none mb-1 d-block" to="#">Sit</router-link>
              <router-link class="text-black text-decoration-none mb-1 d-block" to="#">Amet</router-link>
              <router-link class="text-black text-decoration-none mb-1 d-block" to="#">consectetur</router-link>
            </nav>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "SectionFooterComponent",
}
</script>