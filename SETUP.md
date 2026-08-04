# GitHub Profile — Stable Telemetry Upload

Bu sürümde dışarıdan yüklenen GitHub istatistik kartları tamamen kaldırıldı.
`0x07` bölümü artık repo içindeki `assets/telemetry-console.svg` dosyasını kullanır.

## Yüklenecekler

- `README.md`
- `assets/`
- `.github/` (snake kullanacaksan; zorunlu değil)

## Güncelleme

1. GitHub'da `beratergun/beratergun` reposunu aç.
2. `README.md` dosyasını aç ve kalem simgesine bas.
3. Eski kodun tamamını silip bu paketteki `README.md` kodunu yapıştır.
4. `assets` klasörüne `telemetry-console.svg` dosyasını yükle.
5. Commit message:
   `fix: replace broken stats cards with local telemetry console`

## Önemli

Yeni README içinde `github-readme-stats.vercel.app` veya başka bir dış istatistik kartı yoktur.
Bu nedenle GitHub Statistics / Top Languages şeklindeki kırık görseller görünmez.
