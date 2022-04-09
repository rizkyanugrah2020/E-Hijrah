<template>
<!-- Body -->
<div class="container">
  <div class="column">
    <div class="row">
      <div
        v-for="i in cards"
        :key="i"
        class="col-md-4 col-lg-4 col-12 p-2">
        <div class="card">
          <div class="card-body">
            <h5 class="card-title fw-bold">{{ i.title }}</h5>
            <h6 class="card-subtitle mb-2 text-muted"> {{ i.desc }} </h6>
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
</template>
<script>
export default {
  data () {
    return {
      cards: [
        {
          title: 'Langkah 1',
          desc: 'Download Aplikasi E-Hijrah'
        },
        {
          title: 'Langkah 2',
          desc: 'Lakukan Pendaftaran Akun'
        },
        {
          title: 'Langkah 3',
          desc: 'Pilih Jenis Paket'
        },
        {
          title: 'Langkah 4',
          desc: 'Masukan Dokumen'
        },
        {
          title: 'Langkah 5',
          desc: 'Lakukan Pembayaran'
        }
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