# sipd-chrome-extension
Optimasi aplikasi SIPD dengan chrome extension
Semoga bermanfaat

### DONASI
- Donasi untuk pengembang aplikasi, klik di link ini https://smkasiyahhomeschooling.blogspot.com/p/donasi-pengembangan-smk-asiyah.html atau https://donasi.qodr.or.id/
- Untuk pemda yang kesulitan dalam penerapan wp-sipd atau belum memiliki tenaga IT, kami menawarkan jasa setting dan penerapan wp-sipd. Informasi lebih detail di https://wpsipd.qodrbee.com/

### GRUP telegram https://t.me/sipd_chrome_extension

### Plugin Wordpress WP-SIPD https://github.com/agusnurwanto/wp-sipd

### Pesan Untuk Tim Pengembang SIPD
- Semoga selalu diberi kesehatan dan aplikasi SIPD lancar digunakan oleh pemda
- Extension ini dibuat untuk mengoptimasi kinerja aplikasi SIPD
- Pengembangan script extension akan berhenti setelah aplikasi SIPD siap untuk mengakomodir semua fitur yang diperlukan oleh pemda
- Demikian dan salam semangat :blush:

### Cara Pakai Extension
- Download file master zip terbaru atau bisa clone repository ke lokal
- Buat file baru **config.js** dan copy isi dari **config.js.example** ke file **config.js**
- Edit configurasi file config.js menyesuaikan data dari pemda
- **id_daerah** bisa didapatkan dengan buka **inspect element > console log**. Ketikan kode **drakor** dan tekan **Enter**. Informasi lebih detail bisa cek video tutorial ini https://www.youtube.com/watch?v=VnySS0RE6zc
- Buka halaman [chrome://extensions/](chrome://extensions/), aktifkan developer mode.
- Tekan tombol **Load unpacked** dan pilih folder sipd-chrome-extension

### Fitur:
- Export data SSH ke database lokal
- Export data akun belanja ke database lokal
- Export RKA satu perangkat daerah ke database lokal
- Export rincian belanja per sub kegiatan ke database lokal
- Mapping multi standar harga ke multi rekening belanja langsung di SIPD
- Pencarian item standar harga dengan ID standar harga di halaman tambah rincian belanja
- Auto login user admin / penyelia SSH
- Download excel semua laporan
- Export SKPD ke database lokal
- Export RKA seluruh perangkat daerah
- Export program kegiatan ke database lokal
- Menampilkan nama TAPD di RKA pendapatan
- Menampilkan daftar SKPD yang lintas urusan di lampiran 2 APBD perda
- Menampilkan tanggal dan nama kepala daerah di lampiran 1-9 APBD perda dan 1-5 APBD penjabaran
- Import Dana Desa ke Rincian Sub kegiatan
- Import data sumber dana ke db lokal
- Menampilkan detail rincian lampiran 3-5 APBD penjabaran
- Import data RPJM
- Import data provinsi, kabupaten, kecamatan, desa
- Import data profile penerima bantuan
- Menampilkan detail rincian penerima bantuan di RKA dan rincian belanja
- Ganti Rekening/Akun Multi Komponen Rincian Belanja
- Hapus multi komponen
- Export data user kelurahan/desa ke database lokal
- Export data user anggota dewan ke database lokal
- Menambahkan tombol detail akun/rekening di halaman analisa belanja > standar harga
- Setting Nomor, tanggal dan keterangan Perkada
- Perbaikan fitur import BANKEU (tambah kolom keterangan)
- Import data RENSTRA
- Import data Pendapatan
- Import data Pembiayaan
- Integrasi data SIPD ke SIMDA keuangan
- Nama TAPD lebih dari 8 orang
- Get data rincian murni untuk printout APBD Penjabaran di wp-sipd lokal
- Export data usulan ASMAS
- Export data usulan POKIR
- Menampilkan tombol print lokal APBD Penjabaran lampiran 1,2,3,4,5,6
- Print RENJA per OPD dan semua OPD di halaman Pengaturan > Profil > Perangkat Daerah
- Print mandatory spending di halaman Pengaturan > Data > Label (Tag) Sub Kegiatan
- Update status non active di database lokal jika ada sub kegiatan yang dihapus di SIPD
- Allow right click
- Perbaikan bug error ubahSkpd saat singkron user tapd
- Perbaikan singkron master penerima bantuan dan pilih ssh by id encrypted
- Hapus duplikat item SSH & SBU
- Upload data penerima HIBAH, BOS, BANSOS, BANKEU
- Jaga session login agar tidak terlogout sendiri ketika user tidak aktif dalam 1 menit terakhir
- Modul usulan SSH dan singkronisasi ke SIPD

### Pengembangan berikutnya:
- Melengkapi dokumentasi penggunaan di halaman wiki
- Melengkapi video tutorial di youtube

### Video tutorial
- Cara install chrome extension https://www.youtube.com/watch?v=VnySS0RE6zc
- Mencari Komponen SSH dengan ID Standar Harga di halaman input rincian belanja 
    - v1 = https://www.youtube.com/watch?v=ixiwcs7xz8g
	- v2 = https://youtu.be/2MgCu5J_jcs
- Setting multi Standar Harga ke multi Rekening Belanja https://youtu.be/oIDmpfZm0kw
- Export SSH SIPD ke Database Server Lokal https://www.youtube.com/watch?v=lcLXBwSq9Ng
- Export RKA Kegiatan ke Database Server Lokal https://www.youtube.com/watch?v=t84n2jZUfFo
- Setting Tanggal RKA dan Nama TAPD https://www.youtube.com/watch?v=3z9zn506oTw
- Setting Tanggal RKA dan Nama TAPD di Aplikasi SIPD https://www.youtube.com/watch?v=UCroKhfaHKQ
- Print Laporan APBD Lampiran III Semua Perangkat Daerah https://www.youtube.com/watch?v=QZKb8LrHcpg
- Upload Excel Belanja Bantuan Keuangan Dana Desa https://www.youtube.com/watch?v=F3Db_v40Rh4
- Upload Excel Data BOS v2.8.0 https://www.youtube.com/watch?v=ASEzt7RnO48
- Release v1.9 perbaikan beberapa bug error dan menampilkan tanda tangan kepala daerah di lampiran APBD https://www.youtube.com/watch?v=UpQheTCkEN4
- Ganti/update Rekening Multi Komponen di halaman rincian belanja https://www.youtube.com/watch?v=Wo6BdOCPb1g
- Integrasi data SIPD ke SIMDA keuangan https://youtu.be/vFOsAlnxmTo
- Integrasi data APBD SIPD ke SIMDA Pink 2022 https://smkasiyahhomeschooling.blogspot.com/2021/12/sipd-chrome-extension-untuk-migrasi.html
- Integrasi data APBD SIPD ke FMIS https://smkasiyahhomeschooling.blogspot.com/2021/12/fmis-chrome-extension-untuk-integrasi.html