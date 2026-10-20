# Suit Web — Batu Gunting Kertas

Game suit (batu-gunting-kertas) melawan komputer langsung di browser. Pemain memilih ✊ batu, ✌️ gunting, atau 🖐 kertas, komputer memilih acak, lalu hasil tiap ronde dan skor kumulatif (menang/kalah/seri) ditampilkan. Ada tombol reset skor.

## Cara Menjalankan

Buka file-nya langsung di browser:

```bash
xdg-open index.html
```

Atau pakai server lokal:

```bash
cd suit-web
python3 -m http.server 8000
# lalu buka http://localhost:8000 di browser
```

## Cara Main

1. Klik salah satu emoji pilihan.
2. Lihat pilihan komputer dan hasil ronde.
3. Klik **Reset Skor** untuk mengulang skor dari nol.
