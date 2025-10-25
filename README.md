Langkah-langkah Membuat Repository dan Mengaktifkan GitHub Pages

a. Membuat Repository Baru & Mengaktifkan GitHub Pages
1. Login ke akun GitHub kamu.

2. Klik tombol “New Repository” (biasanya di halaman utama GitHub atau di menu profil kanan atas).

3. Isi detail repository:
Repository name → misalnya: my-website
Tambahkan deskripsi (opsional)
Pilih Public agar bisa diakses semua orang
Centang Add a README file (opsional tapi disarankan)

4. Klik Create repository.

5. Setelah repository dibuat, buka tab Settings → Pages.

6. Di bagian Source, pilih branch:
main (atau master jika itu nama branch utamamu)
Folder / (root)

7. Klik Save.

8. Tunggu beberapa menit, lalu buka link yang muncul seperti:
👉 https://username.github.io/my-website/

b. Struktur Folder dan File Sederhana

my-website/
│
├── index.html
└── style.css

Penjelasan:

index.html → file utama halaman web.

style.css → file berisi desain/tampilan (warna, font, layout, dll).

c. Menghubungkan File CSS ke HTML

Agar desain dari style.css muncul di web, tambahkan kode berikut di dalam tag <head> di file index.html:
<link rel="stylesheet" href="style.css">

Contoh lengkap index.html:

<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Website Pertamaku</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <h1>Halo Dunia!</h1>
  <p>Selamat datang di website pertamaku di GitHub Pages 🎉</p>
</body>
</html>

Contoh style.css:

body {
  font-family: Arial, sans-serif;
  background-color: #f3f3f3;
  text-align: center;
  padding: 50px;
}

h1 {
  color: #0078ff;
}
