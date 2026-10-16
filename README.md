# ECLIPSE: REALMS OF RUIN — RPG Prototype

Prototype RPG dark fantasy bergaya pixel dengan UI mobile-friendly. Saat ini karakter/monster menggunakan ikon emoji sebagai placeholder visual, supaya project ringan dan mudah dikembangkan.

## Fitur yang sudah ada
- Profil karakter: nama, ras, class
- Level, EXP, HP, MP, Gold, dan poin atribut
- Atribut STR, VIT, AGI, INT
- Pertarungan monster, skill Shadow Slash, serangan balik monster
- Loot, potion, equipment, inventory
- Quest dan penyimpanan lokal otomatis (localStorage)
- Layout responsif untuk layar HP

## Cara mencoba
Buka `index.html` di browser. Progress tersimpan di browser/perangkat yang sama.

## Menjadikan APK Android
Project ini adalah versi web awal. Untuk APK, gunakan Capacitor:
1. Buat project Node.js dan letakkan `index.html` di folder `www/`.
2. Jalankan `npm init -y`
3. Jalankan `npm install @capacitor/core @capacitor/cli`
4. Jalankan `npx cap init "Eclipse RPG" "com.eclipse.realms" --web-dir=www`
5. Jalankan `npm install @capacitor/android`
6. Jalankan `npx cap add android`
7. Jalankan `npx cap sync android`
8. Buka folder Android di Android Studio atau gunakan workflow build Android yang sudah kamu pakai.

Catatan: ini prototype awal, belum berisi sprite pixel khusus, peta eksplorasi berjalan, sistem akun online, atau multiplayer. Semua data tersimpan lokal di browser/aplikasi.
