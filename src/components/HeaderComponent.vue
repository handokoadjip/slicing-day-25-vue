<template>
  <header class="min-vh-100 position-relative">
    <nav class="navbar navbar-expand-lg fixed-top bg-black navbar-dark px-4">
      <div class="container-fluid py-4 d-flex">
        <router-link class="navbar-brand text-center text-uppercase mp-0 fw-bolder fs-5 ls-5px d-flex align-items-start"
          to="#">
          <small class="fw-normal me-2">GIE</small>
          / FINNHUTTE
        </router-link>

        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
          aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav text-uppercase ms-auto">
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link text-center" aria-current="page" to="#">home</router-link>
            </li>
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link text-center" to="#">pages</router-link>
            </li>
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link text-center" to="#">portofolio</router-link>
            </li>
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link text-center" to="#">shop</router-link>
            </li>
            <li class="nav-item px-0 px-lg-4">
              <router-link class="nav-link text-center" to="#">comment</router-link>
            </li>
          </ul>
        </div>
      </div>
    </nav>

    <section>
      <div class="container-fluid p-0">
        <div class="row">
          <div class="col-lg-12">
            <div class="bg-image-1">
              <div
                class="d-flex flex-column justify-content-center align-items-center text-white text-center mt-5 min-vh-100 position-relative z-999">
                <h1 class="display-3 fw-medium text-border-bottom-center mb-3">Architecture Projects</h1>
                <p class="w-50 fs-5">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Dolorem autem illo
                  explicabo cum ut maiores.</p>
                <router-link class="btn bg-white py-3 px-5 text-black text-decoration-underline" to="#">Read More
                </router-link>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </header>
</template>

<script>
export default {
  name: "HeaderComponent",
}
</script>

