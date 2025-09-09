# Sistem Kasir Café

Aplikasi kasir ini digunakan untuk mencatat pesanan pelanggan, menghitung total harga dengan pajak 10%, serta memproses pembayaran menggunakan tunai atau e-wallet.

## Langkah Penggunaan
1. Kasir menerima pesanan dari pelanggan.
2. Masukkan daftar pesanan ke dalam aplikasi.
3. Sistem akan otomatis menghitung subtotal + pajak 10%.
4. Kasir memilih metode pembayaran:
   - Tunai → sistem menampilkan jumlah yang harus dibayar.
   - E-Wallet → sistem menghasilkan kode QR untuk pembayaran.
5. Setelah pembayaran berhasil, sistem mencetak struk.

## Contoh Input/Output
**Input Pesanan:**
- Nasi Goreng (Rp20.000)
- Es Teh (Rp5.000)

**Output Sistem:**
- Subtotal: Rp25.000  
- Pajak (10%): Rp2.500  
- Total: Rp27.500
