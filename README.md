# 🗣️ SpeakFlow – Daily Speaking Challenge App (Bahasa Indonesia)

**SpeakFlow** adalah aplikasi pelatihan berbicara dalam Bahasa Indonesia yang membantu pengguna meningkatkan kemampuan public speaking melalui tantangan interaktif setiap hari. Dirancang untuk pelajar, profesional, maupun siapa saja yang ingin lebih percaya diri saat berbicara, SpeakFlow menyediakan berbagai jenis latihan seperti membaca, presentasi, dialog, wawancara, dan storytelling.

---

## 🚀 Fitur Utama

- **Tantangan Harian**: Topik dan latihan berbicara yang berbeda setiap hari.
- **Jenis Challenge Beragam**:
  - Reading (membaca dengan intonasi)
  - Presentation (menyampaikan ide)
  - Dialog (berbicara dengan karakter)
  - Interview (menjawab pertanyaan)
  - Storytelling (menceritakan pengalaman)
- **Rekaman Suara Langsung**: Pengguna merekam suara secara langsung melalui aplikasi.
- **Feedback Otomatis Berbasis AI**:
  - Kecepatan bicara (WPM)
  - Kejelasan dan kelancaran
  - Grammar (opsional)
  - Saran perbaikan
- **Riwayat dan Progres**: Pengguna dapat melihat perkembangan kemampuan mereka dari waktu ke waktu.

---

## 📱 Platform

Aplikasi ini dibangun dengan pendekatan **mobile-first**, dan akan tersedia di:
- Android
- iOS
- (Opsional) Web

---

## 🧱 Tech Stack

### Frontend:
- [React Native](https://reactnative.dev/) (via Expo)
- React Navigation
- Expo AV (untuk rekaman suara)

### Backend:
- [Node.js](https://nodejs.org/) + Express.js
- MongoDB (via Mongoose)
- Whisper API (OpenAI) / Deepgram (untuk Speech-to-Text)
- Firebase Auth (opsional)

---

## 📦 Struktur Fitur

- `/api/topic` → Mendapatkan topik & challenge harian
- `/api/challenge-step/:id` → Mendapatkan step dari challenge
- `/api/recording/upload` → Upload rekaman & analisis suara
- `/api/feedback/:step_id` → Mendapatkan feedback latihan
- `/api/history` → Riwayat latihan pengguna

---

## 🔒 Autentikasi

Pengguna dapat login menggunakan email/password atau Google login. Setiap sesi latihan terhubung dengan `user_id` untuk menyimpan hasil latihan dan feedback.

---

## 📄 Lisensi

Aplikasi ini dibangun sebagai proyek edukatif dan pengembangan keterampilan berbicara. Semua fitur dapat dikembangkan lebih lanjut untuk skala produksi.

---

> Dibuat oleh [Faried Yoga Prawira](https://github.com/fariedyoga) ✨