<script setup>
import Header from "../components/Header.vue";
import Banner from "../components/Banner.vue";
import Sidebar from "../components/Sidebar.vue";
</script>

<template>
  <Header />
  <Banner />

  <main class="flex">
    <Sidebar />

    <div class="flex-1 p-10">
      <p class="text-3xl font-semibold">Visi & Misi Desa</p>
      <p class="text-lg font-semibold">Visi</p>
      <p>
        TERKESIMA
“Terwujudnya Kesejahtraan Masyarakat”
Desa Pasirgaok pada Tahun 2023 – 2029

      </p>
      <p class="text-lg font-semibold">Misi</p>
      <ul>
        <li>
          1. Terbentuknya masyarakat kurang mampu dalam pemenuhan kebutuhan dasar dan Ekonomi; 
        </li>
        <li>
          2.	Terwujudnya pembangunan dan pelayanan publik masyarakat Desa Pasirgaok; 
        </li>
        <li>
         3.	Terwujudnya pembangunan berkelanjutan yang berwawasan lingkungan serta peduli perempuan dan anak berdasarkan sosial budaya.
        </li>
        <li>
          4. Meningkatkan kemampuan dan peran serta aktif masyarakat dalam
          mengelola pembangunan berkelanjutan secara efisisen dan efektif dengan
          memanfaatkan potensi sumber daya yang ada, baik sumber daya alam
          maupun sumberdaya manusia;
        </li>
        <li>
        </li>
      </ul>
    </div>
  </main>
</template>

<style>
body {
  background: #f1f1f1;
}
</style>
