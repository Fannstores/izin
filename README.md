# REPO IZIN - Fannstores/izin
**Repo untuk lisensi IP VPS script FTS-Tunnel Fantunel Store**

Repo ini berisi database IP dan admin yang digunakan untuk validasi lisensi script.

## Struktur
```
main/
├── ip         # Daftar IP dengan format: ### USERNAME YYYY-MM-DD IP
└── admin      # Daftar admin yang berhak regis
```

## Format File `main/ip`
```
### NAMA_PEMILIK TANGGAL_EXPIRED IP_VPS
```
Contoh:
```
### admin 2027-12-31 0.0.0.0
### reyz 2026-10-20 192.168.1.100
```

## Format File `main/admin`
```
NAMA_PEMILIK TANGGAL_EXPIRED IP_VPS
```
Contoh:
```
admin 2027-12-31 0.0.0.0
```

## Cara Update
Repo ini diupdate otomatis lewat fitur **Regis IP** di menu script.
Atau bisa langsung push perubahan ke `main/ip` dan `main/admin`.

---
© 2026 Fantunel Store. All Rights Reserved.
