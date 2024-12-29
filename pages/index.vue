<template>
  <div class="container-fluid">
    <div>
      <CoverVidio />
    </div>

    <!-- sambutan -->
    <div class="grid md:grid-cols-2 grid-cols-1 pt-10 md:pt-20 bg-blue-700 mt-10 px-4 md:px-8 gap-8 pb-10">
      <div class="flex flex-col items-center">
        <div class="w-full max-w-md flex flex-col items-center space-y-2">
          <img src="~/assets/img/kepalasekolah.png" alt="Kepala Sekolah" class="" />
          <div class="text-center">
            <h3 class="text-lg md:text-xl font-semibold text-gray-100">Kurniawan, S.Pd, M.Pd.</h3>
            <p class="text-gray-200">Kepala Sekolah</p>
          </div>
        </div>
      </div>

      <div class="mt-4 md:mt-10">
        <div class="block p-4 md:p-6 border border-gray-200 rounded-lg shadow">
          <h5 class="mb-4 md:mb-5 text-2xl md:text-4xl text-center font-bold tracking-tight text-white">Sambutan Kepala Sekolah</h5>
          <p class="font-normal text-justify text-white text-sm md:text-base leading-relaxed">
            Assalamualaikum Warahmatullahi Wabarakatuh
            <br />
            Selamat datang di SMKN 4 Tasikmalaya. Segala puji dan syukur kita panjatkan kehadirat Allah SWT, semoga kita semua ada dalam lindungan-Nya. Dan atas perkenan-Nya pula kami dapat menghadirkan website SMK Negeri 4 Tasikmalaya ini.
            Kami berharap dengan adanya website di SMK Negeri 4 Tasikmalaya ini para pengunjung dapat mengenal lebih jauh tentang sekolah kami sehingga dapat mempererat tali silaturrahmi antara sekolah dengan masyarakat demi kemajuan kita
            bersama. Tiada gading yang tak retak, website kami ini masih dalam proses pengembangan, masih banyak kekurangan yang harus kami perbaiki. Kritik dan sarannya yang membangun sangat kami harapkan untuk pengembangan ke depan.
            Akhirnya, saya mengucapkan terimakasih yang sebesar-besarnya kepada semua pihak yang tidak dapat disebutkan satu segala bantuan dan persatu atas fasilitasnya yang telah diberikan semoga semua yang kita lakukan bermanfaat bagi
            masyarakat. Wassalamu'alaikum Warahmatullahi Wabarakatuh.
          </p>
        </div>
      </div>
    </div>

    <!-- informasi jumlah guru siswa -->
    <Informasi />
    <!-- berita -->
    <div class="min-h-screen bg-blue-700">
      <section class="py-16 px-4">
        <div class="max-w-6xl mx-auto">
          <div class="text-center mb-12">
            <h2 class="text-3xl font-bold text-white mb-2">Berita & Artikel</h2>
            <div class="w-20 h-1 bg-blue-300 mx-auto rounded-full"></div>
          </div>

          <div class="border border-white/20 p-6 rounded-lg">
            <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
              <div class="group bg-white bg-opacity-20 hover:shadow-[0_8px_30px_rgb(0,0,0,0.12)] rounded-xl overflow-hidden border border-gray-100/20 transition-all duration-500">
                <div class="relative overflow-hidden">
                  <img src="assets/img/agate.webp" alt="news" class="w-full h-52 object-cover transform group-hover:scale-105 transition-all duration-700 ease-in-out" />
                  <div class="absolute inset-0 bg-gradient-to-t from-black/60 via-transparent to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-500"></div>
                </div>
                <div class="p-6">
                  <h3 class="text-lg font-semibold text-center text-white group-hover:text-sky-300 line-clamp-2 transition-colors duration-300">Jalinan kerjasama dengan PT Agate International.</h3>
                </div>
              </div>
              <div class="group bg-white bg-opacity-20 hover:shadow-[0_8px_30px_rgb(0,0,0,0.12)] rounded-xl overflow-hidden border border-gray-100/20 transition-all duration-500">
                <div class="relative overflow-hidden">
                  <img src="assets/img/lks otomotif.webp" alt="news" class="w-full h-52 object-cover transform group-hover:scale-105 transition-all duration-700 ease-in-out" />
                  <div class="absolute inset-0 bg-gradient-to-t from-black/60 via-transparent to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-500"></div>
                </div>
                <div class="p-6">
                  <h3 class="text-lg font-semibold text-center text-white group-hover:text-sky-300 line-clamp-2 transition-colors duration-300">Juara 1 LKS Otomotif Tingkat Kota Tasikmalaya</h3>
                </div>
              </div>
              <div class="group bg-white bg-opacity-20 hover:shadow-[0_8px_30px_rgb(0,0,0,0.12)] rounded-xl overflow-hidden border border-gray-100/20 transition-all duration-500">
                <div class="relative overflow-hidden">
                  <img src="assets/img/upacaraGuru.jpg" alt="news" class="w-full h-52 object-cover transform group-hover:scale-105 transition-all duration-700 ease-in-out" />
                  <div class="absolute inset-0 bg-gradient-to-t from-black/60 via-transparent to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-500"></div>
                </div>
                <div class="p-6">
                  <h3 class="text-lg font-semibold text-center text-white group-hover:text-sky-300 line-clamp-2 transition-colors duration-300">Upacara Peringatan Hari Guru dan Hut PGRI</h3>
                </div>
              </div>
            </div>
          </div>

          <div class="mt-12 text-center">
            <NuxtLink to="/berita" class="text-white font-semibold border border-sky-300 py-2 px-5 hover:px-6 rounded-full inline-flex items-center group transform hover:text-primary hover:-translate-y-1 duration-200">
              Lihat Semua Berita
              <svg class="w-4 h-4 ml-1 transform group-hover:translate-x-2 duration-200" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"></path>
              </svg>
            </NuxtLink>
          </div>
        </div>
      </section>
    </div>
    <!-- Galeri -->
    <div class="min-h-screen">
      <section class="py-16 px-4 bg-white">
        <div class="max-w-6xl mx-auto">
          <div class="text-center mb-12">
            <h2 class="text-3xl font-bold text-blue-700 mb-2">Galeri</h2>
            <div class="w-20 h-1 bg-sky-300 mx-auto rounded-full"></div>
          </div>

          <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
            <div class="group relative overflow-hidden rounded-lg shadow-md hover:shadow-xl transition-all duration-300">
              <img src="assets/img/Edu Fair SMKN 4 Tasikmalaya.jpg" alt="gambar" class="w-full h-64 object-cover transform group-hover:scale-105 transition-transform duration-300" />
            </div>

            <div class="group relative overflow-hidden rounded-lg shadow-md hover:shadow-xl transition-all duration-300">
              <img src="assets/img/Job Fair SMKN 4 Tasikmalaya.jpg" alt="gambar" class="w-full h-64 object-cover transform group-hover:scale-105 transition-transform duration-300" />
            </div>

            <div class="group relative overflow-hidden rounded-lg shadow-md hover:shadow-xl transition-all duration-300">
              <img src="assets/img/Hari Kemerdekaan 79.jpg" alt="gambar" class="w-full h-64 object-cover transform group-hover:scale-105 transition-transform duration-300" />
            </div>
          </div>
          <div class="mt-12 text-center">
            <NuxtLink to="/galeri" class="text-gray-800 font-semibold border border-sky-300 py-2 px-5 hover:px-6 rounded-full inline-flex items-center group transform hover:text-primary hover:-translate-y-1 duration-200">
              Lihat Semua Galeri
              <svg class="w-4 h-4 ml-1 transform group-hover:translate-x-2 duration-200" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"></path>
              </svg>
            </NuxtLink>
          </div>
        </div>
      </section>
    </div>
    <!-- kompetensi keahlian -->
    <Jurusan />
  </div>
</template>
