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

    <p>Diatas adalah news berupa foto minimal 3 </p>
    <p>Promo (image 3 or 4)</p>
    <h4>Promo</h4>
    <div class="row mt-4">
      <div class="col-xs-6 col-lg-3">
        <div class="card mb-2">
          <img class="card-img-top" src="https://s3-ap-southeast-1.amazonaws.com/tees-static/banners/fTCsTm.png" alt="">
        </div>
      </div>
      <div class="col-xs-6 col-lg-3">
        <div class="card mb-2">
          <img class="card-img-top" src="https://s3-ap-southeast-1.amazonaws.com/tees-static/banners/vgoytT.png" alt="">
        </div>
      </div>
      <div class="col-xs-6 col-lg-3">
        <div class="card mb-2">
          <img class="card-img-top" src="https://s3-ap-southeast-1.amazonaws.com/tees-static/banners/ypcCIk.png" alt="">
        </div>
      </div>
      <div class="col-xs-6 col-lg-3">
        <div class="card mb-2">
          <img class="card-img-top" src="https://s3-ap-southeast-1.amazonaws.com/tees-static/banners/cGoURc.png" alt="">
        </div>
      </div>
    </div>

    <p>Kategori (slider kemungkinan)</p>
    <h4>Kategori</h4>
    <div class="row mt-4 mb-4">
      <div class="col" v-for="category in 5" :key="category">
        <div class="card">
          <div class="card-body pt-1 pb-1 pr-0 pl-0">
            <img src="https://ecs7-p.tokopedia.net/img/cache/200-square/product-1/2020/8/5/14668459/14668459_01334ad1-a548-4c2d-9c0f-af39b14b65c1_1024_1024.webp" width="64" height="64" alt=" ">
            <span>Jam Tangan</span>
          </div>
        </div>
      </div>
    </div>

    <p>Cuci Gudang (1 deret)</p>
    <h4>
      <span>Cuci Gudang</span>
      <span class="fs-14 float-right text-secondary">Lihat Semua</span>
    </h4>
    <div class="row mt-4 mb-4">
      <div class="col-6 col-md-2" v-for="onSale in 6" :key="onSale">
        <div class="card shadow mb-3 border-0-s size">
          <img class="card-img-top" src="https://ecs7-p.tokopedia.net/img/cache/200-square/product-1/2019/3/11/63220954/63220954_df5713b4-3f66-49b0-bdc3-087b7aaa87bd_1000_1000.jpg.webp" alt="Card image cap">
          <span class="wish flex-center">54%</span>
          <div class="card-body p-2">
            <p class="fs-14 mb-2 font-weight-light text-break">Kaos - Baju - Tshirt Deus Ex Machina 02 - Putih, M</p>
            <p class="fs-12 font-weight-light mb-2">
            <span class="text-danger">
              <s>Rp. 150.000</s>
            </span>
            <br>
            <span class="font-weight-bold">
              Rp. 150.000
            </span>
            </p>
            <p class="fs-12 font-weight-light">
            <span class="text-warning" v-for="star in 3" :key="star">
              <i class="fas fa-star"></i>
            </span>
            <span class="text-warning">
              <i class="fal fa-star"></i>
            </span>
            <span class="text-warning">
              <i class="fal fa-star"></i>
            </span>
            <span class="float-right text-muted">
              <i class="far fa-ellipsis-h"></i>
            </span>
            </p>
          </div>
        </div>
      </div>
    </div>

    <p>Paling Banyak Dilihat (2 deret / lebih)</p>
    <h4>Paling Banyak Dilihat</h4>
    <div class="row mt-4 mb-4">
      <div class="col-6 col-md-3" v-for="most in 8" :key="most">
        <div class="card shadow mb-3 border-0-s">
          <img class="card-img-top" src="https://tees.co.id/go/generate/preview/image?product_id=727000&color_id=187&model=kaos-pria&side=front&size=M" alt="Card image cap">
          <span class="wish flex-center">54%</span>
          <div class="card-body p-2">
            <p class="fs-14 mb-2 font-weight-light text-break">Kaos - Baju - Tshirt Deus Ex Machina 02 - Putih, M</p>
            <p class="fs-12 font-weight-light mb-2">
            <span class="text-danger">
              <s>Rp. 150.000</s>
            </span>
            <br>
            <span class="font-weight-bold">
              Rp. 150.000
            </span>
            </p>
            <p class="fs-12 font-weight-light">
            <span class="text-warning" v-for="star in 3" :key="star">
              <i class="fas fa-star"></i>
            </span>
            <span class="text-warning">
              <i class="fal fa-star"></i>
            </span>
            <span class="text-warning">
              <i class="fal fa-star"></i>
            </span>
            <span class="float-right text-muted">
              <i class="far fa-ellipsis-h"></i>
            </span>
            </p>
          </div>
        </div>
      </div>
    </div>

    <div class="text-center">
      <button type="button" class="btn btn-outline-secondary btn-lg">Muat Lebih Banyak</button>
    </div>
  </div>
</template>

<script>
import { VueperSlides, VueperSlide } from "vueperslides";
import "vueperslides/dist/vueperslides.css";

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
          slideRatio: 1 / 5
        },
        600: {
          slideRatio: 1 / 5,
          arrows: false,
          bulletsOutside: true
        }
      }
    };
  },
  components: { VueperSlides, VueperSlide }
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
.wish {
  background-color: red;
  color: white;
  border-radius: 50% 0 50% 50%;
  font-size: 12px !important;
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
}
.size {
  width: 179px !important;
}

</style>
