# source code
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Joupit</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
      /* Custom styles for navigation */
      .nav-link {
        padding: 0.5rem 1rem;
        border-radius: 0.375rem;
        transition: background-color 0.3s, color 0.3s;
      }

      .nav-link:hover {
        background-color: #1d4ed8; /* Tailwind's blue-800 color */
        color: white;
      }

      html {
        scroll-behavior: smooth; /* Smooth scrolling between sections */
      }

      /* Mobile menu styling */
      .mobile-menu {
        display: none;
      }

      .mobile-menu.active {
        display: block;
      }
    </style>
  </head>
  <body class="bg-gray-100">
    <header class="bg-white shadow">
      <div
        class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-4 flex justify-between items-center"
      >
        <div class="text-xl font-bold text-blue-800">
          <img src="img/logo.png" alt="Logo" class="h-8 inline-block mr-2" />
          Joupit
        </div>
        <nav class="hidden lg:flex space-x-4 text-gray-600">
          <a href="#Sekilas Toko" class="nav-link hover:text-blue-500"
            >Sekilas Toko</a
          >
          <a href="#Produk" class="nav-link hover:text-blue-500">Produk</a>
          <a href="#Layanan" class="nav-link hover:text-blue-500">Layanan</a>
          <a href="#Tentang Kami" class="nav-link hover:text-blue-500"
            >Tentang Kami</a
          >
        </nav>
        <button class="lg:hidden text-gray-600" onclick="toggleMenu()">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="h-6 w-6"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M4 6h16M4 12h16m-7 6h7"
            />
          </svg>
        </button>
      </div>

      <!-- Mobile Menu -->
      <div
        id="mobile-menu"
        class="mobile-menu bg-white shadow-lg p-4 lg:hidden"
      >
        <a
          href="#Sekilas Toko"
          class="block nav-link hover:text-blue-500"
          onclick="toggleMenu()"
        >
          Sekilas Toko
        </a>
        <a
          href="#Produk"
          class="block nav-link hover:text-blue-500"
          onclick="toggleMenu()"
        >
          Produk
        </a>
        <a
          href="#Layanan"
          class="block nav-link hover:text-blue-500"
          onclick="toggleMenu()"
        >
          Layanan
        </a>
        <a
          href="#Layanan"
          class="block nav-link hover:text-blue-500"
          onclick="toggleMenu()"
        >
          Tentang Kami
        </a>
        <a
          href="https://wa.me/+6289665763920"
          target="_blank"
          class="block nav-link bg-green-500 text-white mt-4 hover:bg-green-600"
        >
          Klik Disini Untuk Pemesanan
        </a>
      </div>
    </header>

    <!-- Home Section -->
    <section id="Sekilas Toko" class="bg-white py-16">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="text-center">
          <h2 class="text-4xl font-extrabold text-blue-800">
            Selamat Datang di Joupit
          </h2>
          <p class="mt-4 text-gray-500">
            Toko outpit dengan rating terbaik di masa kini dan terpercaya.
            Tujuan kami adalah untuk menunjang para generasi milenial agar
            tampil lebih kece dan menarik. Telah melayani 100000+ order baik
            online maupun offline. Temukan apa yang kami tawarkan untuk Gen Z.
          </p>
        </div>
      </div>
    </section>

    <!-- Product Section -->
    <section id="Produk" class="bg-gray-50 py-16">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <h2 class="text-3xl font-bold text-blue-800 text-center">
          Produk Tersedia
        </h2>
        <p class="mt-4 text-gray-500 text-center">Sepatu Casual</p>
        <div class="mt-8 grid gap-8 grid-cols-1 sm:grid-cols-2 lg:grid-cols-3">
          <!-- Product 1 -->
          <div class="bg-white shadow-lg rounded-lg p-4">
            <img
              src="img/product 1ganti.jpg"
              alt="Product 1"
              class="w-full h-wha48 object-cover rounded-t-lg"
            />
            <h3 class="mt-4 text-xl font-bold text-blue-800">
              Adidas Samba Series
            </h3>
            <p class="mt-2 text-gray-500">
              Sepatu adidas Samba ini memiliki estetika dekonstruksi tanpa
              kehilangan ritme dalam style. Sepatu ini merefleksikan warisan
              yang kaya dengan desain sepanjang masa. Dari kaki atlet sepak bola
              hingga panggung mode high-fashion, sepatu adidas Samba merupakan
              bentuk ekspresi diri dan style kasual. Adidas ini cocok digunakan
              pada saat berolahraga,coffe shop dan santai. Biasanya sering
              digunakan dikalangan remaja hingga orang tua sekalipun.
            </p>
            <a
              href="https://wa.me/+6289665763920"
              target="_blank"
              class="mt-4 w-full bg-blue-800 text-white py-2 rounded-lg hover:bg-blue-600 text-center inline-block"
            >
              Klik Beli Disini
            </a>
          </div>

          <!-- Product 2 -->
          <div class="bg-white shadow-lg rounded-lg p-4">
            <img
              src="img/foto2ganti.jpg"
              alt="Product 2"
              class="w-full h-48 object-cover rounded-t-lg"
            />
            <h3 class="mt-4 text-xl font-bold text-blue-800">
              Adidas Spezial Series
            </h3>
            <p class="mt-2 text-gray-500">
              Salah satu Produk Adidas yang paling terkenal adalah sepatu,
              contohnya adalah Adidas Spezial yang kini banyak sekali digemari
              oleh orang orang dari anak anak, dewasa hingga orang tua karena
              desain yang klasik menjadi salah satu alasan mengapa sepatu ini
              digemari lintas generasi. Produk ini terinspirasi oleh sejarah dan
              budaya olahraga, musik, dan pastinya fashion yang dijadikan
              sepasang sepatu yang klasik dan berkualitas.
            </p>
            <a
              href="https://wa.me/+6289665763920"
              target="_blank"
              class="mt-4 w-full bg-blue-800 text-white py-2 rounded-lg hover:bg-blue-600 text-center inline-block"
            >
              Klik Beli Disini
            </a>
          </div>

          <!-- Product 3 -->
          <div class="bg-white shadow-lg rounded-lg p-4">
            <img
              src="img/foto3ganti.jpg"
              alt="Product 3"
              class="w-full h-48 object-cover rounded-t-lg"
            />
            <h3 class="mt-4 text-xl font-bold text-blue-800">
              Adidas Liverpool Series
            </h3>
            <p class="mt-2 text-gray-500">
              Sepatu Adidas Liverpool adalah kolaborasi antara Adidas dan
              Liverpool FC, menampilkan warna khas klub seperti merah, hitam,
              dan putih. Didesain dengan material berkualitas tinggi, sepatu ini
              menawarkan kenyamanan dan sirkulasi udara, cocok untuk aktivitas
              sehari-hari dan olahraga ringan. Sol karet memberikan daya
              cengkeram yang baik. Detail tambahan yang terinspirasi oleh
              sejarah klub menambah nilai koleksi bagi penggemar Liverpool.
              <a
                href="https://wa.me/+6289665763920"
                target="_blank"
                class="mt-4 w-full bg-blue-800 text-white py-2 rounded-lg hover:bg-blue-600 text-center inline-block"
              >
                Klik Beli Disini
              </a>
            </p>
          </div>
        </div>
      </div>
    </section>

    <!-- Product Section -->
    <section id="Produk" class="bg-gray-50 py-16">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <p class="mt-4 text-gray-500 text-center">Jacket Casual</p>
        <div class="mt-8 grid gap-8 grid-cols-1 sm:grid-cols-2 lg:grid-cols-3">
          <!-- Product 4 -->
          <div class="bg-white shadow-lg rounded-lg p-4">
            <img src="img/foto jaket 1.jpg" />
            <h3 class="mt-4 text-xl font-bold text-blue-800">Company Series</h3>
            <p class="mt-2 text-gray-500">
              C.P. Company Series adalah lini produk dari merek pakaian Italia
              C.P. Company, yang mengkhususkan diri dalam teknologi garment dyed
              sejak 1971. Seri ini, terutama Metropolis Series, dirancang untuk
              sepenuhnya beradaptasi dengan lingkungan perkotaan, dengan fokus
              pada fungsionalitas, inovasi teknologi, dan desain mutakhir.
              Proses desain merek ini dipengaruhi oleh arsip pakaian yang
              substansial, yang digunakan untuk melakukan penelitian tentang
              pakaian militer, industri, atau utilitarian dan reinterpretasi
              detail desain mereka untuk menginformasikan hasil desain baru.
            </p>
            <a
              href="https://wa.me/+6289665763920"
              target="_blank"
              class="mt-4 w-full bg-blue-800 text-white py-2 rounded-lg hover:bg-blue-600 text-center inline-block"
            >
              Klik Beli Disini
            </a>
          </div>

          <!-- Product 5 -->
          <div class="bg-white shadow-lg rounded-lg p-4">
            <img src="img/foto jaket 2.jpg" />
            <h3 class="mt-4 text-xl font-bold text-blue-800">Company Series</h3>
            <p class="mt-2 text-gray-500">
              C.P. Company Series adalah lini produk dari merek pakaian Italia
              C.P. Company, yang mengkhususkan diri dalam teknologi garment dyed
              sejak 1971. Seri ini, terutama Metropolis Series, dirancang untuk
              sepenuhnya beradaptasi dengan lingkungan perkotaan, dengan fokus
              pada fungsionalitas, inovasi teknologi, dan desain mutakhir.
              Proses desain merek ini dipengaruhi oleh arsip pakaian yang
              substansial, yang digunakan untuk melakukan penelitian tentang
              pakaian militer, industri, atau utilitarian dan reinterpretasi
              detail desain mereka untuk menginformasikan hasil desain baru.
            </p>
            <a
              href="https://wa.me/+6289665763920"
              target="_blank"
              class="mt-4 w-full bg-blue-800 text-white py-2 rounded-lg hover:bg-blue-600 text-center inline-block"
            >
              Klik Beli Disini
            </a>
          </div>

          <!-- Product 6 -->
          <div class="bg-white shadow-lg rounded-lg p-4">
            <img src="img/foto 3 ganti.jpg" />
            <h3 class="mt-4 text-xl font-bold text-blue-800">Company Series</h3>
            <p class="mt-2 text-gray-500">
              C.P. Company Series adalah lini produk dari merek pakaian Italia
              C.P. Company, yang mengkhususkan diri dalam teknologi garment dyed
              sejak 1971. Seri ini, terutama Metropolis Series, dirancang untuk
              sepenuhnya beradaptasi dengan lingkungan perkotaan, dengan fokus
              pada fungsionalitas, inovasi teknologi, dan desain mutakhir.
              Proses desain merek ini dipengaruhi oleh arsip pakaian yang
              substansial, yang digunakan untuk melakukan penelitian tentang
              pakaian militer, industri, atau utilitarian dan reinterpretasi
              detail desain mereka untuk menginformasikan hasil desain baru.
            </p>
            <a
              href="https://wa.me/+6289665763920"
              target="_blank"
              class="mt-4 w-full bg-blue-800 text-white py-2 rounded-lg hover:bg-blue-600 text-center inline-block"
            >
              Klik Beli Disini
            </a>
          </div>
        </div>
      </div>
    </section>

    <!-- Product Section -->
    <section id="Produk" class="bg-gray-50 py-16">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <p class="mt-4 text-gray-500 text-center">Polo Shirt</p>
        <div class="mt-8 grid gap-8 grid-cols-1 sm:grid-cols-2 lg:grid-cols-3">
          <!-- Product 7 -->
          <div class="bg-white shadow-lg rounded-lg p-4">
            <img src="img/polo 1.jpg" />
            <h3 class="mt-4 text-xl font-bold text-blue-800">
              Polo Fred Perry
            </h3>
            <p class="mt-2 text-gray-500">
              Fred Perry adalah merek pakaian yang terkenal, terutama dikenal
              karena produk polo-nya yang ikonik. Didirikan pada tahun 1952 oleh
              juara tenis asal Inggris, Fred Perry, merek ini awalnya dimulai
              dengan fokus pada pakaian olahraga, tetapi kemudian berkembang
              menjadi simbol gaya hidup dan budaya.
            </p>
            <a
              href="https://wa.me/+6289665763920"
              target="_blank"
              class="mt-4 w-full bg-blue-800 text-white py-2 rounded-lg hover:bg-blue-600 text-center inline-block"
            >
              Klik Beli Disini
            </a>
          </div>

          <!-- Product 8 -->
          <div class="bg-white shadow-lg rounded-lg p-4">
            <img src="img/polo 2.jpg" />
            <h3 class="mt-4 text-xl font-bold text-blue-800">
              Polo Fred Perry
            </h3>
            <p class="mt-2 text-gray-500">
              Fred Perry adalah merek pakaian yang terkenal, terutama dikenal
              karena produk polo-nya yang ikonik. Didirikan pada tahun 1952 oleh
              juara tenis asal Inggris, Fred Perry, merek ini awalnya dimulai
              dengan fokus pada pakaian olahraga, tetapi kemudian berkembang
              menjadi simbol gaya hidup dan budaya.
            </p>
            <a
              href="https://wa.me/+6289665763920"
              target="_blank"
              class="mt-4 w-full bg-blue-800 text-white py-2 rounded-lg hover:bg-blue-600 text-center inline-block"
            >
              Klik Beli Disini
            </a>
          </div>

          <!-- Product 9 -->
          <div class="bg-white shadow-lg rounded-lg p-4">
            <img src="img/polo 3.jpg" />
            <h3 class="mt-4 text-xl font-bold text-blue-800">
              Polo Fred Perry
            </h3>
            <p class="mt-2 text-gray-500">
              Fred Perry adalah merek pakaian yang terkenal, terutama dikenal
              karena produk polo-nya yang ikonik. Didirikan pada tahun 1952 oleh
              juara tenis asal Inggris, Fred Perry, merek ini awalnya dimulai
              dengan fokus pada pakaian olahraga, tetapi kemudian berkembang
              menjadi simbol gaya hidup dan budaya.
            </p>
            <a
              href="https://wa.me/+6289665763920"
              target="_blank"
              class="mt-4 w-full bg-blue-800 text-white py-2 rounded-lg hover:bg-blue-600 text-center inline-block"
            >
              Klik Beli Disini
            </a>
          </div>
        </div>
      </div>
    </section>

    <!-- Services Section -->
    <section id="Layanan" class="bg-white py-16">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <h2 class="text-3xl font-bold text-blue-800 text-center">
          Layanan Yang Tersedia
        </h2>
        <p class="mt-4 text-gray-500 text-center"></p>
        <div class="mt-8 flex justify-center space-x-4">
          <a
            href="https://shopee.co.id/arkosecond.id"
            target="_blank"
            class="nav-link bg-orange-800 text-white py-2 px-4 rounded-lg hover:bg-red-600 flex items-center"
          >
            <img src="img/logo shope.png" alt="Shopee" class="h-6 mr-2" />
            Shopee
          </a>
          <a
            href="https://www.instagram.com/ilhammmmmaulana"
            target="_blank"
            class="nav-link bg-pink-500 text-white py-2 px-4 rounded-lg hover:bg-pink-600 flex items-center"
          >
            <img src="img/logo ig.png" alt="Instagram" class="h-6 mr-2" />
            Instagram
          </a>
          <a
            href="https://wa.me/+6289665763920"
            target="_blank"
            class="nav-link bg-green-500 text-white py-2 px-4 rounded-lg hover:bg-green-600 flex items-center"
          >
            <img src="img/logo wa.png" alt="WhatsApp" class="h-6 mr-2" />
            WhatsApp
          </a>
        </div>
      </div>
    </section>

    <!-- About Section -->
    <section id="Tentang Kami" class="bg-gray-50 py-16">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <h2 class="text-3xl font-bold text-blue-800 text-center">Tentang</h2>
        <p class="mt-4 text-gray-500 text-center">
          Kepuasaan costumer adalah prioritas utama kami
        </p>

        <!-- Google Maps Embed -->
        <div class="mt-8">
          <h3 class="text-xl font-semibold text-blue-800 text-center">
            Lokasi
          </h3>
          <iframe
            src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3151.835434509051!2d107.1665801!3d-6.3246117!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2e699b0c08ad8d01%3A0x2b18001d1b1371f9!2sUNIVERSITAS+PELITA+BANGSA!5e0!3m2!1sid!2sid!4v1631287971472!5m2!1sid!2sid"
            width="600"
            height="450"
            style="border: 0"
            allowfullscreen=""
            loading="lazy"
            class="mx-auto"
          ></iframe>
        </div>

        <!-- Email Display -->
        <div class="mt-8 text-center">
          <p class="text-gray-500">
            Email:
            <a
              href="mailto:Joutpit@gmail.com"
              class="text-blue-800 hover:underline"
            >
              Joupit@gmail.com
            </a>
          </p>
        </div>
      </div>
    </section>
    <script>
      function toggleMenu() {
        const mobileMenu = document.getElementById("mobile-menu");
        mobileMenu.classList.toggle("active");
      }
    </script>
  </body>
</html>

# demo 
![image](https://github.com/user-attachments/assets/35430933-e7f8-4474-b0a0-ce636a96fd09)
pada button klik disini akan diarahkan ke dalam whatsapp untuk pemesanan selanjutnya
![image](https://github.com/user-attachments/assets/4d31d20d-4034-4209-97e5-679260b87e5e)
pada di bagian button shopee akan di arahkan ke shopee toko, lalu ke bagian instagram diarahkan ke instagram toko dan whatsapp diarahkan ke admin toko.
![Uploading Screenshot (88).png…]()
![Screenshot (87)](https://github.com/user-attachments/assets/3f9aa2e3-6510-4bc7-a35c-7f148861ec52)
![Screenshot (86)](https://github.com/user-attachments/assets/fe3b81c9-3a8a-4903-b513-94cd9774220d)
