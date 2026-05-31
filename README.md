# glxgears - Pastel Sky Edition ⚙️☁️

Modifikasi estetis dari aplikasi klasik `glxgears`, dirancang khusus untuk mempercantik *ricing* desktop Linux. 

*(Ganti baris ini: Hapus tulisan ini, lalu drag & drop file gambar screenshot desktopmu ke sini)*

## ✨ Fitur Utama
* **Palet Warna Pastel:** Menggunakan perpaduan *Pastel Pink*, *Sky Blue*, *Soft White*, dan *Lilac*.
* **4 Roda Gigi (Gears):** Tambahan satu roda gigi ekstra dengan rasio putaran matematika presisi agar tersinkronisasi dan saling menggigit sempurna.
* **Latar Transparan:** Memaksa X11/XWayland menggunakan jendela ARGB 32-bit (Alpha Channel) untuk memberikan efek latar belakang kaca gelap transparan.

## 🛠️ Cara Build & Run
Pastikan kamu sudah menginstal pustaka *compiler* dasar (`build-essential`, `libgl1-mesa-dev`, `libx11-dev`). Lalu jalankan perintah kompilasi ini di terminal:

```bash
gcc glxgears.c -o glxgears_kustom -lGL -lX11 -lm
./glxgears_kustom
