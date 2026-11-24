# AI IPTV PRO v2 (Android 14 / Android TV box)

Özellikler: M3U + Xtream (canlı, film, dizi), kumanda (D-pad) uyumlu arayüz, Türkçe sesli komut,
yapay zekâ destekli Türkçe dublaj (İngilizce -> Türkçe), otomatik bağlantı düzeltme, dahili tarayıcı
(sayfadaki video akışını yakalayıp kendi oynatıcısında açar).

## APK'yı üretmek (kod bilmeden) — GitHub ile
1. github.com'da ücretsiz hesap aç, yeni bir **private** depo oluştur.
2. Bu klasörün içindekileri (zip'in içi) depoya yükle ("Add file > Upload files").
   `.github/workflows/build.yml` dosyasının da yüklendiğinden emin ol.
3. Depoda **Actions** sekmesi > "Build APK" > bitince "AI_IPTV_PRO_apk" çıktısını indir (içinde .apk var).
4. APK'yı USB bellek / "Send files to TV" ile kutuya at, kur. (Eski sürüm kurulu ve imza hatası verirse önce eskisini kaldır.)

## Alternatif: Android Studio
Klasörü "Open" ile aç, Gradle 8.9 / JDK 17 seç, Build > Build APK(s).

## İlk ayar
Ayarlar'dan M3U linki **veya** Xtream bilgisi gir. Dublaj ve akıllı komutlar için:
- STT (Whisper uyumlu) adres + anahtar (OpenAI veya Groq)
- Claude API anahtarı
