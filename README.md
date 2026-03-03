# Book Sales Data Analysis

> Tools: Microsoft Excel | Python | Power BI&nbsp;|&nbsp;Oleh: Fernando Hasiholan Sinaga

---

## Latar Belakang

Toko buku menghasilkan data penjualan dalam jumlah besar setiap harinya, namun tidak semua data tersebut dimanfaatkan secara optimal. Pertanyaan itulah yang menjadi dasar dari proyek ini.

Dengan 971 data buku yang telah melalui proses cleaning, proyek ini berusaha menjawab pertanyaan bisnis yang sederhana namun penting: Buku mana yang paling laris? Genre apa yang paling diminati? Publisher mana yang paling dominan? Author mana yang paling banyak dibeli dan paling disukai pembaca?

Proyek ini merupakan latihan nyata dalam mengolah data dari awal, mulai dari data cleaning menggunakan Python, eksplorasi data menggunakan Excel, hingga penyajian dalam dashboard Power BI yang dapat digunakan langsung untuk pengambilan keputusan bisnis.

---

## Alur Kerja

### 1. Data Cleaning - Python (Pandas Library)

Tahapan pertama adalah membersihkan data yang belum siap dianalisis. Missing values ditangani menggunakan df.dropna(), kolom yang tidak relevan seperti index, sales rank, dan author rating dihapus untuk menyederhanakan dataset. Tipe data pada kolom Publishing Year dikonversi dari float ke integer, dan inkonsistensi pada kolom genre diatasi dengan menggabungkan kategori "genre fiction" dan "fiction" menjadi satu. Setelah seluruh proses ini selesai, data sudah bersih dan siap untuk dianalisis lebih lanjut.

### 2. Exploratory Data Analysis - Microsoft Excel (Pivot Table)

Tahapan kedua adalah eksplorasi data menggunakan Pivot Table di Microsoft Excel. Data yang sudah bersih dianalisis untuk menemukan pola penjualan, performa per genre, publisher dan author terlaris, hingga distribusi pasar berdasarkan bahasa buku.

**Key Metrics yang ditemukan:**

| Metric | Value |
|---|---|
| Total Unit Terjual | 9.537.104 |
| Total Gross Sales | $1.842.674.350 |
| Jumlah Data Buku | 971 |
| Rata-rata Rating | 4,00 |

### 3. Visualisasi Data - Power BI

Semua temuan dari EDA disajikan dalam satu dashboard interaktif di Power BI. Dashboard ini menampilkan performa penjualan per genre, author, publisher, dan bahasa buku secara visual dan mudah dibaca.

---

## Key Findings

**Buku Terlaris**
"New Moon: The Complete Illustrated Movie Companion" jadi buku yang paling banyak terjual dengan 61.560 unit dan gross sales $1.560.580, disusul "Maybe Someday" dan "Mr Maybe" dengan masing-masing 61.128 unit.

**Publisher Terkuat**
Amazon Digital Services paling banyak menjual buku dengan 5,6 juta unit, tapi dari sisi pendapatan, Random House LLC justru yang tertinggi dengan total $91,5 miliar.

**Genre Paling Laku**
Fiction jadi genre yang paling diminati dengan 7,7 juta unit terjual atau sekitar 81% dari total penjualan. Nonfiction dan children jauh tertinggal di belakangnya.

**Author Terbaik**
Stephen King jadi author paling banyak dibeli dengan 270.824 unit dari 27 judul buku. Untuk rating, J.R. Ward dan Colleen Hoover mendapat nilai tertinggi dengan rata-rata 4,33.

**Bahasa Buku**
Buku berbahasa Inggris mendominasi hampir seluruh penjualan dengan 6,9 juta unit atau 96% dari total. Buku berbahasa Spanyol, Prancis, dan Belanda masih sangat sedikit peminatnya.

---

## Rekomendasi

**Perbanyak Stok Fiction**
Karena fiction jelas jadi favorit pembeli, sebaiknya porsi stok terbesar difokuskan ke genre ini, terutama buku dari Stephen King, Janet Evanovich, dan Colleen Hoover yang sudah terbukti laris.

**Jaga Hubungan Baik dengan Publisher Besar**
Amazon Digital Services, Random House LLC, dan Penguin Group adalah publisher yang paling berpengaruh. Hubungan yang baik dengan mereka bisa membuka peluang harga lebih bagus dan akses ke judul-judul terbaru lebih cepat.

**Tampilkan Buku dari Author Berrating Tinggi di Posisi Utama**
Buku dari J.R. Ward, Colleen Hoover, dan Jim Butcher layak ditampilkan lebih depan karena rating tinggi biasanya jadi pertimbangan utama pembeli sebelum memutuskan beli.

**Perkuat Koleksi Buku Bahasa Inggris**
Pastikan stok buku berbahasa Inggris selalu lengkap karena itu yang paling banyak dicari. Kalau ingin coba pasar baru, buku berbahasa Spanyol atau Prancis bisa mulai diperkenalkan dalam jumlah kecil dulu.

**Lebih Selektif dalam Memilih Judul Nonfiction dan Children**
Kedua genre ini penjualannya tidak sebesar fiction, jadi perlu lebih hati-hati dalam memilih judul mana yang layak distok agar tidak menumpuk dan tetap menguntungkan.

---

## Conclusion

Dari 971 data buku yang dianalisis, terlihat jelas bahwa fiction adalah genre yang paling dicari, buku berbahasa Inggris menguasai hampir seluruh pasar, dan nama-nama seperti Stephen King serta Random House sudah jadi pilihan utama pembeli. Rating rata-rata koleksi sebesar 4,00 juga menunjukkan bahwa buku-buku yang ada sudah cukup disukai pembaca.

Temuan ini bisa langsung dipakai sebagai dasar untuk mengatur stok, memilih mitra publisher dan menentukan arah pengembangan koleksi ke depannya. Kalau ke depan datanya bisa dilengkapi dengan tren penjualan per periode dan data pelanggan, analisisnya tentu bisa jauh lebih tajam dan berguna.

## Contact

| Platform | Link |
|---|---|
| GitHub | [fernandosinaga123456](https://github.com/fernandosinaga123456) |
| Email | [fernandosinaga2002@gmail.com](mailto:fernandosinaga2002@gmail.com) |
| LinkedIn | [Fernando Hasiholan Sinaga](https://www.linkedin.com/in/fernandohasiholansinaga/) |
| Portfolio | [datascienceportfol.io/fernandosinaga_h](https://www.datascienceportfol.io/fernandosinaga_h) |
| Instagram | [@fernandosng_](https://www.instagram.com/fernandosng_) |
