<template>
  <div class="container">
    <vueper-slides
      class="no-shadow mt-7"
      :breakpoints="breakpoints"
      :visible-slides="3"
      :dragging-distance="35"
      autoplay
    >
      <vueper-slide v-for="i in 4" :key="i" :title="i.toString()" />
    </vueper-slides>

    <h4>Promo</h4>
    <div class="row mt-4 mb-5 row-cols-2  row-cols-md-4 row-cols-lg-4 row-cols-xl-4">
      <div class="col p-8-s">
        <div class="card mb-2 shadow-sm">
          <img class="card-img-top" src="https://s3-ap-southeast-1.amazonaws.com/tees-static/banners/fTCsTm.png" alt="">
        </div>
      </div>
      <div class="col p-8-s">
        <div class="card mb-2 shadow-sm">
          <img class="card-img-top" src="https://s3-ap-southeast-1.amazonaws.com/tees-static/banners/vgoytT.png" alt="">
        </div>
      </div>
      <div class="col p-8-s">
        <div class="card mb-2 shadow-sm">
          <img class="card-img-top" src="https://s3-ap-southeast-1.amazonaws.com/tees-static/banners/ypcCIk.png" alt="">
        </div>
      </div>
      <div class="col p-8-s">
        <div class="card mb-2 shadow-sm">
          <img class="card-img-top" src="https://s3-ap-southeast-1.amazonaws.com/tees-static/banners/cGoURc.png" alt="">
        </div>
      </div>
    </div>

    <h4>
      <span>Kategori</span>
      <a href="#" class="fs-14 float-right text-secondary pt-2">Lihat semua</a>
    </h4>
    <div class="row mt-4 mb-5 row-cols-2  row-cols-md-4 row-cols-lg-5 row-cols-xl-5">
      <div class="col p-8-s">
        <div class="card shadow-sm text-center mb-3">
          <a href="#" class="text-decoration-none text-dark">
            <img class="mx-auto d-block mt-2" src="https://ecs7-p.tokopedia.net/img/cache/200-square/product-1/2020/5/6/52528683/52528683_9bcede64-a420-4075-8dd5-8770416a1d9e_1500_1500.webp" width="64" height="64" alt=" ">
            <div class="card-body">
              <span class="font-weight-bold">Baju</span>
            </div>
          </a>
        </div>
      </div>

      <div class="col p-8-s">
        <div class="card shadow-sm text-center mb-3">
          <a href="#" class="text-decoration-none text-dark">
            <img class="mx-auto d-block mt-2" src="https://ecs7-p.tokopedia.net/img/cache/200-square/product-1/2020/7/2/19632696/19632696_8c5fd13f-bc6d-491a-85a0-5e0e7b496b1d_800_800.webp" width="64" height="64" alt=" ">
            <div class="card-body">
              <span class="font-weight-bold">Jaket</span>
            </div>
          </a>
        </div>
      </div>

      <div class="col p-8-s d-none d-md-block">
        <div class="card shadow-sm text-center mb-3">
          <a href="#" class="text-decoration-none text-dark">
            <img class="mx-auto d-block mt-2" src="https://ecs7-p.tokopedia.net/img/cache/200-square/attachment/2019/4/10/15548853000097/15548853000097_eac117c4-ac02-48c9-9531-b0035275f318.png.webp" width="64" height="64" alt=" ">
            <div class="card-body">
              <span class="font-weight-bold">Celana Pria</span>
            </div>
          </a>
        </div>
      </div>

      <div class="col p-8-s d-none d-md-block">
        <div class="card shadow-sm text-center mb-3">
          <a href="#" class="text-decoration-none text-dark">
            <img class="mx-auto d-block mt-2" src="https://ecs7-p.tokopedia.net/img/cache/200-square/product-1/2020/1/9/458544/458544_30823d7d-50a5-4ad2-8078-dfdb1bf0f03b_800_800.webp" width="64" height="64" alt=" ">
            <div class="card-body">
              <span class="font-weight-bold">Aksesoris</span>
            </div>
          </a>
        </div>
      </div>

      <div class="col p-8-s d-none d-lg-block">
        <div class="card shadow-sm text-center mb-3">
          <a href="#" class="text-decoration-none text-dark">
            <img class="mx-auto d-block mt-2" src="https://ecs7-p.tokopedia.net/img/cache/200-square/product-1/2020/8/6/707313048/707313048_4e71aa4e-8988-4191-91ea-3c3c138d61f1_709_709.jpg.webp" width="64" height="64" alt=" ">
            <div class="card-body">
              <span class="font-weight-bold">Tas Selempang</span>
            </div>
          </a>
        </div>
      </div>
    </div>

    <h4>
      <span>Cuci Gudang</span>
      <a href="#" class="fs-14 float-right text-secondary pt-2">Lihat semua</a>
    </h4>
    <div class="row mt-4 mb-5 row-cols-2  row-cols-md-3 row-cols-lg-4 row-cols-xl-5">
      <div class="col-6 col-lg col-md-4" v-for="onSale in 5" :key="onSale">
        <div class="card shadow mb-3 border-0-s">
          <a href="#">
            <img class="card-img-top img-fit" src="https://www.specialbrandstore.com/wp-content/uploads/2017/08/3978-rvca-zap-va_1-330x0.jpg" alt="Card image cap">
            <span class="discount">70%</span>
            <i class="fas fa-heart wish"></i>
          </a>
          <div class="card-body p-2">
            <a href="#" class="text-decoration-none text-secondary">
              <p class="fs-14 mb-2 font-weight-light text-break">Kaos - Baju - Tshirt Deus Ex Machina 02 - Putih, M</p>
            </a>
            <p class="fs-12 font-weight-light mb-2">
            <span class="text-danger">
              <s>Rp. 150.000</s>
            </span>
            <br>
            <span class="font-weight-bold h6">
              Rp. 105.000
            </span>
            </p>
            <p class="fs-12 font-weight-light">
              <star-rating :rating="4" :star-size="14" :read-only="true" :show-rating="false"
                active-color="#ffb700">
              </star-rating>
            </p>
          </div>
        </div>
      </div>
    </div>

    <h4>Paling Banyak Dilihat</h4>
    <div class="row mt-4 mb-2 row-cols-2  row-cols-md-3 row-cols-lg-4 row-cols-xl-5">
      <div class="col" v-for="most in 10" :key="most">
        <div class="card shadow mb-3 border-0-s">
          <img class="card-img-top img-fit" src="https://www.specialbrandstore.com/wp-content/uploads/2017/08/3978-rvca-zap-va_1-330x0.jpg" alt="Card image cap">
          <span class="discount">70%</span>
          <i class="fas fa-heart wish"></i>
          <div class="card-body p-2">
            <a href="#" class="text-decoration-none text-secondary">
              <p class="fs-14 mb-2 font-weight-light text-break">Kaos - Baju - Tshirt Deus Ex Machina 02 - Putih, M</p>
            </a>
            <p class="fs-12 font-weight-light mb-2">
            <span class="text-danger">
              <s>Rp. 150.000</s>
            </span>
            <br>
            <span class="font-weight-bold h6">
              Rp. 105.000
            </span>
            </p>
            <p class="fs-12 font-weight-light">
              <star-rating :rating="4" :star-size="14" :read-only="true" :show-rating="false"
                active-color="#ffb700">
              </star-rating>
            </p>
          </div>
        </div>
      </div>
    </div>

    <div class="text-center mb-5">
      <button type="button" class="btn btn-outline-secondary btn-lg">Muat Lebih Banyak</button>
    </div>
  </div>
</template>

<script>
import { VueperSlides, VueperSlide } from "vueperslides";
import "vueperslides/dist/vueperslides.css";
import StarRating from 'vue-star-rating'

export default {
  data() {
    return {
      breakpoints: {
        2000: {
          slideRatio: 1 / 5
        },
        1400: {
          slideRatio: 1 / 5
        },
        900: {
          slideRatio: 1 / 4
        },
        600: {
          slideRatio: 1 / 4,
          arrows: false,
          bulletsOutside: true
        }
      }
    };
  },
  components: { VueperSlides, VueperSlide, StarRating }
};
</script>

<style>
.vueperslide {
  color: #fff;
  background: #42b983;
  transition: 0.3s ease-in-out;
  transform: scale(0.8);
}
.vueperslide--active {
  transform: scale(1);
}
.vueperslide__title {
  font-size: 2em;
}
.vueperslides__bullet .default {
  background-color: rgba(0, 0, 0, 0.3);
  border: none;
  box-shadow: none;
  transition: 0.3s;
}
.vueperslides__bullet--active .default {
  background-color: #42b983;
}
.mt-7 {
  margin-top: 7rem;
}
.fs-12 {font-size: 12px !important;}
.fs-14 {font-size: 14px !important;}
.discount {
  background-color: #d83832;
  color: white;
  border-radius: 0 60% 60% 60%;
  font-size: 12px !important;
  left: 0 !important;
  top: 0 !important;
  z-index: 100;
  position: absolute;
  width: 40px;
  height: 40px;
  align-items: center;
  display: flex;
  justify-content: center;
}
.wish {
  background-color: white;
  color: red;
  border-radius: 50% 0 50% 50%;
  font-size: 16px !important;
  right: 0 !important;
  top: 0 !important;
  z-index: 100;
  position: absolute;
  width: 40px;
  height: 40px;
  align-items: center;
  display: flex;
  justify-content: center;
}
@media (max-width: 767.98px) { 
  .border-0-s {
     border: 0!important;
     box-shadow: none !important;
  }
  .p-8-s {
    padding: 8px !important;
  }
}
.img-fit {
  object-fit: cover;
}

</style>
