<template>
  <div class="hero">
    <div class="d-md-block d-none">
      <div class="row mt-4">
        <div class="col-md-6">
          <div class="d-flex h-100">
            <div class="justify-content-center align-self-center">
              <h2>
                <strong> Delicious Foods Menu,</strong> <br />
                in Your Gadget
              </h2>
              <p>Ayo segera pesan dan pilih makanan favorit Anda</p>
              <router-link class="btn btn-success btn-lg" to="/foods">
                <b-icon-arrow-right></b-icon-arrow-right> Pesan
              </router-link>
            </div>
          </div>
        </div>
        <div class="col-md-6">
          <img src="../assets/image/hero.svg" alt="" width="100%" />
        </div>
      </div>
    </div>
    <div class="d-sm-block d-md-none">
      <div class="row mt-4">
        <div class="col-md-6 mb-3">
          <img src="../assets/image/hero.svg" alt="" width="100%" />
        </div>
        <div class="col-md-6">
          <div class="d-flex h-100">
            <div class="justify-content-center align-self-center">
              <h2>
                <strong> Delicious Foods Menu,</strong> <br />
                in Your Gadget
              </h2>
              <p>Ayo segera pesan dan pilih makanan favorit Anda</p>
              <button class="btn btn-success btn-lg">
                <b-icon-arrow-right></b-icon-arrow-right> Pesan
              </button>
            </div>
          </div>
        </div>
        
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Hero",
};
</script>

<style>
</style>