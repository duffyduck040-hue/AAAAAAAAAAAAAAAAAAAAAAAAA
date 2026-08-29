# Death Valley Radar V6

Kurulum: ZIP'i açın ve `index.html` dosyasını tarayıcıda açın. GitHub Pages / Netlify / Vercel gibi statik hosting'e de doğrudan yüklenebilir.

## Sayaçlar
- Ancient Tree: 3.600 s / 1 saat
- Ancient Mine: 4.200 s / 1 saat 10 dk
- Ancient Stone: 3.000 s / 50 dk
- Ancient Excavation Site: 6.000 s / 1 saat 40 dk
- Ancient Beast: 28.800 s / 8 saat
- Ancient Basket: 4.800 s / 1 saat 20 dk
- Ancient Bush: 10.800 s / 3 saat

Sayaçlar tarayıcı `localStorage` içinde tutulur; sayfa yenilense bile geri sayım devam eder. `TOPLANDI · BAŞLAT` yalnızca seçilen Ancient için yeni respawn periyodu başlatır; diğer sayaçlara dokunmaz.

## Boss süreleri
Resmî kaynaklarda Death Valley bossları için tek tek sabit respawn süresi değil 1–5 saatlik aralık yayımlanmıştır. Bu nedenle paket, Deathlord / Dread Cyclops / Diviner / Flame Rock / Satyr için uydurma sabit süre göstermemekte ve `1–5 SAAT` doğrulanmış aralığını gösterir.
