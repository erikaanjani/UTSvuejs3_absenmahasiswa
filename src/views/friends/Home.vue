<template>
  <div class="home">
    <!--  <img alt="Vue logo" src="../assets/logo.png"> -->
    <Slider />
    <hr class = "my-3">
    <router-link class="btn btn-primary" to="/createfriends">TAMBAHKAN DATA MAHASISWA</router-link>
    <table class="table">
  <thead>
    <tr>
      <th scope="col">NO</th>
      <th scope="col">ID</th>
      <th scope="col">NAMA MAHAISWA</th>
      <th scope="col">ALAMAT</th>
      <th scope="col">NO TELP</th>
      <th scope="col">EMAIL</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row">1</th>
      <td>2018114014</td>
      <td>Erika Anjani</td>
      <td>Cirebon</td>
      <td>67521</td>
      <td>erika@gmail.com</td>
    </tr>
    <tr>
      <th scope="row">3</th>
      <td>2018114008</td>
      <td>Selvi Feliyanti</td>
      <td>Cirebon</td>
      <td>76543</td>
      <td>mpi@gmail.com</td>
    </tr>
    <tr>
      <th scope="row">4</th>
      <td>2018114006</td>
      <td>Lala Nurjanah</td>
      <td>Cirebon</td>
      <td>12345</td>
      <td>lala@gmail.com</td>
    </tr>
    <tr>
      <th scope="row">5</th>
      <td>2018114021</td>
      <td>Diana Kusuma Dewi</td>
      <td>Cirebon</td>
      <td>954367</td>
      <td>diana@gmail.com</td>
    </tr>
    <tr>
      <th scope="row">6</th>
      <td>2018114016</td>
      <td>Hendra Wijaya</td>
      <td>Cirebon</td>
      <td>34278</td>
      <td>hendra@gmail.com</td>
    </tr>
     <tr>
      <th scope="row">7</th>
      <td>2018114003</td>
      <td>Dewi silvia</td>
      <td>Cirebon</td>
      <td>223445</td>
      <td>dewi@gmail.com</td>
    </tr>
    <tr>
      <th scope="row">8</th>
      <td>2018114019</td>
      <td>Adriel Alfa</td>
      <td>Cirebon</td>
      <td>776554</td>
      <td>adriel@gmail.com</td>
    </tr>
  </tbody>
</table>
  </div>
</template>

<script>
// @ is an alias to /src
import Slider from "@/components/Slider.vue";
export default {
  name: 'Home',
  components: {
    Slider,
  },

};
</script>