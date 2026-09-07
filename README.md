BICIRIK ANDROID UYGULAMASI
=========================

Uygulama adı: Bıcırık
Paket adı: org.bicirik.app
Site: https://bicirik.org/
Minimum Android: Android 7.0 (API 24)

APK OLUSTURMA
1. Android Studio'yu açın.
2. Open düğmesiyle Bicirik-Android-App klasörünü seçin.
3. Android Studio gerekli Gradle ve Android SDK bileşenlerini tamamlasın.
4. Build > Generate App Bundles or APKs > Generate APKs yolunu açın.
5. Test APK'sı app/build/outputs/apk/debug/app-debug.apk konumunda oluşur.

GITHUB ILE OTOMATIK APK
1. Bu klasörün içeriğini GitHub'da boş bir depoya yükleyin.
2. Deponun Actions bölümünü açın.
3. "Bicirik APK Olustur" iş akışını seçin.
4. Run workflow düğmesine basın.
5. İşlem tamamlandığında sayfanın Artifacts bölümündeki bicirik-apk paketini indirin.
6. Paketin içinden bicirik-debug.apk dosyası çıkar.

YAYIN ICIN IMZALI APK
1. Build > Generate Signed App Bundle or APK seçeneğini açın.
2. APK seçin.
3. Create new ile bir .jks imza anahtarı oluşturun.
4. Anahtar dosyasını ve şifresini güvenli biçimde yedekleyin.
5. release sürümünü oluşturun.
6. Çıkan dosyayı bicirik.apk olarak adlandırıp sitenizde downloads klasörüne yükleyin.

SITEYE INDIRME BAGLANTISI
<a href="downloads/bicirik.apk" class="btn btn-primary" download>Android Uygulamasını İndir</a>

NOTLAR
- APK, güvenli HTTPS bağlantısıyla bicirik.org sitesini uygulama içinde açar.
- Site dışı WhatsApp, telefon, harita ve sosyal medya bağlantıları ilgili uygulamalarda açılır.
- İnternet olmadığında özel uyarı ekranı gösterilir.
- Android uygulama dosyaları yalnızca Android Studio ile derlenebilir.
- Yeni sürümlerde versionCode değerini mutlaka artırın.
