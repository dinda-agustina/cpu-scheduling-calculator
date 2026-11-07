# CPU Scheduler — FCFS & SRTF

Aplikasi berbasis web untuk simulasi dan perhitungan algoritma penjadwalan CPU menggunakan metode First-Come, First-Served (FCFS) dan Shortest Remaining Time First (SRTF).

## 👥 Identitas Kelompok 3

| No. | Nama | NIM |
|---|---|---|
| 1 | Dinda Agustina Hidayani | 2501020004 |
| 2 | Fahrizal Hariwira Winata | 2501020005 |
| 3 | M. Naufal Abdurrafi | 2501020014 |
| 4 | Mutia Khairunnisa | 2501020042 |
| 5 | Akhdan Dana Diaksa | 2501020048 |

## 📌 Deskripsi Aplikasi

CPU Scheduler merupakan aplikasi web interaktif yang dirancang untuk menyimulasikan dan menghitung algoritma penjadwalan CPU. Pengguna dapat memasukkan data proses, memilih algoritma, serta melihat hasil perhitungan dalam bentuk tabel dan Gantt Chart.

## 🎯 Tujuan Pembuatan

1. Memenuhi Tugas 2 mata kuliah Sistem Operasi pada materi algoritma penjadwalan CPU.
2. Memahami logika, proses perhitungan, dan implementasi algoritma FCFS dan SRTF ke dalam source code berbasis HTML, CSS, dan JavaScript.

## ⚙️ Pengertian Algoritma

**1. First-Come, First-Served (FCFS)**

FCFS adalah algoritma penjadwalan CPU yang menjalankan proses berdasarkan urutan waktu kedatangannya (*Arrival Time*). Algoritma ini bersifat **non-preemptive**, sehingga proses yang sedang berjalan akan diselesaikan terlebih dahulu sebelum proses berikutnya dijalankan.

**2. Shortest Remaining Time First (SRTF)**

SRTF adalah algoritma penjadwalan CPU yang bersifat **preemptive**, yaitu proses dapat dihentikan sementara jika terdapat proses baru dengan sisa waktu eksekusi (*Remaining Time*) yang lebih kecil. CPU akan selalu memilih proses dengan sisa waktu eksekusi paling sedikit.

## 📐 Rumus Perhitungan

| Komponen | Rumus |
|---|---|
| Completion Time (CT) | Waktu proses selesai dieksekusi |
| Turnaround Time (TAT) | `CT - AT` |
| Waiting Time (WT) | `TAT - BT` |
| Rata-rata TAT | `Total TAT / Jumlah Proses` |
| Rata-rata WT | `Total WT / Jumlah Proses` |

**Keterangan:**
- AT (*Arrival Time*): Waktu kedatangan proses.
- BT (*Burst Time*): Waktu yang dibutuhkan proses untuk dieksekusi.
- CT (*Completion Time*): Waktu selesainya proses.
- TAT (*Turnaround Time*): Total waktu sejak proses datang hingga selesai.
- WT (*Waiting Time*): Total waktu proses menunggu dalam antrean.

Seluruh waktu menggunakan satuan milidetik (ms).

## 🚀 Cara Penggunaan

1. Pilih algoritma penjadwalan CPU, yaitu FCFS atau SRTF.
2. Masukkan nilai *Arrival Time* (AT) dan *Burst Time* (BT) pada tabel input.
3. Gunakan tombol **Tambah Proses** atau **Hapus** untuk mengatur jumlah proses.
4. Klik tombol **Hitung** untuk menjalankan simulasi.
5. Lihat hasil perhitungan CT, TAT, WT, nilai rata-rata, dan visualisasi urutan eksekusi proses pada Gantt Chart.

## 📝 Penutup

Aplikasi CPU Scheduler dibuat sebagai media pembelajaran untuk memahami dan membandingkan algoritma penjadwalan CPU FCFS dan SRTF. Melalui aplikasi ini, diharapkan pengguna dapat memahami proses eksekusi, perhitungan waktu, serta perbedaan karakteristik kedua algoritma secara lebih mudah dan interaktif.

---

**Kelompok 3 — Tugas 2 Sistem Operasi**
