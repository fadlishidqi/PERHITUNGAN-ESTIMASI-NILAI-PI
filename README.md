# Integrasi Reimann untuk Perkiraan Pi

Metode integrasi Reimann digunakan untuk menghitung perkiraan nilai pi dengan membagi area di bawah kurva fungsi 4 / (1 + x^2) menjadi persegi panjang kecil dan menghitung total luasnya.

## Dependencies

- numpy
- matplotlib

## Cara Penggunaan

1. Pastikan memiliki Python yang sesuai dengan dependensi yang disebutkan di atas.
2. Unduh atau kloning repositori ini.
3. Jalankan script Python `reimann_integration.py`.
4. Script akan menghitung perkiraan nilai pi dengan berbagai nilai N (jumlah persegi panjang), mengukur galat RMS terhadap nilai referensi pi, dan mengukur waktu eksekusi.
5. Grafik hasil akan ditampilkan, termasuk galat RMS terhadap N dan waktu eksekusi terhadap N.

## Deskripsi Kode

- `reimann_integration.py`: Script utama yang menggunakan metode integrasi Reimann untuk menghitung nilai perkiraan pi, mengukur galat RMS, dan waktu eksekusi untuk berbagai nilai N.

## Hasil Analisis

- Grafik menunjukkan bagaimana galat RMS dan waktu eksekusi bervariasi dengan jumlah persegi panjang (N).
- Galat RMS adalah perbedaan antara nilai perkiraan dan nilai referensi pi.
- Waktu eksekusi menunjukkan berapa lama waktu yang dibutuhkan untuk menghitung perkiraan nilai pi untuk setiap N.

## Catatan

- Pastikan untuk memeriksa dan menyesuaikan nilai `nilai_N` sesuai kebutuhan Anda dalam script sebelum menjalankannya.
- Galat RMS digunakan untuk mengukur seberapa dekat perkiraan dengan nilai referensi pi. Semakin kecil galat RMS, semakin baik perkiraan tersebut.
