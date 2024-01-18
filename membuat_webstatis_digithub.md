Buat Repository:

Buat repository baru di GitHub.
Pastikan repository tersebut memiliki nama sesuai format: <username>.github.io, di mana <username> adalah nama pengguna GitHub Anda. Misalnya, jika nama pengguna GitHub Anda adalah "john", nama repository-nya harus menjadi "john.github.io".
Klon Repository:

Gunakan Git untuk mengklon repository tersebut ke komputer lokal Anda.
bash
Copy code
git clone https://github.com/<username>/<username>.github.io.git
Buat Struktur Situs Web:

Buat struktur situs web Anda di dalam repository lokal. Misalnya, buat file index.html sebagai halaman utama situs Anda.
Tambahkan Konten:

Tambahkan file HTML, CSS, JavaScript, atau aset lainnya sesuai dengan kebutuhan situs Anda.
Commit dan Push:

Lakukan commit dan push perubahan Anda ke repository GitHub.
bash
Copy code
git add .
git commit -m "Menambahkan halaman utama"
git push origin master
Aktifkan GitHub Pages:

Buka pengaturan repository di GitHub.
Gulir ke bawah hingga menemukan bagian "GitHub Pages".
Pilih branch yang berisi situs web Anda (biasanya master).
Klik "Save" atau "Save Changes".
Akses Situs Web:

Setelah beberapa saat, situs web Anda akan dapat diakses melalui URL: https://<username>.github.io.
