<template>
  <div class="matakuliah">
    <!--  <img alt="Vue logo" src="../assets/logo.png"> -->
    <Slider />
    <hr class = "my-3">
    <router-link class="btn btn-primary" to="/createfriends">TAMBHAKAN DATA MAHASISWA</router-link>
    <table class="table">
  <thead>
    <tr>
      <th scope="col">NO</th>
      <th scope="col">ID</th>
      <th scope="col">MATAKULIAH</th>
      <th scope="col">SKS</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row">1</th>
      <td>2018114014</td>
      <td>Pemrograman Internet</td>
      <td>4</td>
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
  name: 'Matakuliah',
  components: {
    Slider,
  },

};
</script>