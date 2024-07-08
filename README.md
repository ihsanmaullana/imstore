# IMSTORE

Selamat datang di IMSTORE! Toko online yang menyediakan berbagai pilihan HP berkualitas dengan harga terbaik. Di sini, Anda dapat menemukan produk terbaru dan terjamin originalitasnya dengan garansi resmi.

## Fitur

1. **Promosi**: Pesan selamat datang dan tautan untuk melihat produk baru.
2. **Navigasi**: 
   - Tautan ke halaman cara pembelian.
   - Tautan langsung untuk chat dengan admin melalui WhatsApp.
3. **Ajakan Bertindak (CTA)**: 
   - Formulir pencarian barang.
   - Teks promosi yang menarik.
4. **Daftar Produk**:
   - Menampilkan produk-produk terbaru dengan detail dan harga.
   - Tautan untuk membeli langsung melalui WhatsApp.
5. **Footer**: Informasi hak cipta dan nama toko.

## Teknologi yang Digunakan

- **HTML**: Untuk struktur halaman web.
- **Tailwind CSS**: Untuk styling dan desain responsif.

## Cara Penggunaan

### 1. Clone Repository
Clone repository ini ke lokal mesin Anda menggunakan perintah berikut:
```bash
git clone <URL_REPOSITORY_ANDA>
```

### 2. Buka File HTML
Buka file `index.html` dengan peramban pilihan Anda.

### 3. Menambahkan Produk Baru
Untuk menambahkan produk baru, ikuti langkah-langkah berikut:
1. Tambahkan div baru dalam bagian `<div class="grid grid-cols-1 sm:grid-cols-3 gap-4">`.
2. Pastikan struktur div produk baru mengikuti format produk yang ada.

### 4. Mengubah Informasi Produk
Untuk mengubah informasi produk, ubah teks dalam elemen-elemen berikut:
- **Nama Produk**: Elemen `<h3 class="mt-4 text-lg font-medium text-gray-900">`.
- **Harga Produk**: Elemen `<p class="mt-1.5 text-sm text-gray-700">`.
- **Tautan Pembelian**: Elemen `<a href="...">`.

### 5. Menyesuaikan Promosi
Ubah teks dalam bagian `<div class="bg-slate-900 px-4 py-3 text-white">` untuk menyesuaikan pesan promosi.

## Contoh Kode

Berikut adalah contoh kode untuk produk dalam daftar:
```html
<div class="group relative block overflow-hidden">
  <img
    src="assets/iphone-15-pro-max.jpg"
    alt="foto iphone 15 pro max"
    class="border border-slate-900 w-full object-cover transition duration-500 group-hover:scale-105 sm:h-72"
  />
  <div class="relative border border-slate-900 bg-white p-6">
    <span class="text-white whitespace-nowrap bg-slate-900 px-3 py-1.5 text-xs font-medium">New</span>
    <h3 class="mt-4 text-lg font-medium text-gray-900">Apple iPhone 15 Pro Max 256GB - Garansi Resmi iBox Apple Indonesia</h3>
    <p class="mt-1.5 text-sm text-gray-700">Rp25.249.000</p>
    <a
      href="https://wa.me/6285899998273?text=Saya%20ingin%20membeli%20Apple%20iPhone%2015%20Pro%20Max%20256GB%20-%20Garansi%20Resmi%20iBox%20Apple%20Indonesia,%20Apakah%20stoknya%20masih%20tersedia?"
      class="text-white w-full rounded bg-slate-900 p-4 text-sm font-medium transition hover:bg-gray-800 text-center block mt-4"
    >
      Beli Sekarang
    </a>
  </div>
</div>
```

## Kontak

Jika Anda memiliki pertanyaan atau membutuhkan bantuan, silakan hubungi kami melalui:
- **WhatsApp**: [Chat Admin](https://wa.me/6285899998273?text=Halo%20Admin,%20Saya%20ingin%20bertanya%20tentang%20produk%20yang%20tersedia%20di%20IMSTORE!)

Terima kasih telah berbelanja di IMSTORE!
