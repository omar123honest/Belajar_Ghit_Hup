# 📘 Belajar Git & GitHub

Repository ini dibuat untuk belajar dan latihan menggunakan **Git** dan **GitHub**, mulai dari clone, branching, commit, push, sampai pull request dan cara menyelesaikan merge conflict.

Cocok buat kamu yang baru mulai belajar Git, lagi ikut bootcamp, atau butuh catatan singkat & gampang dipahami tentang alur kerja Git sehari-hari.

---

## 📑 Daftar Perintah Git

| No | Perintah | Penjelasan | Contoh |
|----|----------|------------|--------|
| 1 | **Git Clone** | Meng-copy / mengambil (nge-pull) project dari remote/GitHub agar bisa dikerjakan di komputer lokal masing-masing. | `git clone <url-repository-nya>` |
| 2 | **Git Pull** | Fitur untuk menarik pekerjaan/perubahan yang ada di remote ke komputer lokal. Ketika kita mau memasukkan perubahan ke repository GitHub, kita nggak bisa langsung push paksa — biasanya perlu selaraskan dulu (pull) sebelum push, apalagi kalau kerja bareng tim. | `git pull origin <nama-branch>` |
| 3 | **Git Status** | Memeriksa kondisi file — melihat file mana yang sudah siap di-push dan mana yang belum di-commit. | `git status` |
| 4 | **Git Add & Git Commit** | Langkah wajib sebelum push. Setelah ngedit kode, kamu pilih file mana yang mau disimpan perubahannya (`git add`), lalu "kunci" perubahan itu dengan pesan singkat tentang apa yang dikerjakan (`git commit`). | `git add .` (masukin semua file yang berubah)<br>`git commit -m "Pesan singkat, misal: benerin tombol login"` |
| 5 | **Git Push** | Kode yang sudah di-commit tadi masih ada di laptop kamu doang. Supaya teman satu tim bisa lihat dan kodenya masuk ke GitHub, kamu harus nge-push kodenya ke internet. | `git push origin <nama-branch-kamu>` |
| 6 | **Git Branch** | Fitur untuk membuat dan mengelola cabang (branch) kerja, supaya perubahan/fitur baru nggak langsung nyampur ke branch utama (`main`). Berguna biar kerjaan banyak orang nggak saling tabrakan. | `git branch <nama-branch>` atau `git switch -c <nama-branch>` |
| 7 | **Pull Request (PR) / Merge Request (MR)** | Ngajuin proposal ke tim: "Eh, kerjaanku udah kelar nih, tolong dicek dong. Kalau oke, gabungin ke project utama ya." | Lewat UI GitHub/GitLab, atau `gh pr create` |
| 8 | **Merge Conflict** | Terjadi kalau ada perubahan yang tabrakan antar branch. Git bakal nandain file yang bentrok pakai simbol `<<<<<<<`, `=======`, `>>>>>>>`. Tinggal buka filenya, hapus simbol-simbol itu, lalu pilih manual kode mana yang mau dipertahankan. Setelah itu, save, `git add`, dan `git commit` lagi. | - |
| 9 | **Rangkuman Alur Kerja Harian (Workflow)** | Urutan kerja yang biasa dipakai sehari-hari. | Lihat bagian di bawah 👇 |

---

## 🔄 Rangkuman Alur Kerja Sehari-hari (Workflow)

```bash
git pull                          # biar kerjaan kamu up-to-date sama remote
# ...edit kode...
git add .                         # masukin perubahan ke staging area
git commit -m "nambahin fitur A"  # simpan perubahan secara lokal
git push origin nama-branch       # upload ke GitHub
```

Setelah itu:
1. Bikin **Pull Request** di GitHub untuk minta review dari teman tim.
2. Kalau ada tabrakan kode, benerin dulu **Merge Conflict**-nya.
3. Setelah disetujui, PR di-merge ke branch utama (`main`).

---

## 📂 Struktur Repository

Repo ini berisi file-file latihan seputar praktik Git & GitHub (branch, commit, PR, dsb):

| File / Folder | Keterangan |
|---|---|
| `Git.txt` | Catatan alur kerja Git tim (workflow ringkas) |
| `Tes 1` | Latihan dasar: belajar git & github, coba branch baru + PR |
| `test page`, `test_page2`, `test-123` | File latihan commit & push |
| `omar_g1`, `omar_p1`, `omar_p2`, `omar_test` | File latihan personal (branching/commit) |
| `altop2`, `altop_test` | File latihan personal (branching/commit) |
| `malik` | File latihan personal (branching/commit) |
| `tes branch git` | Latihan membuat & bekerja dengan branch |
| `Belajar-Githup-bersama-kink-liktop/` | Folder tambahan terkait materi belajar |

---
