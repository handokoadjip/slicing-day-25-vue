<template>
  <footer class="bg-white">
    <div class="container-fluid">
      <div class="row align-items-center h-vh-30">
        <div class="col-lg-2 bg-black py-3 mb-3 mb-lg-0">
          <div class="wrapper text-center text-lg-start">
            Lorem ipsum / dolor sit
          </div>
        </div>
        <div class="col-lg-9">
          <div class="wrapper text-center text-lg-start">
            <div class="copyright d-block d-lg-flex justify-content-lg-between align-items-lg-center text-center">
              <div class="mb-5 mb-lg-0">
                <router-link
                  class="text-black text-uppercase mp-0 fw-bolder ls-5px d-flex justify-content-center align-items-start"
                  to="#">
                  <small class="fw-normal me-2">GIE</small>
                  / FINNHUTTE
                </router-link>
              </div>
              <div class="mb-5 mb-lg-0">
                <p class="mp-0 text-black">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quos, sed.</p>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-1 d-flex justify-content-end">
          <div class="wrapper text-center border text-black text-center p-2 w-50">
            T
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "FooterComponent",
}
</script>