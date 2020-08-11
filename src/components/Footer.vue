<template>
  <footer>
    <hr class="mx-0 px-0" />
    <div class="row justify-content-around mb-0 pt-2 pb-0 ">
      <div class="col-11">
          <div class="container">
        <div class="row justify-content-center">
          <div
            class="col-md-12 col-lg-3 col-12 font-italic align-items-center mt-md-3 mt-4"
          >
            <h5>
              <span>
                <img src="@/assets/tridatu.png" class="img-fluid mb-1 "/></span
              ><b class="text-dark">
                Tridatu<span class="text-muted"> Bali ID</span></b
              >
            </h5>
            <p class="social mt-3 mb-3">
              <span><i class="fab fa-facebook-square"></i></span>
              <span><i class="fab fa-instagram-square"></i></span>
              <span><i class="fab fa-twitter-square"></i></span>
              <span><i class="fab fa-google-plus-square"></i></span>
            </p>
            <small class="copy-rights cursor-pointer"
              >&#9400; 2020 Tridatu Bali ID</small
            ><br />
            <small>All Right Reserved</small>
          </div>
          <div class="col-md-12 col-lg-3 col-12 my-sm-0 mt-5">
            <ul class="list-unstyled">
              <li class="mt-md-3 mt-4">Kontak</li>
              <li><i class="far fa-phone-alt mr-2"></i>+628113885929</li>
              <li>
                <i class="far fa-envelope mr-2"></i>support@tridatu-bali.id
              </li>
              <li>
                Jl. Muding Tengah, Bougenville No. 18 Kerobokan, Kuta Utara,
                Badung, Bali 80361
              </li>
            </ul>
          </div>
          <div class="col-md-12 col-lg-3 col-12 my-sm-0 mt-5">
            <ul class="list-unstyled ml-5">
              <li class="mt-md-3 mt-4">Informasi</li>
              <li>Tentang Kami</li>
              <li>Panduan Belanja</li>
              <li>Syarat & Ketentuan</li>
              <li>Kebijakan Privasi</li>
            </ul>
          </div>
          <div class="col-md-12 col-lg-3 col-12 my-sm-0 mt-5">
            <ul class="list-unstyled multi-bank">
              <li class="mt-md-3 mt-4 mb-2">Metode Pengiriman</li>
              <div class="img-bank">
                  <img
                    src="https://www.gramedia.com/assets/bank/payment-mandiri.png"
                    class="w-48"
                    alt="..."
                  />
                  <img
                    src="https://www.gramedia.com/assets/bank/payment-permata.png"
                    class="w-48"
                    alt="..."
                  />
                  <img
                    src="https://www.gramedia.com/assets/bank/payment-bni.png"
                    class="w-48"
                    alt="..."
                  />
                  <img
                    src="https://www.gramedia.com/assets/bank/payment-bri.png"
                    class="w-48"
                    alt="..."
                  />
                  <img
                    src="https://www.gramedia.com/assets/bank/payment-bca.png"
                    class="w-48"
                    alt="..."
                  />
                  <img
                    src="https://www.gramedia.com/assets/bank/payment-go-pay.png"
                    class="w-48"
                    alt="..."
                  />
                  <img
                    src="https://www.gramedia.com/assets/bank/payment-ovo.png"
                    class="w-48"
                    alt="..."
                  />
              </div>
            </ul>
            <ul class="list-unstyled multi-bank">
              <li class="mt-md-3 mt-4 mb-2">Metode Pengiriman</li>
              <div class="img-bank">
                  <img
                    src="https://www.gramedia.com/assets/shipping/shipping-kg-logistik.png"
                    class="w-48"
                    alt="..."
                  />
                  <img
                    src="https://www.gramedia.com/assets/shipping/shipping-pick-up-in-store.png"
                    class="w-48"
                    alt="..."
                  />
                  <img
                    src="https://www.gramedia.com/assets/shipping/shipping-grab.png"
                    class="w-48"
                    alt="..."
                  />
              </div>
            </ul>
          </div>
        </div>
          </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {};
</script>

<style scoped>
.fab {
  cursor: pointer;
  font-size: 25px;
  margin: 5px 5px 5px 10px !important;
}

.social {
  position: relative;
  left: -10px;
}

.cursor-pointer {
  cursor: pointer !important;
  color: green;
  font-weight: bold;
}

h5 {
  font-size: calc(
    20px + (28 - 20) * ((100vw - 360px) / (1600 - 360))
  ) !important;
}

li {
  margin-top: 10px;
  margin-bottom: 10px;
}

img {
  vertical-align: middle !important;
  width: 100%;
  height: auto;
  width: calc(17px + 6 * ((100vw - 320px) / 680));
}

li:first-child {
  font-size: 21px !important;
  font-weight: bold;
  margin-bottom: calc(
    20px + (48 - 40) * ((100vw - 360px) / (1600 - 360))
  );
  color: #757575 !important;
}

footer {
  color: #757575 !important;
}
.w-48 {
  width: 48px !important;
  height: 48px !important;
  margin: 0px 2px;
}
.img-bank {
  display: flex;
  flex-wrap: wrap;
}
.multi-bank {
  max-width: 216px;
}
</style>
