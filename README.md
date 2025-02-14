<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Happy Valentine - Ucapan Romantis</title>
  <style>
    /* Gaya umum */
    body, html {
      margin: 0;
      padding: 0;
      height: 100%;
      font-family: 'Arial', sans-serif;
      background: #fff0f6;
      color: #333;
      overflow: hidden;
    }
    /* Container slide */
    #slide-container {
      width: 100%;
      height: 100%;
      position: relative;
    }
    .slide {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      display: none;
      padding: 20px;
      box-sizing: border-box;
      overflow-y: auto;
    }
    .slide.active {
      display: block;
      animation: fadeIn 0.8s;
    }
    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }
    /* Konten slide */
    .content {
      max-width: 800px;
      margin: 50px auto;
      background: rgba(255,255,255,0.8);
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
      text-align: center;
    }
    h1 {
      margin-bottom: 20px;
      font-size: 2em;
      color: #d6336c;
    }
    p {
      line-height: 1.6;
      white-space: pre-line;
      text-align: left;
    }
    button {
      margin-top: 20px;
      padding: 10px 20px;
      background: #d6336c;
      color: #fff;
      border: none;
      border-radius: 5px;
      font-size: 1em;
      cursor: pointer;
      transition: background 0.3s;
    }
    button:hover {
      background: #c12a5a;
    }
    /* Gaya untuk slide ketiga (kotak kata) */
    .boxes {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 15px;
      margin-top: 20px;
    }
    .box {
      background: #ffe0ec;
      border: 1px solid #f8b6c4;
      border-radius: 8px;
      padding: 15px;
      font-size: 0.95em;
      text-align: center;
    }
    /* Sembunyikan iframe YouTube agar tidak tampil */
    #bg-music {
      display: none;
    }
  </style>
</head>
<body>

  <!-- YouTube iframe sebagai background music -->
  <iframe
    id="bg-music"
    src="https://www.youtube.com/embed/q6on6wvbvwk?autoplay=1&loop=1&playlist=q6on6wvbvwk&controls=0&showinfo=0"
    frameborder="0"
    allow="autoplay; encrypted-media"
    allowfullscreen>
  </iframe>

  <!-- Container slide -->
  <div id="slide-container">
    <!-- Slide 1 -->
    <section id="slide1" class="slide active">
      <div class="content">
        <h1>Semestaku</h1>
        <p>
Di tengah malam yang sunyi, kau bisikkan rindu,<br>
“Sayang banget mbe kamu,” begitu katamu.<br>
Aku tersenyum di balik layar, merasakan hangat,<br>
Seperti pelukan yang tak terlihat, tapi erat.<br><br>

Kau pinta satu hal dengan lirih,<br>
“Jangan selingkuh,” pintamu gigih.<br>
Aku tahu, hatimu rapuh oleh cemburu,<br>
Aku pun sama, takut kehilanganmu.<br><br>

Kita berjanji dalam sunyi,<br>
Tak ada yang lain, hanya kau dan aku di sini.<br>
Karena cinta bukan sekadar kata,<br>
Tapi janji yang kita jaga selamanya.<br><br>

“Selamat bobo, semestaku,” katamu lembut,<br>
Dan aku tersenyum, hangat, tak ada yang luput.<br>
Sebab semestaku adalah kamu,<br>
Dan cintaku akan selalu utuh untukmu.<br>
madiun, 6 Feb 2025
        </p>
        <button onclick="showSlide(2)">Next</button>
      </div>
    </section>

    <!-- Slide 2 -->
    <section id="slide2" class="slide">
      <div class="content">
        <h1>Boleh, Sayang</h1>
        <p>
Boleh, sayang, jangan kau tahan,<br>
rindu tak perlu disimpan sendirian.<br>
Biarkan mengalir, seperti biasa,<br>
seperti dulu, tanpa luka.<br><br>

Boleh, sayang, tanyakan semua,<br>
aku di sini, mendengar dengan setia.<br>
Tak perlu berpura menepis rasa,<br>
karena aku pun selalu kangen ke kamu.<br><br>

Boleh, sayang, jangan kau lelah,<br>
cintaku tak akan berubah arah.<br>
Jika hatimu ingin kembali seperti dulu,<br>
maka peluklah aku, tanpa ragu.<br><br>

Boleh, sayang, selalu boleh,<br>
cinta kita tak perlu diseleksi.<br>
Jadilah dirimu, tanpa beban,<br>
karena aku mencintaimu, tanpa syarat dan alasan.<br>
Madiun, 10 feb 2025
        </p>
        <button onclick="showSlide(3)">Next</button>
      </div>
    </section>

    <!-- Slide 3 -->
    <section id="slide3" class="slide">
      <div class="content">
        <h1>Pesan Untukmu</h1>
        <div class="boxes">
          <div class="box">Gimana? kalo ini udah kamu buka, berarti kamu udah janji ngga ilfeel sama aku kan wkwkwk</div>
          <div class="box">Semangat kerjanya yaaa.... i love you syg</div>
          <div class="box">fun fact!! aku buat ini pas kita marahan lohh</div>
          <div class="box">kalo kamu bisa ngeh, musik yang kamu dengar sekarang pasti yang kamu nyanyiin baru-baru ini pas kita ketemu</div>
          <div class="box">kalo kita ga bisa ketemu di hari jumat berarti kita ketemu di hari minggu, jadi jngn salahkan aku yaa kalo aku ngasih ini telat</div>
          <div class="box">gimana keadaanmu sekarang?</div>
          <div class="box">aku takut kenapa-napa, aku khawatir sama kamu?</div>
          <div class="box">mungkin aku gabisa jaga kamu kayak dulu, tapi aku minta tolong banget jaga diri baik baik</div>
          <div class="box">kamu harus bisa tanggung jawab sama diri kamu sendiri yaaa</div>
        </div>
      </div>
    </section>
  </div>

  <script>
    // Fungsi untuk berpindah slide
    function showSlide(n) {
      var slides = document.getElementsByClassName('slide');
      for (var i = 0; i < slides.length; i++) {
        slides[i].classList.remove('active');
      }
      var nextSlide = document.getElementById('slide' + n);
      if (nextSlide) {
        nextSlide.classList.add('active');
      }
    }
  </script>
</body>
</html>
