# Black-Box Testing – Selenium IDE

## 🧪 Tujuan
Melakukan pengujian fungsional (black-box) pada aplikasi berbasis Flask untuk fitur:
- Login
- Menambahkan data (Item)
- Logout

## ⚙️ Tools
- **Selenium IDE (Chrome Extension)**
- **GitHub Codespaces (Flask app)**
- **URL Publik:** https://username-5000.app.github.dev

## 📋 Langkah Pengujian

### 1. Login
- Input username dan password
- Klik tombol "Login"
- Hasil: Redirect ke dashboard

### 2. Tambah Data
- Klik tombol "Tambah Item"
- Isi form: Nama dan Deskripsi
- Klik tombol "Submit"
- Hasil: Muncul data baru di list item

### 3. Logout
- Klik tombol "Logout"
- Hasil: Redirect ke halaman login

## ✅ Hasil Pengujian

| Skenario       | Status | Bukti              |
|----------------|--------|--------------------|
| Login          | PASS   | `SeleniumIDE.side` |
| Tambah Item    | PASS   |                    |
| Logout         | PASS   |                    |

📸 Bukti screenshot:
![Hasil Pengujian](SeleniumIDENadhifa.png)

## 📎 Lampiran
- `SeleniumIDE.side`: Skrip pengujian otomatisasi Selenium
- `SeleniumIDENadhifa.png`: Tangkapan layar hasil uji
