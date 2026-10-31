# QA Manual Testing – Kartu Ngobrol

Pengujian manual pada website https://kartu-ngobrol.vercel.app

## Ruang Lingkup
5 halaman/fitur: Main Page, Sendirian, Berdua, Rame-rame, dan Custom.

## Pendekatan
- Jenis testing: functional, UI, negative testing
- Browser: Chrome
- Tools: Google Sheets

## Ringkasan Hasil
- Total test case: 23
- Eksekusi pertama: 11 Pass, 12 Fail
- Temuan: 8 (5 bug, 2 improvement, 1 change request)
- Severity bug: 1 High, 3 Medium, 1 Low
- Status akhir: semua temuan Closed dan semua test case Pass setelah retest

## Temuan Utama
| ID | Judul | Severity |
|---|---|---|
| BUG-001 | Timer berjalan padahal kartu belum dibuka | High |
| BUG-003 | Tombol "Kartu berikutnya" bisa diklik sebelum waktu habis | Medium |
| BUG-004 | Sisa kartu salah (14, seharusnya 15) | Medium |
| BUG-005 | Ringkasan menghitung 1 kartu dibuka padahal 0 | Medium |
| BUG-002 | Animasi time bar tidak konsisten (panjang teks tombol) | Low |

## Isi Repository
- [Test Cases](test-cases.csv)
- [Bug Reports](bug-reports.csv)

## Spreadsheet Asli
[(QA Kartu Ngobrol - Google Sheets)](https://docs.google.com/spreadsheets/d/1C4C1GA8JTUYYNjbbU_-R4Eu8Q_6LGJQY-Jg8mFKAzV8/edit?usp=sharing)
