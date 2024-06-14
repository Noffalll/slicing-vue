<script setup></script>

<template>
  <!-- NAVBAR -->
  <nav class="navbar navbar-expand-lg">
    <div class="container-fluid">
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
        aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <img src="./assets/logo.awl.png" class="h-16" alt="HC Logo" width="70" height="70" />
      <a class="navbar-brand" href="#">Heart Healty</a>
      <div class="collapse navbar-collapse  d-flex justify-content-center" id="navbarNav">
        <a class="navbar-brand" href="#"></a>
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link" href="#1">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#2">About Us</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#3">Contact Us</a>
          </li>
        </ul>
      </div>
    </div>
    <form class="d-flex">
      <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
    </form>
  </nav>
  <!-- NAVBAR -->

  <!-- Hero banner Start -->
  <section id="home" class="p-20">
    <!-- Wrapper -->
    <div class="text-center">
      <br>
      <h3 class="font-bold  text-2xl mb-6">Selamat Datang di Mental Health, Tempat Berbagi dan Memahami Kesehatan
        Mental.</h3>
      <br>
      <br>
      <img src="./assets/dokter.jpeg" alt="" width="500px" height="350px">
    </div>
    <!-- wrwapper end -->
  </section>
  <br>
  <!-- Hero banner End -->

  <!-- Content Start 1 -->
  <section id="content" class="sm:pl-4 sm:pr-4 md:pl-8 md:pr-8 lg:pl-16 lg:pr-16 xl:pl-28 xl:pr-28">
    <p class="text-center text-sm sm:text-sm md:text-base lg:text-lg xl:text-xl">
      Selamat Datang di Mental Health, Tempat Berbagi dan Memahami Kesehatan Mental. Kesehatan mental adalah aspek
      penting dalam kesejahteraan kita sehari-hari. Kami di Mental Health berkomitmen untuk memberikan dukungan,
      informasi, dan inspirasi untuk memahami dan meningkatkan kesehatan mental Anda. Setiap orang memiliki perjalanan
      uniknya sendiri, dan di sini, kami ingin menciptakan ruang yang aman dan terbuka untuk berbicara tentang
      tantangan, kemenangan, dan pengalaman seputar kesehatan mental. Kami percaya bahwa dengan berbagi cerita,
      pengetahuan, dan sumber daya, kita dapat memperkuat satu sama lain. Jelajahi artikel, tips kesehatan mental, dan
      panduan praktis yang kami sediakan. Apakah Anda mencari dukungan pribadi, informasi terkini, atau sekadar ingin
      memahami lebih dalam tentang kesehatan mental, Anda berada di tempat yang tepat. Ingatlah bahwa perjalanan
      menuju kesehatan mental yang lebih baik adalah proses, dan Anda tidak sendirian. Kami bersama-sama membangun
      masyarakat yang peduli dan mendukung kesehatan mental. Mari kita bersama-sama menjadikan kesehatan mental sebagai
      prioritas dan membangun fondasi kebahagiaan yang kokoh. Terima kasih telah bergabung di Mental Health. Dengan
      kasih, Tim Mental Health
    </p>
  </section>
  <!-- Content End 1 -->

  <hr class="bg-black">

  <!-- Content Start 2 -->
  <section id="1" class="p-6 md:p-20 bg-gradient-to-r from-teal-300 via-blue-300 to-indigo-300">
    <h1 class="text-center font-bold text-2xl md:text-4xl pt-16">Mengenal Lebih Jauh Beberapa Kondisi Kesehatan Mental
    </h1>
    <p class="text-center p-4 md:p-16">Simak sejumlah istilah dan kondisi menyangkut kesehatan mental yang
      sering kita dengar, serta kiat agar kita dapat mendukung kesejahteraan keluarga.</p>
    <!-- DEPRESI -->
    <div class="container p-4">
      <div class="row">
        <div class="col-md-4 mb-4">
          <div class="card">
            <img src="./assets/depresi.jpeg" class="card-img-top" alt="Depresi" width="100px" height="350px">
            <div class="card-body">
              <h5 class="card-title">Apa itu depresi?</h5>
              <p class="card-text">Depresi atau gangguan adalah gangguan kesehatan mental yang memengaruhi perasaan,
                Gejala depresi pada seseorang yabg umum adalah merasa sedih,
              </p>
              <div class="d-flex justify-content-center">
                <a href="#" class="btn btn-success">Read More</a>
              </div>
            </div>
          </div>
        </div>
        <!-- CEMAS -->
        <div class="col-md-4 mb-4">
          <div class="card">
            <img src="/src/assets/cemas.jpeg" class="card-img-top" alt="cemas" width="100px" height="350px">
            <div class="card-body">
              <h5 class="card-title">Apa itu kecemasan?</h5>
              <p class="card-text">Cemas merupakan perasaan gugup atau gelisah. Kadang-kadang orang akan merasa cemas
                saat berhadapan dengan situasi tertentu</p>
              <div class="d-flex justify-content-center">
                <a href="#" class="btn btn-success">Read More</a>
              </div>
            </div>
          </div>
        </div>
        <!-- STRES -->
        <div class="col-md-4 mb-4">
          <div class="card">
            <img src="/src/assets/stres.jpeg" class="card-img-top" alt="stres" width="100px" height="350px">
            <div class="card-body">
              <h5 class="card-title">Apa itu stres?</h5>
              <p class="card-text">Stres adalah suatu hal yang tidak dapat terlepas dari kehidupan sehari-hari. Semua
                datangnya masalah dapat menimbulkan tekanan pada diri Anda</p>
              <div class="d-flex justify-content-center">
                <a href="#" class="btn btn-success">Read More</a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- Content End 2 -->
  <hr class="bg-black">

  <!-- Content Start 3 -->
  <section id="2" class="p-6 md:p-20 bg-gradient-to-r from-teal-300 via-blue-300 to-indigo-300">
    <h1 class="text-center font-bold text-2xl md:text-4xl pt-16">Tips menjaga kesehatan mental
    </h1>
    <p class="text-center p-4 md:p-16">Cari tahu bentuk dukungan yang tepat untuk kesehatan mental keluarga Anda.</p>
    <!-- berdiskusi tentang konflik dan perang dengan anak -->
    <div class="container p-4">
      <div class="row">
        <div class="col-md-4 mb-4">
          <div class="card">
            <img src="/src/assets/content31.jpeg" class="card-img-top" alt="berdiskusi tentang konflik" width="100px"
              height="350px">
            <div class="card-body">
              <h5 class="card-title">Berdiskusi Tentang Konflik Dan Perang Dengan Anak</h5>
              <p class="card-text">Ada beberapa cara yang bisa dilakukan oleh orang tua untuk berbicara tentang konflik
                dan perang dengan anak.
              </p>
              <div class="d-flex justify-content-center">
                <a href="#" class="btn btn-success">Read More</a>
              </div>
            </div>
          </div>
        </div>
        <!-- Kiat berkomunikasi dengan remaja -->
        <div class="col-md-4 mb-4">
          <div class="card">
            <img src="/src/assets/content32.jpeg" class="card-img-top" alt="Kiat berkomunikasi" width="100px"
              height="350px">
            <div class="card-body">
              <h5 class="card-title">Kiat berkomunikasi dengan remaja</h5>
              <p class="card-text">Membangun hubungan dengan remaja adalah modal penting bagi kesejahteraan mental serta
                pembelajaran sosial</p>
              <div class="d-flex justify-content-center">
                <a href="#" class="btn btn-success">Read More</a>
              </div>
            </div>
          </div>
        </div>
        <!-- Tips merawat diri untuk orang tua -->
        <div class="col-md-4 mb-4">
          <div class="card">
            <img src="/src/assets/content33.jpeg" class="card-img-top" alt="Tips merawat diri" width="100px"
              height="350px">
            <div class="card-body">
              <h5 class="card-title">Tips merawat diri untuk orang tua</h5>
              <p class="card-text">Merawat diri bisa dilakukan dengan membangun kebiasaan baru mungkin sulit, tetapi
                lama kelamaan membuat kita terbiasa.
              </p>
              <div class="d-flex justify-content-center">
                <a href="#" class="btn btn-success">Read More</a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- Content End 3 -->
  <hr class="bg-black">

  <!-- Content Start 4 -->
  <section id="cerita" class="p-6 md:p-20 bg-gradient-to-r from-teal-300 via-blue-300 to-indigo-300">
    <h1 class="text-center font-bold text-2xl md:text-4xl pt-16">Cerita
    </h1>
    <p class="text-center p-4 md:p-16">Cari tahu bentuk dukungan yang tepat untuk kesehatan mental keluarga Anda.</p>
    <!-- Caraku mengatasi kesehatan mental -->
    <div class="container p-4">
      <div class="row">
        <div class="col-md-4 mb-4">
          <div class="card">
            <img src="./assets/cerita1.jpeg" class="card-img-top" alt="Depresi" width="100px" height="350px">
            <div class="card-body">
              <h5 class="card-title">Caraku mengatasi kesehatan mental</h5>
              <p class="card-text">Pada awal memasuki sekolah smk, saya semakin susah untuk bergaul bersama siswa siswa
                yang lain. Setelah saya mencari informasi lebih lanjut, ternyata hal yang saya alami adalah gejala pada
                remaja yang terkena gangguan mental.
              </p>
              <div class="d-flex justify-content-center">
                <a href="#" class="btn btn-success">Read More</a>
              </div>
            </div>
          </div>
        </div>
        <!-- Dukunganku -->
        <div class="col-md-4 mb-4">
          <div class="card">
            <img src="./assets/cerita2.jpeg" class="card-img-top" alt="cemas" width="100px" height="350px">
            <div class="card-body">
              <h5 class="card-title">Dukunganku</h5>
              <p class="card-text">Menurutku, keluarga dan sekolah adalah pemeran penting untuk melindungi kesehatan
                mental para remaja. Disaat aku mengalami tekanan mental, orang tuaku selalu menjadi pendengar yang baik.
                Orang tuaku selalu mendukungku untuk tetap semangat menjalani hidup.</p>
              <div class="d-flex justify-content-center">
                <a href="#" class="btn btn-success">Read More</a>
              </div>
            </div>
          </div>
        </div>
        <!-- Yang Saya Rasakan (Kesehatan Mental) -->
        <div class="col-md-4 mb-4">
          <div class="card">
            <img src="./assets/cerita3.jpeg" class="card-img-top" alt="stres" width="100px" height="350px">
            <div class="card-body">
              <h5 class="card-title">Yang Saya Rasakan (Kesehatan Mental)</h5>
              <p class="card-text">Yang saya rasakan saat saya mengalami kesahatan mental pada usia remaja, saya merasa
                kehidupan saya tidak ada artinya, saya merasa putus asa.Setiap malam saya mendengar suara yang membisiki
                telinga saya untuk melakukan hal buruk.
              </p>
              <div class="d-flex justify-content-center">
                <a href="#" class="btn btn-success">Read More</a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- Content End 4 -->

  <hr class="bg-black">
  <!-- Berita Start -->
  <div class="text-center font-bold text-2xl md:text-4xl pt-16 pb-10">
    <h1>Dokter Kami</h1>
  </div>
  <section id="3">
    <!-- dokter 1 -->
    <div class="container p-4">
      <div class="row">
        <div class="col-md-4 mb-4">
          <div class="card">
            <img src="/src/assets/dokter1.jpeg" class="card-img-top" alt="dokter1" width="100px" height="350px">
            <div class="card-body">
              <h5 class="card-title">Christina Tedja, S.Psi., M.Psi. Psikolog</h5>
              <!-- gradu -->
              <div class="d-flex items-start gap-2">
                <svg xmlns="http://www.w3.org/2000/svg" width="19" height="19" fill="currentColor"
                  class="bi bi-mortarboard" viewBox="0 0 16 16">
                  <path
                    d="M8.211 2.047a.5.5 0 0 0-.422 0l-7.5 3.5a.5.5 0 0 0 .025.917l7.5 3a.5.5 0 0 0 .372 0L14 7.14V13a1 1 0 0 0-1 1v2h3v-2a1 1 0 0 0-1-1V6.739l.686-.275a.5.5 0 0 0 .025-.917zM8 8.46 1.758 5.965 8 3.052l6.242 2.913z" />
                  <path
                    d="M4.176 9.032a.5.5 0 0 0-.656.327l-.5 1.7a.5.5 0 0 0 .294.605l4.5 1.8a.5.5 0 0 0 .372 0l4.5-1.8a.5.5 0 0 0 .294-.605l-.5-1.7a.5.5 0 0 0-.656-.327L8 10.466zm-.068 1.873.22-.748 3.496 1.311a.5.5 0 0 0 .352 0l3.496-1.311.22.748L8 12.46z" />
                </svg>
                <p class="pl-3">Universitas Brawijaya, 2010</p>
              </div>
              <!-- lokasi -->
              <div class="d-flex items-start gap-2">
                <svg xmlns="http://www.w3.org/2000/svg" width="19" height="19" fill="currentColor" class="bi bi-geo-alt"
                  viewBox="0 0 16 16">
                  <path
                    d="M12.166 8.94c-.524 1.062-1.234 2.12-1.96 3.07A32 32 0 0 1 8 14.58a32 32 0 0 1-2.206-2.57c-.726-.95-1.436-2.008-1.96-3.07C3.304 7.867 3 6.862 3 6a5 5 0 0 1 10 0c0 .862-.305 1.867-.834 2.94M8 16s6-5.686 6-10A6 6 0 0 0 2 6c0 4.314 6 10 6 10" />
                  <path d="M8 8a2 2 0 1 1 0-4 2 2 0 0 1 0 4m0 1a3 3 0 1 0 0-6 3 3 0 0 0 0 6" />
                </svg>
                <p class="pl-3">Lokasi Praktik Di Malang</p>
              </div>
              <!-- tempat -->
              <div class="d-flex items-start gap-2">
                <svg xmlns="http://www.w3.org/2000/svg" width="19" height="19" fill="currentColor"
                  class="bi bi-hospital" viewBox="0 0 16 16">
                  <path
                    d="M8.5 5.034v1.1l.953-.55.5.867L9 7l.953.55-.5.866-.953-.55v1.1h-1v-1.1l-.953.55-.5-.866L7 7l-.953-.55.5-.866.953.55v-1.1zM13.25 9a.25.25 0 0 0-.25.25v.5c0 .138.112.25.25.25h.5a.25.25 0 0 0 .25-.25v-.5a.25.25 0 0 0-.25-.25zM13 11.25a.25.25 0 0 1 .25-.25h.5a.25.25 0 0 1 .25.25v.5a.25.25 0 0 1-.25.25h-.5a.25.25 0 0 1-.25-.25zm.25 1.75a.25.25 0 0 0-.25.25v.5c0 .138.112.25.25.25h.5a.25.25 0 0 0 .25-.25v-.5a.25.25 0 0 0-.25-.25zm-11-4a.25.25 0 0 0-.25.25v.5c0 .138.112.25.25.25h.5A.25.25 0 0 0 3 9.75v-.5A.25.25 0 0 0 2.75 9zm0 2a.25.25 0 0 0-.25.25v.5c0 .138.112.25.25.25h.5a.25.25 0 0 0 .25-.25v-.5a.25.25 0 0 0-.25-.25zM2 13.25a.25.25 0 0 1 .25-.25h.5a.25.25 0 0 1 .25.25v.5a.25.25 0 0 1-.25.25h-.5a.25.25 0 0 1-.25-.25z" />
                  <path
                    d="M5 1a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v1a1 1 0 0 1 1 1v4h3a1 1 0 0 1 1 1v7a1 1 0 0 1-1 1H1a1 1 0 0 1-1-1V8a1 1 0 0 1 1-1h3V3a1 1 0 0 1 1-1zm2 14h2v-3H7zm3 0h1V3H5v12h1v-3a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1zm0-14H6v1h4zm2 7v7h3V8zm-8 7V8H1v7z" />
                </svg>
                <p class="pl-3">RSU Dr Saiful Anwar</p>
              </div>
            </div>
          </div>
        </div>
        <!-- end dokter 1 -->
        <!-- dokter 2 -->
        <div class="col-md-4 mb-4">
          <div class="card">
            <img src="/src/assets/dokter2.jpeg" class="card-img-top" alt="dokter1" width="100px" height="350px">
            <div class="card-body">
              <h5 class="card-title">dr. Anastasia Vanny Launardo, M.Kes., Sp.M
                Sp. Mata</h5>
              <!-- gradu -->
              <div class="d-flex items-start gap-2">
                <svg xmlns="http://www.w3.org/2000/svg" width="19" height="19" fill="currentColor"
                  class="bi bi-mortarboard" viewBox="0 0 16 16">
                  <path
                    d="M8.211 2.047a.5.5 0 0 0-.422 0l-7.5 3.5a.5.5 0 0 0 .025.917l7.5 3a.5.5 0 0 0 .372 0L14 7.14V13a1 1 0 0 0-1 1v2h3v-2a1 1 0 0 0-1-1V6.739l.686-.275a.5.5 0 0 0 .025-.917zM8 8.46 1.758 5.965 8 3.052l6.242 2.913z" />
                  <path
                    d="M4.176 9.032a.5.5 0 0 0-.656.327l-.5 1.7a.5.5 0 0 0 .294.605l4.5 1.8a.5.5 0 0 0 .372 0l4.5-1.8a.5.5 0 0 0 .294-.605l-.5-1.7a.5.5 0 0 0-.656-.327L8 10.466zm-.068 1.873.22-.748 3.496 1.311a.5.5 0 0 0 .352 0l3.496-1.311.22.748L8 12.46z" />
                </svg>
                <p class="pl-3">Universitas Brawijaya, 2013</p>
              </div>
              <!-- lokasi -->
              <div class="d-flex items-start gap-2">
                <svg xmlns="http://www.w3.org/2000/svg" width="19" height="19" fill="currentColor" class="bi bi-geo-alt"
                  viewBox="0 0 16 16">
                  <path
                    d="M12.166 8.94c-.524 1.062-1.234 2.12-1.96 3.07A32 32 0 0 1 8 14.58a32 32 0 0 1-2.206-2.57c-.726-.95-1.436-2.008-1.96-3.07C3.304 7.867 3 6.862 3 6a5 5 0 0 1 10 0c0 .862-.305 1.867-.834 2.94M8 16s6-5.686 6-10A6 6 0 0 0 2 6c0 4.314 6 10 6 10" />
                  <path d="M8 8a2 2 0 1 1 0-4 2 2 0 0 1 0 4m0 1a3 3 0 1 0 0-6 3 3 0 0 0 0 6" />
                </svg>
                <p class="pl-3">Lokasi Praktik Di Malang</p>
              </div>
              <!-- tempat -->
              <div class="d-flex items-start gap-2">
                <svg xmlns="http://www.w3.org/2000/svg" width="19" height="19" fill="currentColor"
                  class="bi bi-hospital" viewBox="0 0 16 16">
                  <path
                    d="M8.5 5.034v1.1l.953-.55.5.867L9 7l.953.55-.5.866-.953-.55v1.1h-1v-1.1l-.953.55-.5-.866L7 7l-.953-.55.5-.866.953.55v-1.1zM13.25 9a.25.25 0 0 0-.25.25v.5c0 .138.112.25.25.25h.5a.25.25 0 0 0 .25-.25v-.5a.25.25 0 0 0-.25-.25zM13 11.25a.25.25 0 0 1 .25-.25h.5a.25.25 0 0 1 .25.25v.5a.25.25 0 0 1-.25.25h-.5a.25.25 0 0 1-.25-.25zm.25 1.75a.25.25 0 0 0-.25.25v.5c0 .138.112.25.25.25h.5a.25.25 0 0 0 .25-.25v-.5a.25.25 0 0 0-.25-.25zm-11-4a.25.25 0 0 0-.25.25v.5c0 .138.112.25.25.25h.5A.25.25 0 0 0 3 9.75v-.5A.25.25 0 0 0 2.75 9zm0 2a.25.25 0 0 0-.25.25v.5c0 .138.112.25.25.25h.5a.25.25 0 0 0 .25-.25v-.5a.25.25 0 0 0-.25-.25zM2 13.25a.25.25 0 0 1 .25-.25h.5a.25.25 0 0 1 .25.25v.5a.25.25 0 0 1-.25.25h-.5a.25.25 0 0 1-.25-.25z" />
                  <path
                    d="M5 1a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v1a1 1 0 0 1 1 1v4h3a1 1 0 0 1 1 1v7a1 1 0 0 1-1 1H1a1 1 0 0 1-1-1V8a1 1 0 0 1 1-1h3V3a1 1 0 0 1 1-1zm2 14h2v-3H7zm3 0h1V3H5v12h1v-3a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1zm0-14H6v1h4zm2 7v7h3V8zm-8 7V8H1v7z" />
                </svg>
                <p class="pl-3">RS Soepraoen</p>
              </div>
            </div>
          </div>
        </div>
        <!-- end dokter 2 -->

        <!-- dokter 3 -->
        <div class="col-md-4 mb-4">
          <div class="card">
            <img src="/src/assets/dokter3.jpeg" class="card-img-top" alt="dokter1" width="100px" height="350px">
            <div class="card-body">
              <h5 class="card-title">drg. Aya Sophia, Sp. KGA
                Sp. Gigi Anak</h5>
              <!-- gradu -->
              <div class="d-flex items-start gap-2">
                <svg xmlns="http://www.w3.org/2000/svg" width="19" height="19" fill="currentColor"
                  class="bi bi-mortarboard" viewBox="0 0 16 16">
                  <path
                    d="M8.211 2.047a.5.5 0 0 0-.422 0l-7.5 3.5a.5.5 0 0 0 .025.917l7.5 3a.5.5 0 0 0 .372 0L14 7.14V13a1 1 0 0 0-1 1v2h3v-2a1 1 0 0 0-1-1V6.739l.686-.275a.5.5 0 0 0 .025-.917zM8 8.46 1.758 5.965 8 3.052l6.242 2.913z" />
                  <path
                    d="M4.176 9.032a.5.5 0 0 0-.656.327l-.5 1.7a.5.5 0 0 0 .294.605l4.5 1.8a.5.5 0 0 0 .372 0l4.5-1.8a.5.5 0 0 0 .294-.605l-.5-1.7a.5.5 0 0 0-.656-.327L8 10.466zm-.068 1.873.22-.748 3.496 1.311a.5.5 0 0 0 .352 0l3.496-1.311.22.748L8 12.46z" />
                </svg>
                <p class="pl-3">Universitas Brawijaya, 2008</p>
              </div>
              <!-- lokasi -->
              <div class="d-flex items-start gap-2">
                <svg xmlns="http://www.w3.org/2000/svg" width="19" height="19" fill="currentColor" class="bi bi-geo-alt"
                  viewBox="0 0 16 16">
                  <path
                    d="M12.166 8.94c-.524 1.062-1.234 2.12-1.96 3.07A32 32 0 0 1 8 14.58a32 32 0 0 1-2.206-2.57c-.726-.95-1.436-2.008-1.96-3.07C3.304 7.867 3 6.862 3 6a5 5 0 0 1 10 0c0 .862-.305 1.867-.834 2.94M8 16s6-5.686 6-10A6 6 0 0 0 2 6c0 4.314 6 10 6 10" />
                  <path d="M8 8a2 2 0 1 1 0-4 2 2 0 0 1 0 4m0 1a3 3 0 1 0 0-6 3 3 0 0 0 0 6" />
                </svg>
                <p class="pl-3">Lokasi Praktik Di Malang</p>
              </div>
              <!-- tempat -->
              <div class="d-flex items-start gap-2">
                <svg xmlns="http://www.w3.org/2000/svg" width="19" height="19" fill="currentColor"
                  class="bi bi-hospital" viewBox="0 0 16 16">
                  <path
                    d="M8.5 5.034v1.1l.953-.55.5.867L9 7l.953.55-.5.866-.953-.55v1.1h-1v-1.1l-.953.55-.5-.866L7 7l-.953-.55.5-.866.953.55v-1.1zM13.25 9a.25.25 0 0 0-.25.25v.5c0 .138.112.25.25.25h.5a.25.25 0 0 0 .25-.25v-.5a.25.25 0 0 0-.25-.25zM13 11.25a.25.25 0 0 1 .25-.25h.5a.25.25 0 0 1 .25.25v.5a.25.25 0 0 1-.25.25h-.5a.25.25 0 0 1-.25-.25zm.25 1.75a.25.25 0 0 0-.25.25v.5c0 .138.112.25.25.25h.5a.25.25 0 0 0 .25-.25v-.5a.25.25 0 0 0-.25-.25zm-11-4a.25.25 0 0 0-.25.25v.5c0 .138.112.25.25.25h.5A.25.25 0 0 0 3 9.75v-.5A.25.25 0 0 0 2.75 9zm0 2a.25.25 0 0 0-.25.25v.5c0 .138.112.25.25.25h.5a.25.25 0 0 0 .25-.25v-.5a.25.25 0 0 0-.25-.25zM2 13.25a.25.25 0 0 1 .25-.25h.5a.25.25 0 0 1 .25.25v.5a.25.25 0 0 1-.25.25h-.5a.25.25 0 0 1-.25-.25z" />
                  <path
                    d="M5 1a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v1a1 1 0 0 1 1 1v4h3a1 1 0 0 1 1 1v7a1 1 0 0 1-1 1H1a1 1 0 0 1-1-1V8a1 1 0 0 1 1-1h3V3a1 1 0 0 1 1-1zm2 14h2v-3H7zm3 0h1V3H5v12h1v-3a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1zm0-14H6v1h4zm2 7v7h3V8zm-8 7V8H1v7z" />
                </svg>
                <p class="pl-3">RS Islam Malang</p>
              </div>
            </div>
          </div>
        </div>
        <!-- end dokter 3 -->
      </div>
    </div>

    <!-- dokter 4 -->
    <div class="d-flex justify-content-center">
      <div class="card">
        <img src="/src/assets/dokter4.jpeg" class="card-img-top" alt="dokter1" width="100px" height="250px">
        <div class="card-body">
          <h5 class="card-title">dr. Cahyani Gita Ambarsari Sp .A (K)
          </h5>
          <!-- gradu -->
          <div class="d-flex items-start gap-2">
            <svg xmlns="http://www.w3.org/2000/svg" width="19" height="19" fill="currentColor" class="bi bi-mortarboard"
              viewBox="0 0 16 16">
              <path
                d="M8.211 2.047a.5.5 0 0 0-.422 0l-7.5 3.5a.5.5 0 0 0 .025.917l7.5 3a.5.5 0 0 0 .372 0L14 7.14V13a1 1 0 0 0-1 1v2h3v-2a1 1 0 0 0-1-1V6.739l.686-.275a.5.5 0 0 0 .025-.917zM8 8.46 1.758 5.965 8 3.052l6.242 2.913z" />
              <path
                d="M4.176 9.032a.5.5 0 0 0-.656.327l-.5 1.7a.5.5 0 0 0 .294.605l4.5 1.8a.5.5 0 0 0 .372 0l4.5-1.8a.5.5 0 0 0 .294-.605l-.5-1.7a.5.5 0 0 0-.656-.327L8 10.466zm-.068 1.873.22-.748 3.496 1.311a.5.5 0 0 0 .352 0l3.496-1.311.22.748L8 12.46z" />
            </svg>
            <p class="pl-3">Universitas Brawijaya, 2014</p>
          </div>
          <!-- lokasi -->
          <div class="d-flex items-start gap-2">
            <svg xmlns="http://www.w3.org/2000/svg" width="19" height="19" fill="currentColor" class="bi bi-geo-alt"
              viewBox="0 0 16 16">
              <path
                d="M12.166 8.94c-.524 1.062-1.234 2.12-1.96 3.07A32 32 0 0 1 8 14.58a32 32 0 0 1-2.206-2.57c-.726-.95-1.436-2.008-1.96-3.07C3.304 7.867 3 6.862 3 6a5 5 0 0 1 10 0c0 .862-.305 1.867-.834 2.94M8 16s6-5.686 6-10A6 6 0 0 0 2 6c0 4.314 6 10 6 10" />
              <path d="M8 8a2 2 0 1 1 0-4 2 2 0 0 1 0 4m0 1a3 3 0 1 0 0-6 3 3 0 0 0 0 6" />
            </svg>
            <p class="pl-3">Lokasi Praktik Di Malang</p>
          </div>
          <!-- tempat -->
          <div class="d-flex items-start gap-2">
            <svg xmlns="http://www.w3.org/2000/svg" width="19" height="19" fill="currentColor" class="bi bi-hospital"
              viewBox="0 0 16 16">
              <path
                d="M8.5 5.034v1.1l.953-.55.5.867L9 7l.953.55-.5.866-.953-.55v1.1h-1v-1.1l-.953.55-.5-.866L7 7l-.953-.55.5-.866.953.55v-1.1zM13.25 9a.25.25 0 0 0-.25.25v.5c0 .138.112.25.25.25h.5a.25.25 0 0 0 .25-.25v-.5a.25.25 0 0 0-.25-.25zM13 11.25a.25.25 0 0 1 .25-.25h.5a.25.25 0 0 1 .25.25v.5a.25.25 0 0 1-.25.25h-.5a.25.25 0 0 1-.25-.25zm.25 1.75a.25.25 0 0 0-.25.25v.5c0 .138.112.25.25.25h.5a.25.25 0 0 0 .25-.25v-.5a.25.25 0 0 0-.25-.25zm-11-4a.25.25 0 0 0-.25.25v.5c0 .138.112.25.25.25h.5A.25.25 0 0 0 3 9.75v-.5A.25.25 0 0 0 2.75 9zm0 2a.25.25 0 0 0-.25.25v.5c0 .138.112.25.25.25h.5a.25.25 0 0 0 .25-.25v-.5a.25.25 0 0 0-.25-.25zM2 13.25a.25.25 0 0 1 .25-.25h.5a.25.25 0 0 1 .25.25v.5a.25.25 0 0 1-.25.25h-.5a.25.25 0 0 1-.25-.25z" />
              <path
                d="M5 1a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v1a1 1 0 0 1 1 1v4h3a1 1 0 0 1 1 1v7a1 1 0 0 1-1 1H1a1 1 0 0 1-1-1V8a1 1 0 0 1 1-1h3V3a1 1 0 0 1 1-1zm2 14h2v-3H7zm3 0h1V3H5v12h1v-3a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1zm0-14H6v1h4zm2 7v7h3V8zm-8 7V8H1v7z" />
            </svg>
            <p class="pl-3">RS Lanuma Abdul Saleh</p>
          </div>
        </div>
      </div>
    </div>
    <!-- end dokter 4 -->
  </section>
  <!-- Berita End -->

  <!-- Footer -->
  <footer class="bg-dark text-white pt-4">
    <div class="container">
      <div class="row">
        <!-- About Column -->
        <div class=" d-flex col-md-4">
          <img src="/src/assets/logo.awl.png" alt="logo-footers" width="100px" height="100px">
          <h3 class="pl-3">Mental Health</h3>
        </div>
        <!-- Links Column -->
        <div class="col-md-4">
          <h5>Click Here</h5>
          <ul class="list-unstyled">
            <li><a href="#1" class="text-white">Home</a></li>
            <li><a href="#2" class="text-white">About</a></li>
            <li><a href="#3" class="text-white">Services</a></li>
          </ul>
        </div>
        <!-- Contact Column -->
        <div class="col-md-4">
          <h5>Contact Us</h5>
          <address>
            Malang<br>
            Jawa Jimur , IND<br>
            <a href="mailto:info@example.com" class="text-white">info@dokter</a><br>
          </address>
        </div>
      </div>
      <div class="row mt-3">
        <div class="col-md-12 text-center">
          <p class="mb-0">&copy; NPALL.4uu</p>
        </div>
      </div>
    </div>
  </footer>
</template>

<style scoped>
.navbar {
  top: 0;
  left: 0;
  width: 100%;
  z-index: 1000;
}

.navbar-brand {
  color: green;
}

.collapse {
  background-color: green;
}

.container {
  margin-top: 50px;

}
</style>
