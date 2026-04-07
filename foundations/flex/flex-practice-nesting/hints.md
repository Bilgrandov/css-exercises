# Hint untuk Latihan Flexbox Nesting

Jika Anda bingung, coba ingat konsep-konsep ini:

### 1. Hubungan Orang Tua & Anak
Flexbox **hanya** mengatur anak langsungnya. 
- `.container` adalah "Orang Tua" dari `.card`. 
- `.card` adalah "Orang Tua" dari `.avatar`, `h3`, dan `p`.

### 2. Arah Aliran (Flex Direction)
Secara default, flex akan berjejer ke samping (`row`). 
- Jika ingin menumpuk ke bawah, gunakan `flex-direction: column;`.

### 3. Perataan (Alignment)
- Jika direction-nya `row` (default), `justify-content` mengatur horizontal, `align-items` mengatur vertikal.
- Jika direction-nya `column`, **kebalikannya**: `justify-content` mengatur vertikal, `align-items` mengatur horizontal.

### Contoh Properti Penting:
- `display: flex;` -> Wajib ada di setiap kontainer.
- `gap: 20px;` -> Untuk jarak antar item.
- `align-items: center;` -> Sangat sakti untuk memindahkan isi ke tengah.

Selamat mencoba!
