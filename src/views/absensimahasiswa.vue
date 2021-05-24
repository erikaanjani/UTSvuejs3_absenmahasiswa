<template>
  <div class="absensimahasiswa">
    <!--  <img alt="Vue logo" src="../assets/logo.png"> -->
    <Slider />
    <hr class = "my-3">
    <router-link class="btn btn-primary" to="/createfriends">TAMBAHKAN DATA MAHASISWA/router-link>
    <table class="table">
  <thead>
    <tr>
      <th scope="col">NO</th>
      <th scope="col">ID/th>
      <th scope="col">WAKTU ABSEN</th>
      <th scope="col">NAMA MAHASISWA</th>
      <th scope="col">MATAKULIAH</th>
      <th scope="col">KETERANGAN</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row">1</th>
      <td>2018114014</td>
      <td>10.00</td>
      <td>Erika Anjani</td>
      <td>Pemograman Internet</td>
      <td>Hadir</td>
      <td>

      </td>
    </tr>
    
  </tbody>
</table>
  </div>
</template>

<script>
// @ is an alias to /src
import Slider from "@/components/Slider.vue";
export default {
  name: 'Absensimahasiswa',
  components: {
    Slider,
  },

};
</script>