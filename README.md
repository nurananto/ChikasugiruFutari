# Chikasugiru Futari

> Aoi dan Akane itu anak SMA, rumah mereka berdua sebelahan. Sejak lahir, bangun, tidur, bahkan mandi pun selalu bareng. Nyebut mereka “teman kecil” aja udah kurang greget—ini keseharian para kuso-najimi. Lebih dari teman kecil, tapi belum pacaran. Mereka semua sudah melakukan apapun bareng, hingga mereka udah kelihatan kayak suami istri. Romcom kuso-najimi dengan jarak diantara mereka berdua yang udah ngga biasa—dimulai!

---

## Info

| | |
|---|---|
| Judul | Chikasugiru Futari |
| Judul Alternatif | 近すぎる2人 |
| Author | Yamiara |
| Tipe | Manga (Hitam Putih) |
| Status | Ongoing |
| Genre | Shounen · Comedy · Romance · School Life |
| Chapter | 6 chapter |

## Link

- [MangaDex](https://mangadex.org/title/c679bf28-e054-4bb7-93e6-18c089ee79f1/chikasugiru-futari)
- [Raw](https://comic-walker.com/detail/KC_008362_S?episodeType=first)

---

## Struktur

```
ChikasugiruFutari/
├── manga-config.json     # Metadata manga
├── manga.json            # Data chapter (auto-generated)
├── manga-automation.js   # Script automation
├── encrypt-manifest.js   # Script enkripsi manifest
├── daily-views.json      # Data views harian
└── <chapter>/
    └── manifest.json     # Daftar halaman (encrypted)
```

## Automation

Semua proses berjalan otomatis via GitHub Actions:

1. Push chapter baru (folder + manifest.json)
2. `encrypt-manifest.yml` — enkripsi manifest
3. `manga-automation.yml` — regenerate manga.json
4. Trigger rebuild ke website utama
5. `sync-cover.yml` — sinkronisasi cover dari website

---

Bagian dari [Nurananto Scanlation](https://nuranantoscans.my.id)