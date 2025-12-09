📘 README Project 2 — Hidden & Security (CMD)

# 🔐 Project 2 – Hidden & Security (Command Prompt)

## 🎯 Tujuan
Menggunakan Command Prompt untuk:
- Menyembunyikan file
- Mengunci file dengan atribut (read-only)
- Mengembalikan file seperti semula
- Mengecek status atribut file

Semua dilakukan menggunakan perintah attrib.

---

# 🟦 1. Membuat Folder dan File Contoh
```cmd
mkdir SecurityFiles
cd SecurityFiles
echo Ini file rahasia > secret.txt


---

🟦 2. Menyembunyikan File (Hidden)

attrib +h secret.txt

✔ File tidak terlihat di File Explorer (kecuali show hidden aktif)


---

🟦 3. Mengunci File (Read-Only + System)

attrib +s +r secret.txt

Atribut yang ditambahkan:

+s → System (file dianggap file sistem)

+r → Read-only (tidak bisa di-edit)



---

🟦 4. Mengecek Status Atribut

attrib secret.txt

Contoh output:

SHR   secret.txt

Artinya file mempunyai atribut:

S = System

H = Hidden

R = Read-only



---

🟦 5. Menampilkan Kembali File & Menghapus Kunci

Untuk mengembalikan file seperti semula:

attrib -h -s -r secret.txt

✔ File kembali terlihat
✔ Bisa dibuka dan diedit lagi


---

🟦 6. Penggunaan Tambahan (Opsional)

Menyembunyikan semua file dalam folder:

attrib +h .

Menampilkan semua file:

attrib -h .

Menampilkan semua atribut file:

attrib


---

🟩 Kesimpulan Project

✔ Berhasil membuat file
✔ Berhasil menyembunyikan file
✔ Berhasil memberi atribut Secure (System + Read-Only)
✔ Berhasil mengembalikan file seperti semula
✔ Sudah dicek menggunakan perintah attrib


---

👤 Created By

Nama: MOHAMAD ALFATIR ANGE
NIM 05301425082
Kelas: SI D 25
Tahun: 2025
