1.Persiapkan Repositori GitHub:
  Buat repositori baru di akun GitHub Anda.
  Beri nama repositori sesuai keinginan Anda.

2.Install Jekyll secara Lokal (Opsional):
  Anda dapat menginstal Jekyll secara lokal di komputer Anda untuk menguji situs web secara lokal sebelum diunggah ke GitHub.
  Untuk melakukannya, ikuti panduan instalasi di situs web resmi Jekyll.

3.Fork atau Clone Jekyll Theme:
  Fork atau clone tema Jekyll yang Anda inginkan dari GitHub. Misalnya,
  Anda dapat menggunakan salah satu tema yang disediakan di Jekyll Themes.

4.Konfigurasi Repositori:
  Jika Anda menggunakan tema Jekyll, lihat petunjuk konfigurasi yang diberikan oleh tema tersebut.
  Buat berkas _config.yml untuk konfigurasi situs web Anda. Sesuaikan dengan preferensi Anda.

5.Tambahkan Konten:
  Tambahkan halaman atau posting blog di direktori _posts untuk posting blog, atau buat halaman statis di direktori utama (root).
  Gunakan format Markdown atau HTML untuk menulis konten.

6.Uji Situs secara Lokal (Opsional):
  Jika Anda menginstal Jekyll secara lokal, jalankan perintah jekyll serve dari terminal di direktori proyek Anda.
  Buka browser dan akses http://localhost:4000 untuk melihat situs web secara lokal.

7.Unggah ke GitHub:
  Tambahkan semua perubahan ke repositori lokal Anda dengan perintah git add ..
  Buat commit dengan perintah git commit -m "Tambahkan situs web Jekyll".
  Unggah ke repositori GitHub dengan perintah git push origin master (pastikan untuk mengganti master sesuai dengan nama cabang yang Anda gunakan).

8.Aktifkan GitHub Pages:
  Buka pengaturan repositori GitHub Anda.
  Pada bagian "GitHub Pages," pilih sumber (misalnya, cabang master) dari mana GitHub akan meng-host situs web Jekyll Anda.

9.Akses Situs Web:
  Setelah beberapa saat, situs web Anda akan dapat diakses melalui tautan GitHub Pages (biasanya https://username.github.io/nama-repositori).
