<div align="center">
  <img src="https://github.com/EasyTerminalOfficial/EasyTerminalOfficial/assets/12345678/your-logo-image-name.png" alt="EasyTerminal Logo" width="150"/>
  <h1>EasyTerminal</h1>
  <p>
    <strong>Sebuah Pusat Kendali Jarak Jauh (Remote Control Center) Multi-Protokol yang All-in-One</strong>
  </p>
  <p>
    Dirancang untuk Developer, Administrator Sistem, dan Penggemar Teknologi.
  </p>
  
  <p>
    <a href="https://github.com/EasyTerminalOfficial/EasyTerminal/stargazers"><img src="https://img.shields.io/github/stars/EasyTerminalOfficial/EasyTerminal?style=for-the-badge&logo=github&color=00FF41" alt="Stars"></a>
    <a href="https://github.com/EasyTerminalOfficial/EasyTerminal/network/members"><img src="https://img.shields.io/github/forks/EasyTerminalOfficial/EasyTerminal?style=for-the-badge&logo=github&color=00FF41" alt="Forks"></a>
    <a href="https://github.com/EasyTerminalOfficial/EasyTerminal/issues"><img src="https://img.shields.io/github/issues/EasyTerminalOfficial/EasyTerminal?style=for-the-badge&logo=github&color=FFD700" alt="Issues"></a>
    <a href="https://github.com/EasyTerminalOfficial/EasyTerminal/blob/main/LICENSE"><img src="https://img.shields.io/github/license/EasyTerminalOfficial/EasyTerminal?style=for-the-badge&color=888888" alt="License"></a>
  </p>
  
  <h4><a href="https://easyterminal.netlify.app/">Kunjungi Website Resmi</a></h4>

</div>

<p align="center">
  <img src="https://easyterminal.netlify.app/screenshot.png" alt="EasyTerminal Screenshot">
</p>

## 🚀 Tentang Proyek

EasyTerminal bukan sekadar terminal biasa. Ini adalah sebuah *control center* terintegrasi yang dibangun dengan Python dan Tkinter untuk menyediakan semua yang Anda butuhkan dalam mengelola server dan perangkat jarak jauh. Dengan menggabungkan terminal, file manager SFTP, dan dashboard monitoring dalam satu aplikasi, EasyTerminal bertujuan untuk menyederhanakan alur kerja Anda dan meningkatkan produktivitas.

Aplikasi ini lahir dari kebutuhan akan alat yang cepat, aman, dan kaya fitur tanpa harus berganti-ganti aplikasi.

## ✨ Fitur Utama

EasyTerminal dikemas dengan fitur-fitur canggih untuk memberikan pengalaman manajemen jarak jauh yang superior:

#### 1. Dukungan Multi-Protokol
- **SSH:** Terminal interaktif penuh, SFTP, dan eksekusi perintah.
- **Telnet:** Koneksi dasar untuk perangkat lama dan jaringan internal.
- **FTP/FTPS:** File manager untuk server FTP, dengan opsi koneksi aman (FTPS).
- **Serial (COM):** Terhubung langsung ke perangkat keras seperti mikrokontroler atau perangkat jaringan melalui port serial.

#### 2. Suite SSH & SFTP yang Powerfull
- **Dual-Pane File Manager:** Kelola file lokal dan remote secara berdampingan dengan mudah.
- **Operasi File Lengkap:** Upload, download, rename, hapus file/folder, dan buat file/folder baru.
- **Monitoring Server Real-Time:** Pantau penggunaan CPU, RAM, Suhu, dan Disk server Anda langsung dari UI.
- **Recycle Bin Cerdas:** Hapus file remote dengan aman! File akan dipindahkan ke *Recycle Bin* lokal di komputer Anda, bukan dihapus permanen.
- **Editor Teks Nano Terintegrasi:** Edit file di server langsung dari EasyTerminal menggunakan editor mirip `nano` tanpa harus membuka terminal.
- **Penampil Gambar:** Lihat gambar yang ada di server tanpa perlu mengunduhnya terlebih dahulu.

#### 3. Manajemen Terpusat
- **Manajer Koneksi:** Simpan, kelola, dan kelompokkan semua detail koneksi Anda.
- **Head-Command:** Jalankan satu perintah secara bersamaan di semua sesi SSH yang aktif. Sempurna untuk update massal atau pengecekan status.
- **Pemulihan Sesi:** Aplikasi akan mengingat sesi aktif Anda dan menawarkan untuk memulihkannya saat Anda membuka kembali.
- **Mode Idle Otomatis:** Sesi yang tidak aktif akan masuk ke mode hemat sumber daya untuk menjaga performa aplikasi.

#### 4. Keamanan Terjamin
- **Enkripsi Kredensial Lokal:** Semua *host*, *username*, dan *password* yang Anda simpan dienkripsi secara lokal menggunakan **AES-GCM**, sehingga aman dari akses yang tidak sah.

## 🛠️ Dibangun Dengan

* **Python:** Bahasa utama pengembangan.
* **Tkinter:** Untuk membangun antarmuka pengguna (GUI) yang responsif.
* **Paramiko:** Pustaka utama untuk implementasi protokol SSH dan SFTP.
* **Pillow (PIL):** Untuk fitur penampil gambar.
* **Pyserial:** Untuk fungsionalitas koneksi Serial.
* **Cryptography:** Untuk enkripsi data kredensial yang aman.

## 🏁 Memulai

Untuk menjalankan EasyTerminal di mesin lokal Anda, ikuti langkah-langkah sederhana ini.

1.  **Clone repositori**
    ```sh
    git clone [https://github.com/EasyTerminalOfficial/EasyTerminal.git](https://github.com/EasyTerminalOfficial/EasyTerminal.git)
    cd EasyTerminal
    ```
2.  **Buat dan aktifkan virtual environment**
    ```sh
    # Untuk MacOS/Linux
    python3 -m venv venv
    source venv/bin/activate
    
    # Untuk Windows
    python -m venv venv
    .\venv\Scripts\activate
    ```
3.  **Install dependensi**
    *(Pastikan Anda sudah membuat file `requirements.txt`)*
    ```sh
    pip install -r requirements.txt
    ```
4.  **Jalankan aplikasi**
    ```sh
    python Terminal.py
    ```

## 🤝 Kontribusi

**Kontribusi adalah hal yang membuat komunitas open source menjadi tempat yang luar biasa untuk belajar, menginspirasi, dan berkreasi. Setiap kontribusi Anda sangat kami hargai.**

Saat ini, EasyTerminal dikembangkan dan dikelola oleh satu orang. Sebagai **solo developer dari Indonesia**, saya membangun EasyTerminal karena kecintaan saya dalam membuat alat yang bermanfaat. Saya akan sangat senang jika ada developer lain yang mau bergabung untuk membuatnya menjadi lebih baik.

Bantuan Anda, baik dalam bentuk:
* Fitur baru
* Laporan bug
* Saran dan ide
* Perbaikan dokumentasi

akan sangat berarti. Jangan ragu untuk membuat *Fork* dan *Pull Request*!

1.  Fork Proyek ini
2.  Buat Branch Fitur Anda (`git checkout -b fitur/FiturLuarBiasa`)
3.  Commit Perubahan Anda (`git commit -m 'Menambahkan FiturLuarBiasa'`)
4.  Push ke Branch (`git push origin fitur/FiturLuarBiasa`)
5.  Buka sebuah Pull Request

## 📄 Lisensi

Didistribusikan di bawah Lisensi MIT. Lihat `LICENSE` untuk informasi lebih lanjut.

## 📬 Kontak

**EasyTerminal Official**

* **GitHub:** [https://github.com/EasyTerminalOfficial](https://github.com/EasyTerminalOfficial)
* **Website:** [https://easyterminal.netlify.app/](https://easyterminal.netlify.app/)
* **Telegram:** [https://t.me/EasyTerminalUpdate](https://t.me/EasyTerminalUpdate)

---
Dibuat dengan ❤️ di Indonesia.
