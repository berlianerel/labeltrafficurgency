# 🚦 Sistem Klasifikasi Aduan Lalu Lintas 🚦

Sistem ini digunakan untuk **mendeteksi tingkat urgensi aduan lalu lintas** berdasarkan teks laporan. Aduan diklasifikasikan menjadi **Ringan, Sedang, dan Fatal** menggunakan daftar kata yang telah ditentukan.

## 📌 Fitur
✅ **Membaca daftar kata dari file CSV**  
✅ **Memproses input teks dari pengguna**  
✅ **Mendeteksi dan mengklasifikasikan aduan**  
✅ **Menampilkan skor per kategori (Ringan, Sedang, Fatal)**  
✅ **Menggunakan lisensi MIT dan terdaftar sebagai HKI**  

---

## 📥 Cara Menggunakan
1. **Unduh atau klon repositori ini**
   ```bash
   git clone https://github.com/username/repo-name.git
   cd repo-name
   ```

2. **Pastikan kamu memiliki file set kata**  
   - **Jika menggunakan Google Drive**:  
     Ubah URL file pada bagian `url` dalam kode.

3. **Jalankan skrip Python**  
   ```bash
   python klasifikasi_aduan.py
   ```
   Masukkan teks aduan saat diminta.

---

## 📝 Contoh Penggunaan
```
=== Daftar Kata Per Kategori ===

Kategori: Ringan
lampu, marka, parkir, rambu, trotoar, zebra

Kategori: Sedang
arus, hujan, jalan, jalur, kemacetan, macet, rusak, traffic

Kategori: Fatal
ambulans, banjir, bencana, darurat, gempa, kecelakaan, korban, longsor, polisi, roboh, tabrak, terjebak, tumbang

Masukkan teks aduan: Ada kecelakaan di jalan utama, korban butuh ambulans!

=== Hasil Klasifikasi Aduan ===
Teks Aduan: Ada kecelakaan di jalan utama, korban butuh ambulans!
Skor Ringan: 0
Skor Sedang: 1
Skor Fatal: 3
Kategori: Fatal
```

---

## 📜 Lisensi
Kode ini dilindungi oleh **MIT License**.

```
MIT License

Copyright (c) 2025 Berlian Rahmy Lidiawaty

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## ⚖️ Hak Kekayaan Intelektual (HKI)
Proyek ini telah **didaftarkan sebagai Hak Cipta (HKI) di DJKI** (Direktorat Jenderal Kekayaan Intelektual) Indonesia.  
Pendaftaran dilakukan melalui situs resmi: [https://dgip.go.id/](https://dgip.go.id/)

📌 **Hak dan Batasan Penggunaan**:
- Kode ini **boleh digunakan dan dimodifikasi** secara bebas.
- Setiap penggunaan ulang harus mencantumkan **kredit ke pemilik asli**.
- Tidak diperbolehkan **mengklaim kode ini sebagai milik sendiri**.
- Penggunaan untuk tujuan **komersial** diperbolehkan **tanpa batasan**.

---

## 📧 Kontak
Jika ada pertanyaan atau kerja sama, silakan hubungi:
📩 **Email**: [email@example.com](mailto:email@example.com)  
🐦 **Twitter**: [@username](https://twitter.com/username)  
🌐 **Website**: [https://websiteanda.com](https://websiteanda.com)

---

💡 **Kontribusi**:  
Jika ingin berkontribusi dalam pengembangan proyek ini, silakan buat **pull request** atau buka **issue** di GitHub.  

🚀 **Selamat menggunakan sistem klasifikasi aduan!**
