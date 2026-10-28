# ikursus

**Projek demo dari kelas latihan PHP, Laravel dan Flutter.**

Setiap repo dalam akaun ini dibina secara langsung (live coding) bersama peserta semasa latihan anjuran **[Sitehandy Solutions](https://sitehandy.com)** dan **JomTraining**, dikendalikan oleh **Mohd Amirol Zolkifli**.

![PHP](https://img.shields.io/badge/PHP-777BB4?logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?logo=laravel&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?logo=flutter&logoColor=white)

---

## 🔎 Cari repo kelas anda

Setiap repo dinamakan ikut projek yang dibina, dan deskripsinya menyatakan **nama kursus, penganjur/agensi dan tarikh**. Contoh:

> `jpm-helpdesk` — Kursus Laravel JPM 10 Jul - 13 Jul 2023

Cara paling cepat:

| Nak cari ikut... | Pautan |
|---|---|
| Laravel | [Lihat repo Laravel](https://github.com/ikursus?tab=repositories&q=laravel) |
| PHP (semua) | [Lihat repo PHP](https://github.com/ikursus?tab=repositories&language=php) |
| Flutter / Dart | [Lihat repo Flutter](https://github.com/ikursus?tab=repositories&language=dart) |
| Tahun kursus | Taip tahun dalam kotak carian, contoh [`2023`](https://github.com/ikursus?tab=repositories&q=2023) |
| Agensi / penganjur | Taip nama agensi, contoh [`INTAN`](https://github.com/ikursus?tab=repositories&q=intan) |

Tak jumpa? Tanya jurulatih anda nama repo yang digunakan semasa kelas.

---

## ⚠️ Baca dulu sebelum guna

Repo di sini adalah **kod demo untuk tujuan pembelajaran**, bukan sistem siap guna.

- Kod ditulis untuk menerangkan konsep dalam masa kelas yang terhad. Ada bahagian yang sengaja dipermudahkan (validation, keselamatan, error handling).
- Repo **tidak diselenggara** selepas kelas tamat. Versi framework mengikut tarikh kursus, jadi repo lama mungkin perlukan versi PHP yang lebih lama.
- **Jangan deploy ke production** tanpa semakan dan pengukuhan keselamatan.

---

## 🚀 Cara jalankan repo demo

### Projek Laravel

```bash
git clone https://github.com/ikursus/<nama-repo>.git
cd <nama-repo>
composer install
cp .env.example .env
php artisan key:generate
# kemas kini tetapan DB_* dalam fail .env dahulu
php artisan migrate --seed
php artisan serve
```

> Repo lama (2017–2019) guna versi Laravel yang lebih awal. Semak `require.php` dalam `composer.json` untuk tahu versi PHP yang serasi.

### Projek Flutter

```bash
git clone https://github.com/ikursus/<nama-repo>.git
cd <nama-repo>
flutter pub get
flutter run
```

---

## 🙋 Untuk peserta

- Nak sambung latihan sendiri? **Fork** repo kelas anda dan teruskan di akaun GitHub anda.
- Repo ini ialah rekod kelas, jadi **pull request tidak digabungkan**.
- Jumpa pepijat atau ada soalan berkaitan kelas? Buka **Issue** dalam repo berkenaan.

---

## 🏢 Anjurkan latihan untuk organisasi anda

Latihan dijalankan untuk agensi kerajaan, universiti dan syarikat, secara in-house atau awam.
Hubungi **[Sitehandy Solutions](https://sitehandy.com)** untuk maklumat kursus dan sebut harga.
