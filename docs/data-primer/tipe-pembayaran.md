---
sidebar_position: 3
description: Data tipe pembayaran
---

# Tipe Pembayaran

## Create

![Gambar](./img/tipe-pembayaran-001.png)

| Field           | Type     | Required | Example                              |
| --------------- | -------- | :------: | ------------------------------------ |
| Tahun Ajaran    | Dropdown |    ✅    | 2025/2026                            |
| Nama            | String   |    ✅    | Wakaf Wajib                          |
| Tipe Pembayaran | Dropdown |    ✅    | Pembayaran Awal Semester (Lunas)     |
| Nominal         | Integer  |    ✅    | 6000000                              |
| Jatuh Tempo     | Date     |    ✅    | bulan/tanggal/tahun (**12/30/2025**) |

## Read

![Gambar](./img/tipe-pembayaran-002.png)

## Update

Ubah data jika diperlukan. Hati-hati dalam mengubah data tipe pembayaran. Pembayaran yang telah dilakukan tidak ikut berubah dengan perubahan ini.

![Gambar](./img/tipe-pembayaran-003.png)

## Delete

Demi kenyamanan dan keamanan sistem, maka data tipe pembayaran yang telah diinput, tidak bisa dihapus. Karena dapat menyebabkan kerusakan data lain yang berhubungan dengan tipe pembayaran tersebut.

![Gambar](./img/tipe-pembayaran-004.png)
