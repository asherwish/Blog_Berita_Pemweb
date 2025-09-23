LAPORAN PRAKTIKUM KELOMPOK

PEMROGRAMAN WEB

Pratikum: Layout Website Menggunakan HTML

 
Oleh:
I Made Dedy Wanditya (42430042)

I Gede Nada Arsana (42430011)

Moh. Lukman hakim fhadillah (42430033)

I Gede Suwastika Pande Liemena (42230028)



PROGRAM STUDI TEKNOLOGI INFORMASI
FAKULTAS TEKNIK DAN INFORMATIKA
UNIVERSITAS PENDIDIKAN NASIONAL
2025

1.	PENDAHULUAN
Semantic HTML adalah praktik penulisan markup yang memberi makna jelas pada jenis konten di dalam halaman, sehingga browser dan mesin pencari dapat memahami konteks serta struktur informasi dengan lebih baik. Dengan memanfaatkan tag semantik seperti header, footer, article, section, dan nav, pengembang dapat mendeskripsikan fungsi tiap bagian konten secara eksplisit, alih-alih hanya mengandalkan elemen generik seperti div atau span. Pendekatan ini tidak hanya meningkatkan aksesibilitas bagi pengguna dengan assistive technologies (misalnya screen reader), tetapi juga memperkuat SEO karena mesin pencari lebih mudah mengenali bagian-bagian penting dari halaman. Dalam tugas kelompok ini, kami menerapkan prinsip Semantic HTML untuk membangun struktur halaman yang rapi, konsisten, dan mudah dirawat. Fokus kami mencakup pemilihan elemen semantik yang tepat untuk setiap jenis konten, penyusunan hierarki heading yang logis, serta pengayaan atribut aksesibilitas seperlunya. Dengan demikian, produk akhir tidak hanya ramah bagi pengguna dan mesin pencari, tetapi juga menjadi fondasi yang kuat untuk pengembangan tampilan (CSS) dan interaktivitas (JavaScript) di tahap berikutnya.

2.	PEMBAHASAN
Pada tugas ini, menjelaskan rancangan website berita sederhana yaitu Menit News, beberapa halaman layout yang kami buat, halaman tersebut antara lain: index.html (halaman beranda berita), berita_banjir.html, berita_bisnis.html, berita_olahraga.html, berita_life_style.html menggunakan semantic HTML (pure HTML tanpa CSS). Setiap bagian memuat alasan penggunaan elemen, potongan code, dan pratinjau tampilan.

<img width="559" height="217" alt="Tangkapan Layar 2025-09-23 pukul 12 04 23" src="https://github.com/user-attachments/assets/69c90912-b65a-436b-a19d-623d17fa7e6a" />

Dalam potongan kode ini ditunjukkan sebuah struktur HTML yang memenuhi standar HTML5, menetapkan bahasa dokumen untuk aksesibilitas dan SEO, memastikan pengodean karakter konsisten, mengatur tampilan agar responsif di perangkat mobile, memberi judul halaman yang terbaca browser/mesin pencari, serta memisahkan metadata dan konten sehingga halaman siap diisi elemen semantik (header, nav, main, footer) di tahap berikutnya.

<img width="872" height="464" alt="Tangkapan Layar 2025-09-23 pukul 14 45 17" src="https://github.com/user-attachments/assets/fa584e35-1065-4df4-9090-cc6d5bafb90a" />

Dalam potongan kode ini ditunjukkan struktur area atas (header), alasan menggunakan tag header dimana sebagai landmark area atas yang mengelompokan identitas situs, menu navigasi, dan fitur pencaharian berita. Alasan menggunakan tag nav dimana untuk menandai kumpulan tautan menu kategori berita agar mudah dipahami oleh pengguna. Tag marquee digunakan supaya konten teks bisa berjalan untuk membuat website berita menarik (tanpa menggunakan CSS).

 <img width="1000" height="475" alt="Tangkapan Layar 2025-09-23 pukul 15 11 49" src="https://github.com/user-attachments/assets/e782c11c-ec4f-4cab-8d57-24b25b6da40e" />

Dalam Potongan kode ini ditunjukkan struktur area main konten, alasan menggunakan tag main dimana dipakai sebagai landmark konten halaman utama, kemudian tag section digunakan untuk mengelompokkan bagian bertema dengan diawali dengan tag h2, tag section juga berfungsi untuk membantu pengguna dan mesin pencarian memahami struktur topik, contohnya section berita utama dan section trending, sehingga mesin pencaharian dapat mengenali bagian section yang ingin dicari, sedangkan tiap konten berita diberikan tag article untuk konten mandiri yang dapat dipahami terlepas dari konteks halaman.

 <img width="864" height="95" alt="footer" src="https://github.com/user-attachments/assets/11740f61-afb7-48ac-a68b-65fb544d0126" />

Dalam potongan kode ini ditunjukkan struktur area bawah (footer), alasan menggunakan  tag footer digunakan sebagai landmark penutup halaman yang menampung informasi permanent seperti hak cipta, tautan kebijakan, dan kontak. Penempatan tag footer tersebut berada diluar tag main, dimana footer juga berfungsi memperjelas batas antara konten utama dan menjaga konsistensi layout disemua halaman.

3.	KESIMPULAN
Penerapan Semantic HTML menjadikan struktur halaman lebih bermakna, mudah dipahami mesin pencari, dan lebih ramah aksesibilitas. Dengan memilih elemen semantik yang tepat, menyusun hierarki heading yang logis, serta menambahkan atribut aksesibilitas seperlunya, halaman menjadi rapi, konsisten, dan mudah dirawat.

LAMPIRAN
Link Github web berita sederhana: https://github.com/bliDedok/Blog_Berita_Pemweb.git



