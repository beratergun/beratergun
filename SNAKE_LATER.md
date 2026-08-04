# Contribution Snake'ı Daha Sonra Açma

Şu anki temiz README'den kırık snake bölümü kaldırıldı.

Snake animasyonunu daha sonra açmak için:

1. `.github/workflows/snake.yml` dosyasını depoya yükle.
2. GitHub'da `Settings → Actions → General → Workflow permissions` bölümünden
   `Read and write permissions` seçeneğini aç.
3. `Actions → Generate contribution snake → Run workflow` yolunu çalıştır.
4. Workflow başarılı olduktan ve `output` dalı oluştuktan sonra README'ye snake bloğunu ekle.

Bu dosya oluşmadan README içinde snake bağlantısı kullanılırsa kırık görsel görünür.
