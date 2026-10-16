Jelaskan apa itu Bootstrap dan apa kegunaannya!
Bootstrap adalah framework CSS yang digunakan untuk mempermudah pembuatan tampilan website agar menarik, konsisten, dan responsif. Bootstrap menyediakan berbagai komponen dan class siap pakai, seperti navbar, button, form, card, dan grid, sehingga pengembang tidak perlu membuat semua desain dari awal.

Ada beberapa cara untuk mengimpor atau menggunakan Bootstrap pada project. Sebutkan cara
caranya! 
Ada beberapa cara untuk menggunakan Bootstrap pada project, yaitu:
    - Menggunakan CDN (Content Delivery Network): Menghubungkan Bootstrap melalui URL CSS dan JavaScript yang tersedia secara online.
    - Download Bootstrap: Mengunduh file Bootstrap, kemudian menyimpan dan menghubungkannya ke project secara lokal.
    - Menggunakan package manager: Menginstal Bootstrap melalui npm atau package manager lainnya.
    
Jelaskan mengenai class grid dan kegunaan breakpoint! 
    - Grid adalah sistem tata letak Bootstrap yang membagi halaman menjadi 12 kolom untuk mengatur posisi dan ukuran elemen website. Grid       biasanya menggunakan class .container, .row, dan .col.
    - Breakpoint adalah batas ukuran layar yang digunakan untuk menyesuaikan tampilan website pada berbagai perangkat, seperti HP,              tablet, dan komputer.
    Contoh class grid berdasarkan breakpoint:
        - .col-12: menggunakan 12 kolom pada semua ukuran layar.
        - .col-md-6: menggunakan 6 kolom pada layar berukuran medium ke atas.
        - .col-lg-4: menggunakan 4 kolom pada layar berukuran large ke atas.
        
Sebutkan minimal lima class yang disediakan oleh Bootstrap beserta kegunaannya! 
Berikut lima class Bootstrap beserta kegunaannya:
    .container : Membuat wadah konten dengan lebar yang responsif.
    .row : Membuat baris untuk menyusun kolom dalam grid.
    .col : Membuat kolom dalam sistem grid.
    .btn : Memberikan gaya pada tombol.
    .text-center : Membuat teks rata tengah.
    .img-fluid : Membuat gambar responsif sesuai ukuran wadahnya.
    .navbar : Membuat navigasi website.
    
Bagaimana cara agar foto atau gambar pada website responsif menyesuaikan ukuran layar 
perangkat? 
    Menggunakan class .img-fluid pada tag <img>. Class ini membuat gambar menyesuaikan ukuran wadahnya dan mempertahankan rasio gambar        agar tidak terdistorsi.
        Contoh kode:
            <img src="gambar.jpg" class="img-fluid" alt="Gambar">
    Class .img-fluid menerapkan properti CSS max-width: 100% dan height: auto, sehingga gambar tidak melebihi lebar wadahnya dan              tingginya menyesuaikan secara otomatis.
