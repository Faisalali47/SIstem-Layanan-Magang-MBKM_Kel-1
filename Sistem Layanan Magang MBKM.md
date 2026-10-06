# Sistem Layanan Magang/MBKM

## 1. Layanan yang Dipilih

Layanan yang dipilih adalah **Sistem Layanan Magang/MBKM**. Sistem ini
dirancang untuk membantu proses magang mahasiswa mulai dari pencarian
program, pengajuan, verifikasi, pelaksanaan, penilaian, hingga proses
konversi atau rekognisi SKS.

## 2. Fitur Unggulan

Fitur unggulan yang diusulkan adalah **Integrated Internship
Management**, yaitu fitur pengelolaan magang yang menghubungkan seluruh
pihak yang terlibat dalam proses magang melalui satu platform.

Pihak yang terlibat meliputi mahasiswa, Dosen Pembimbing Akademik (DPA),
Dosen Pembimbing Magang, pihak perusahaan magang, dan pengelola sistem
atau pihak kampus. Setiap pihak memiliki hak akses dan fungsi yang
berbeda sesuai dengan perannya.

Dengan adanya fitur ini, informasi mengenai pengajuan, dokumen, status,
perkembangan kegiatan, penilaian, dan proses konversi SKS dapat dikelola
dalam satu sistem sehingga proses magang menjadi lebih terkoordinasi.

## 3. Analisis Kebutuhan

1.  **Sebagai mahasiswa, saya membutuhkan informasi program magang yang
    tersedia beserta instansi, periode, dan persyaratannya, agar saya
    dapat memilih program yang sesuai.**

2.  **Sebagai mahasiswa, saya membutuhkan fasilitas pengajuan magang dan
    unggah dokumen secara online, agar saya tidak perlu mengirimkan
    dokumen melalui media yang terpisah.**

3.  **Sebagai mahasiswa, saya membutuhkan informasi status pengajuan
    magang, agar saya dapat mengetahui perkembangan pengajuan tanpa
    harus menanyakan status secara terpisah.**

4.  **Sebagai Dosen Pembimbing Akademik (DPA), saya membutuhkan akses
    untuk melihat dan melakukan screening terhadap pengajuan mahasiswa,
    agar proses pemeriksaan dapat dilakukan dengan lebih terstruktur.**

5.  **Sebagai Admin/Staff Prodi, saya membutuhkan data pengajuan dan
    dokumen mahasiswa yang terorganisir, agar proses verifikasi
    administrasi dapat dilakukan dengan lebih mudah dan terkontrol.**

6.  **Sebagai mahasiswa, saya membutuhkan informasi hasil screening atau
    permintaan perbaikan dokumen, agar saya dapat mengetahui tindakan
    yang perlu dilakukan terhadap pengajuan saya.**

## 4. Arsitektur Sistem

Arsitektur sistem dirancang menggunakan pendekatan berbasis web. Seluruh
pengguna mengakses sistem melalui antarmuka yang sama, kemudian sistem
memproses permintaan berdasarkan hak akses dan peran masing-masing
pengguna.

Data seperti informasi program magang, data pengajuan, status,
penilaian, dan riwayat disimpan secara terpusat. Dokumen pengajuan dan
laporan magang juga dikelola melalui sistem sehingga dapat diakses oleh
pihak yang memiliki kewenangan.

Gambar arsitektur sistem akan dibuat dan dilampirkan secara terpisah.

## 5. Alur Fitur Unggulan

Fitur **Integrated Internship Management** menghubungkan proses magang
dari awal sampai selesai. Alur dimulai ketika mahasiswa memilih program
dan mengajukan permohonan beserta dokumen. Pengajuan kemudian diperiksa
oleh DPA dan pihak kampus.

Setelah pengajuan disetujui, pihak perusahaan dapat memberikan
konfirmasi penerimaan mahasiswa. Selama kegiatan magang berlangsung,
mahasiswa dapat mencatat perkembangan kegiatan, sedangkan Dosen
Pembimbing Magang dapat melakukan monitoring dan bimbingan.

Setelah kegiatan selesai, mahasiswa mengunggah laporan. Dosen Pembimbing
Magang dan pihak perusahaan dapat memberikan penilaian. Hasil kegiatan
kemudian diproses oleh pihak kampus untuk kebutuhan verifikasi dan
konversi atau rekognisi SKS.

Gambar alur fitur akan dibuat dan dilampirkan secara terpisah.

## 6. Alasan Desain

Sistem dirancang dalam satu platform karena proses magang melibatkan
beberapa pihak dengan tanggung jawab yang berbeda. Dengan sistem yang
terintegrasi, setiap pihak dapat mengakses informasi yang dibutuhkan
tanpa harus menggunakan media yang berbeda.

Sistem juga menggunakan pembagian hak akses berdasarkan peran agar
setiap pengguna hanya dapat melakukan aktivitas sesuai tanggung
jawabnya. Selain itu, data dan dokumen dikelola secara terpusat sehingga
informasi dalam proses magang lebih mudah ditelusuri.

Fitur tracking status juga dipilih karena mahasiswa perlu mengetahui
perkembangan pengajuan tanpa harus menanyakan status secara manual
kepada pihak kampus.

## 7. Asumsi Tim

-   Sistem digunakan oleh mahasiswa, DPA, Dosen Pembimbing Magang, pihak
    perusahaan, dan pengelola sistem atau pihak kampus.
-   Setiap pengguna memiliki akun dan hak akses sesuai dengan perannya.
-   Program atau posisi magang yang tersedia telah dimasukkan oleh pihak
    yang berwenang.
-   Proses screening, penerimaan mahasiswa, pembimbingan, penilaian, dan
    konversi SKS mengikuti ketentuan yang ditetapkan oleh kampus dan
    pihak perusahaan.
-   Dokumen pengajuan dan laporan magang dapat diunggah dalam format
    yang telah ditentukan oleh sistem.
-   Sistem digunakan untuk mengintegrasikan proses layanan magang,
    sedangkan keputusan akhir tetap berada pada pihak yang memiliki
    kewenangan.

## 8. Kesimpulan

Sistem Layanan Magang/MBKM dirancang sebagai platform terintegrasi yang
menghubungkan mahasiswa, pihak kampus, dosen pembimbing, dan perusahaan
dalam satu proses layanan.

Fitur **Integrated Internship Management** menjadi fitur unggulan karena
seluruh proses magang, mulai dari pengajuan hingga konversi SKS, dapat
dikelola dan dipantau dalam satu sistem dengan hak akses yang
disesuaikan untuk setiap pengguna.
