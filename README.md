# MerbutGames – İndirme Merkezi

Android APK ve Windows kurulum dosyaları GitHub Releases bölümünde yayımlanır.

**İndirmeler:** https://github.com/6161bayramts-ctrl/MerbutGames-Indir/releases/latest

## İlk kurulum (bir kez yapılır)

Bu depo, uygulamaları özel kaynak deposundan derler. Kaynak kodunu herkese açmadan derleme yapabilmek için:

1. GitHub'da **Settings → Developer settings → Personal access tokens → Fine-grained tokens** bölümünden yeni bir token oluştur.
2. Repository access kısmında yalnızca `6161bayramts-ctrl/merbuthansosyal` deposunu seç.
3. Repository permissions altında **Contents: Read-only** ver. Başka izin verme.
4. Token'ı oluşturduktan sonra kopyala. Token'ı sohbet mesajına, dosyaya veya koda yazma.
5. Bu indirme deposunda **Settings → Secrets and variables → Actions → New repository secret** yolunu aç.
6. Secret name alanına tam olarak `MERBUT_SOURCE_TOKEN` yaz; secret value alanına token'ı yapıştır ve kaydet.

## Yeni sürüm yayımlama

1. **Actions → Publish MerbutGames downloads → Run workflow** bölümünü aç.
2. Sürüm alanına benzersiz bir etiket gir (ör. `1.0.0-test1`).
3. Run workflow düğmesine bas.
4. Android ve Windows derlemeleri tamamlanınca dosyalar Releases sayfasında yayımlanır.

> İlk Android paketi test amaçlı debug APK'dır. Kalıcı imzalama anahtarıyla imzalanmış üretim APK'sı değildir; ileride gerçek sürüm güncellemeleri için Android release imzalama kurulmalıdır.

> APK ve Windows uygulamasının cihazlarda kurulup çalıştığı henüz ayrıca doğrulanmış değildir. Yayınlanan her sürüm gerçek cihazda test edilmelidir.
