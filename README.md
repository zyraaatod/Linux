
<div align="center">

# 🐧 Linux

### Linux Documentation & Technical Notes

**Learn · Explore · Build · Secure**

Kumpulan dokumentasi, catatan teknis, konfigurasi, dan eksperimen Linux yang disusun untuk mendukung proses belajar dan pengembangan sistem.

<br>

[![Repository](https://img.shields.io/badge/Repository-Linux-181717?style=flat-square&logo=github)](https://github.com/zyraaatod/Linux)
[![Platform](https://img.shields.io/badge/Platform-Linux-FCC624?style=flat-square&logo=linux&logoColor=black)](https://www.kernel.org/)
[![Shell](https://img.shields.io/badge/Shell-Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)](https://www.gnu.org/software/bash/)

<br>

[Overview](#-overview) · [Documentation](#-documentation) · [Commands](#-linux-command-reference) · [Security](#-security) · [Contributing](#-contributing)

</div>

---

## 📌 Overview

Repository ini menjadi ruang dokumentasi untuk mempelajari Linux, memahami cara kerja sistem, menyimpan referensi perintah, serta mengembangkan keterampilan teknis melalui praktik.

Materi dirancang agar dapat dikembangkan secara bertahap, mulai dari dasar penggunaan terminal hingga administrasi sistem, scripting, jaringan, dan keamanan.

### Objectives

- **Learn** — memahami konsep dan komponen dasar Linux.
- **Document** — menyimpan catatan teknis secara terstruktur.
- **Automate** — mempelajari scripting untuk menyederhanakan pekerjaan.
- **Troubleshoot** — memahami metode diagnosis dan pemecahan masalah.
- **Secure** — mempelajari konfigurasi dan praktik keamanan sistem.

## 📚 Documentation

| Category | Description |
|:--|:--|
| 🐧 Linux Fundamentals | Struktur direktori, permission, proses, dan manajemen pengguna. |
| ⌨️ Command Line | Perintah terminal, pipeline, redirection, dan utilitas sistem. |
| ⚙️ System Administration | Pengelolaan layanan, konfigurasi, dan pemeliharaan sistem. |
| 🌐 Networking | Pemeriksaan konektivitas, DNS, port, dan diagnostik jaringan. |
| 🧩 Shell Scripting | Otomasi menggunakan Bash dan pengolahan tugas berulang. |
| 🔍 Troubleshooting | Teknik analisis masalah dan pemeriksaan log sistem. |
| 🛡️ Cybersecurity | Hardening, audit konfigurasi, dan pemeriksaan keamanan defensif. |

> Kategori ini merupakan roadmap dokumentasi. Materi aktual mengikuti file yang tersedia di repository.

## 🗂️ Repository Structure

Struktur yang direkomendasikan untuk menjaga dokumentasi tetap konsisten:

```text
Linux/
├── README.md
├── docs/
│   ├── fundamentals.md
│   ├── commands.md
│   ├── networking.md
│   ├── administration.md
│   ├── scripting.md
│   ├── security.md
│   └── troubleshooting.md
├── scripts/
│   └── README.md
├── configs/
│   └── README.md
└── LICENSE
```

Direktori di atas adalah rancangan struktur, bukan daftar file yang dipastikan sudah ada.

## 💻 Linux Command Reference

Berikut beberapa perintah dasar untuk pemeriksaan sistem.

### System Information

```bash
# Informasi kernel dan arsitektur
uname -a

# Informasi distribusi
cat /etc/os-release

# Direktori kerja saat ini
pwd
```

### Filesystem

```bash
# Tampilkan file, termasuk file tersembunyi
ls -lah

# Periksa kapasitas filesystem
df -h

# Periksa ukuran direktori
du -sh .
```

### Processes & Resources

```bash
# Tampilkan proses
ps aux

# Pantau proses secara interaktif
top

# Periksa penggunaan memori
free -h
```

### Networking

```bash
# Periksa konfigurasi alamat IP
ip addr

# Periksa tabel routing
ip route

# Periksa resolusi DNS
getent hosts example.com
```

Ketersediaan beberapa perintah bergantung pada distribusi, paket yang terpasang, dan lingkungan eksekusi.

## 🛡️ Security Principles

Keamanan merupakan bagian penting dalam administrasi sistem Linux.

- Terapkan prinsip **least privilege**.
- Perbarui sistem dan paket secara berkala.
- Periksa permission file dan direktori.
- Jangan menyimpan kredensial atau token di dalam source code.
- Validasi script sebelum menjalankannya.
- Lakukan pengujian keamanan hanya pada sistem sendiri atau sistem yang memiliki izin pengujian.

## 🧪 Practical Learning

Pendekatan belajar yang disarankan:

1. **Understand** — pelajari konsep sebelum menjalankan perintah.
2. **Practice** — uji perintah di lingkungan yang aman.
3. **Observe** — amati output, log, dan perubahan sistem.
4. **Document** — catat proses, hasil, dan kendala.
5. **Improve** — perbaiki dokumentasi berdasarkan hasil pengujian.

Setiap tutorial sebaiknya menyertakan tujuan, kebutuhan awal, langkah praktik, contoh output, dan catatan keamanan jika relevan.

## 🤝 Contributing

Kontribusi terbuka untuk perbaikan dokumentasi, koreksi teknis, contoh penggunaan, dan penambahan tutorial.

1. Fork repository.
2. Buat branch untuk perubahan.
3. Lakukan perubahan secara terfokus.
4. Periksa kembali akurasi dan format Markdown.
5. Ajukan Pull Request dengan ringkasan yang jelas.

Contoh penamaan branch:

```bash
git switch -c docs/improve-linux-guide
```

## 📜 License

Lisensi mengikuti file `LICENSE` yang berlaku di repository. Jika file tersebut belum tersedia, tentukan lisensi sebelum menyatakan bahwa konten dapat digunakan ulang.

## 🔗 References

- [Linux Kernel](https://www.kernel.org/)
- [GNU Project](https://www.gnu.org/)
- [GNU Bash Reference Manual](https://www.gnu.org/software/bash/manual/)
- [Git Documentation](https://git-scm.com/doc/)
- [GitHub Markdown Guide](https://docs.github.com/en/get-started/writing-on-github)

---

<div align="center">

**Maintained by [@zyraaatod](https://github.com/zyraaatod)**

*Documenting knowledge. Building skills. Exploring Linux.*

</div>
