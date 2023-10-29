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
      <p class="text-3xl font-semibold">Visi & Misi Desa Sukawening</p>
      <p class="text-lg font-semibold">Visi</p>
      <p>
        “Mewujudkan desa sukawening Tangguh ( tanggap,Giat dan utuh )”
      </p>
      <p class="text-lg font-semibold">Misi</p>
      <ul>
        <li>
          1. Menyelenggarakan  Pemerintahan Desa yang bersih,terbebas dari korupsi serta bentuk penyelewengan lainnya.
        </li>
        <li>
          2. Meningkatkan perekonomian masyarakat melalui pendampingan berupa penyuluhan khusus kepada UMKM,wiraswasta dan petani
        </li>
        <li>
          3. Meningkatkan prekonomian masyarakat untuk mencapai taraf kehidupan yang lebih baik dan layak sehingga menjadi desa yang maju dan mandiri
        </li>
        <li>
          4. Menumbuh kembangkan perekonomian masyarakat melalui pemberdayaan UMKM dan mengembangkan ketahanan pangan menjadi sentra ekonomi masyarakat.
        </li>
        <li>
          5. Meningkatkan Kembali sarana olah raga,bola volley,bulutangkis dan lainnya
        </li>
        <li>
          6. Penggalian potensi untuk program desa wisata guna meningkatkan perekonomian masyarakat
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
