<script setup>

</script>

<template>
<!-- Body -->
<div class="container home">
  <div class="row">
    <div class="bagan-kiri col-lg-6">
    <p class="title">Pesan Paket Haji/Umrah hanya Dengan Menggunakan <span>Smartphone</span></p>
    <p class="sub-title">Nikmati kemudahan dalam pemesanan paket haji dan umrah tanpa harus ribet mengurus keluar rumah</p>
    <div class="btn col-md-7   col-lg-7 col-12">
      <button type="button" class="btn-default">Download Aplikasi</button>
    </div>
  </div>
  <div class="col-lg-6 ">
    <img class="img-hero" src="../images/89354.png" alt="">
  </div>
  </div>
</div>
</template>

<style>
.title{
  margin-top: 100px;
  font-size: 30px;
  font-weight: bolder;
}

.sub-title{
  font-size: 20px;
  color: grey;
}

.btn-default {
        background-color: #186049;
        color: white;
        border-radius: 25px;
        padding: 12px 50px;
    }
    .btn-default:hover,
    .btn-default:focus,
    .btn-default:active    {
        background-color: #053022;
        color: white;
    }


.img-hero{
  margin-top: 80px;
  max-width: 100%;
  height: auto;
  display: block;
  margin-left: auto;
  margin-right: auto;

}


@media screen and (max-width: 600px) {
  .title {
    text-align: center;
    font-size: 24px;
    margin-top: 20px;
  }
  .sub-title{
    text-align: center;
    font-size: 16px;
  }
}
</style>