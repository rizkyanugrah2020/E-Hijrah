<template>
<!-- Body -->
<div class="container">
  <div class="column">
    <h1 class="fw-bold">Tentang E-Hijrah</h1>
    <div class="p-3">
        <h6>
            E-Hijrah merupakan sebuah startup yang bergerak dalam bidang layanan jasa penyelenggaraan ibadah haji dan umrah
        </h6>
    </div>
    <div class="column">
        <h5>Visi</h5>
        <h6
            v-for="v in visi"
            :key="v">- {{ v }}</h6>
    </div>

    <div class="column">
        <h5>Misi</h5>
        <h6
            v-for="m in misi"
            :key="m">- {{ m }}</h6>
    </div>
  </div>
</div>
</template>
<script>
export default {
  data () {
    return {
        visi: [
            'Menjadi Penyedia Jasa Haji dan Umrah Pilihan Masyarakat'
        ],
        misi: [
            'Memahami beragam kebutuhan calon jemaah haji dan umrah',
            'Menambah nilai tambah bagi para mitra biro haji'
        ]
    }
  }
}
</script>
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
</style>