# Bocoran & Tips untuk 4 Tantangan Flexbox

### Tugas 1: Sidebar Layout
- Gunakan `display: flex;` pada `.sidebar-container`.
- Gunakan `width: 200px;` **TAPI** tambahkan `flex-shrink: 0;` karena flexbox terkadang mencoba menyusutkan elemen jika ruang tidak cukup.
- Gunakan `flex: 1;` pada `.main-content`. Ini adalah "shorthand" ajaib agar elemen mengambil sisa ruang yang ada.

### Tugas 2: Photo Grid (Wrapping)
- Gunakan `flex-wrap: wrap;` pada `.grid-container`. Tanpa ini, semua foto akan dipaksa satu baris (dan menyusut).
- Gunakan `gap: 16px;` untuk jarak antar foto yang konsisten.

### Tugas 3: Centered Hero Section
- Gunakan "Flexbox Centering" yang legendaris pada `.hero-container`:
  ```css
  display: flex;
  justify-content: center;
  align-items: center;
  ```
- Ingat bahwa `.hero-content` adalah anak dari container tersebut, jadi dia akan ada di tengah. Di dalamnya, Anda butuh `flex-direction: column;` untuk menumpuk teks dan tombol.

### Tugas 4: Build It Yourself
- Gunakan pengetahuan "Left | Center | Right" yang kita pelajari di Latihan Header.
- Gunakan `align-items: center;` agar Foto Profil, Teks, dan Ikon Hati sejajar secara vertikal.
- Gunakan `flex: 1;` pada area teks tengah agar dia mengambil ruang di antara foto profil dan ikon hati.

Selamat menantang diri sendiri! Anda pasti bisa.
