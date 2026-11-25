# JTI Vote App

Aplikasi **E-Voting Android** berbasis **Java** untuk pemilihan di lingkungan **Jurusan Teknologi Informasi (JTI), Politeknik Negeri Jember**.

![Android](https://img.shields.io/badge/Android-SDK_24--33-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![Java](https://img.shields.io/badge/Java-8-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Retrofit](https://img.shields.io/badge/Networking-Retrofit_2_%26_Volley-0284C7?style=for-the-badge)

---

## Fitur Utama

- **Login Pengguna**: Autentikasi pemilih terhubung ke server REST API (`LoginActivity`, `LoginApiService`, `ModelLogin`, `LoginResponse`).
- **Dashboard Pemilihan**: Menu utama pemilihan kandidat yang mudah diakses (`DashboardActivity`).
- **3 Kategori Voting JTI**:
  - Pemilihan **Kahim** (`KahimActivity`)
  - Pemilihan **Kahmjti** (`KahmjtiActivity`)
  - Pemilihan **Kajur** (`KajurActivity`)
- **Pengaturan Akun**: Pengelolaan profil dan logout pemilih (`SettingsActivity`).

---

## Tech Stack

| Komponen | Teknologi |
| :--- | :--- |
| Bahasa & Platform | Java 8, Android Native (`minSdk 24`, `targetSdk 33`) |
| UI Components | AndroidX AppCompat, Material Components, ConstraintLayout |
| HTTP & JSON | Retrofit 2 (`converter-gson`), Volley |
| Build System | Gradle Kotlin DSL (`build.gradle.kts`) |

---

## Cara Menjalankan

1. Clone repository ini:
   ```bash
   git clone https://github.com/happiestvrgo/JTIVoteApp.git
   ```
2. Buka folder proyek menggunakan **Android Studio**.
3. Pastikan URL endpoint server API pada `ApiClass.java` sudah sesuai dengan alamat backend aktif.
4. Tunggu proses *Gradle Sync* selesai, lalu klik **Run** pada emulator atau perangkat Android (minimal Android 7.0 / API 24).
