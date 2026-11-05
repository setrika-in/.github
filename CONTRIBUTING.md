# Berkontribusi

## Branch
Cabang dari `main` dengan nama `jenis/deskripsi-singkat`, misalnya `feat/laporan-shift` atau `fix/pin-login`.

## Commit
Pakai prefix conventional commit: `feat`, `fix`, `docs`, `chore`, `refactor`, `test`, `ci`. Contoh: `fix: tolak PIN kosong`. Jangan tambahkan baris atribusi AI (mis. Co-Authored-By) di commit atau PR.

## Alur PR
1. Buka PR dengan template yang tersedia.
2. Review sendiri diff-nya, lalu tulis verdict di baris terakhir (`CR: APPROVE` atau `CR: DECISION NEEDED: ...`).
3. Merge setelah CI hijau.

## Secret
Jangan pernah commit secret atau file `.env`. Kalau terlanjur, anggap secret itu bocor dan ganti.

## Deploy
Deploy lewat repo [infra-setrika-in](https://github.com/setrika-in/infra-setrika-in), bukan manual dari repo lain.
