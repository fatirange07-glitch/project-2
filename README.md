NAMA : MOHAMAD ALFATIR ANGE
NIM  :05301425082
MATKUL: SISTEM OPERASI


# 🌐 Project 2 – Network Diagnostic Tool (CMD)

## 🎯 Tujuan
Melakukan diagnosa jaringan menggunakan perintah Command Prompt untuk:
- Mengecek konfigurasi jaringan
- Mengetes koneksi internet
- Mengetes DNS
- Melacak rute internet
- Melihat koneksi aktif

Project ini penting untuk memahami dasar troubleshooting jaringan komputer.

---

# 🟦 1. Membuka Command Prompt
```cmd
Windows + R → cmd → Enter


---

🟦 2. Mengecek Konfigurasi Jaringan

Perintah:

ipconfig /all

Fungsi:

Menampilkan IP Address

Subnet mask

Default gateway

DNS server

MAC address

Status adapter


Hasilnya menunjukkan seluruh detail jaringan yang aktif.


---

🟦 3. Mengetes Koneksi Internet (Ping DNS Google)

Perintah:

ping 8.8.8.8

Jika muncul:

Reply from 8.8.8.8

✔ Berarti koneksi internet stabil.


---

🟦 4. Tes DNS (Ubah Domain ke IP)

Perintah:

ping google.com

Fungsi:

Mengecek apakah DNS berjalan normal

Komputer harus bisa mengubah nama google.com menjadi IP address



---

🟦 5. Melacak Jalur Internet (Traceroute)

Perintah:

tracert google.com

Fungsi:

Melihat rute/hop dari komputer → router → ISP → server Google

Mengetahui lokasi terjadinya delay jaringan


Output berupa daftar hop seperti:

1   2 ms   1 ms  192.168.1.1
2  15 ms  12 ms  10.10.0.1
...


---

🟦 6. Melihat Koneksi Aktif (Netstat)

Perintah:

netstat -an

Fungsi:

Menampilkan seluruh koneksi aktif

Menunjukkan port yang digunakan komputer

Melihat status seperti ESTABLISHED, LISTENING, TIME_WAIT



---

🟩 Kesimpulan Project 2

Dalam Project ini telah dilakukan: ✔ Pemeriksaan konfigurasi IP
✔ Tes ping ke DNS Google
✔ Tes DNS menggunakan domain
✔ Traceroute ke server Google
✔ Pemeriksaan koneksi & port aktif menggunakan netstat

Semua langkah ini digunakan untuk analisis dan troubleshooting jaringan dasar.

