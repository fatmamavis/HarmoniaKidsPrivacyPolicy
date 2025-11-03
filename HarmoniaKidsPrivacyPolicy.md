# GİZLİLİK POLİTİKASI
## Yasal Çerçeve
Bu uygulama Apple'ın Standart Lisans Sözleşmesi (EULA) kapsamındadır: 
https://www.apple.com/legal/internet-services/itunes/dev/stdeula/

Aşağıdaki ek şartlar bu EULA'yı tamamlar:

**Son Güncelleme: 3 Kasım 2025**

## 1. Giriş
Harmonia Kids ("biz," "bizim," veya "şirketimiz") kullanıcılarımızın, özellikle çocukların gizliliğini korumaya önem vermektedir. Bu gizlilik politikası, terapötik masal uygulamamızı kullanırken bilgilerin nasıl toplandığını, kullanıldığını ve korunduğunu açıklar.

**Çocuk Gizliliği Taahhüdü**: Uygulamamız COPPA (Children's Online Privacy Protection Act) ve GDPR (General Data Protection Regulation) dahil olmak üzere uluslararası çocuk gizlilik yasalarına tam uyum sağlar.

## 2. Yaşa Göre Veri Toplama Politikası

### 2.1 13 Yaş Altı Kullanıcılar (Çocuklar)
**Çocuklarınızın gizliliğini korumak bizim önceliğimizdir.**

13 yaş altı kullanıcılar için:
* ❌ **Kişisel bilgi toplanmaz** (isim, e-posta, telefon, konum vb.)
* ❌ **Reklam takibi yapılmaz** (IDFA/Android ID toplanmaz)
* ❌ **Davranışsal pazarlama yoktur**
* ✅ **Sadece anonim çökme raporları** (uygulama iyileştirme için)
* ✅ **Kullanıcı ID'leri hashlenmiş** (şifrelenmiş) formatta
* ✅ **Ebeveyn onayı olmadan veri paylaşımı yapılmaz**

**Teknik Korumalar:**
* Firebase Analytics: KAPALI
* AppsFlyer: Child Mode (reklam tanımlayıcıları devre dışı)
* ATT Dialog (iOS 14+): Gösterilmez
* Google Analytics: Veri toplama devre dışı

### 2.2 13 Yaş Üstü Kullanıcılar
13 yaş ve üzeri kullanıcılar için sınırlı veri toplama:
* ✅ **Anonim kullanım istatistikleri** (uygulama iyileştirme için)
* ✅ **Çökme raporları** (teknik sorun çözümü için)
* ✅ **Analitik veriler** (Google Analytics - anonim)
* ✅ **Pazarlama performans verileri** (AppsFlyer - anonim)
* ⚠️ **ATT izni** (iOS 14+, isteğe bağlı)

**Önemli Not:** Tüm kullanıcı ID'leri SHA-256 algoritması ile hashlenmiş (şifrelenmiş) formatta saklanır. Hiçbir koşulda düz metin olarak kişisel bilgi toplanmaz.

### 2.3 Bilinmeyen Yaş Kullanıcıları
Yaş bilgisi bilinmeyen kullanıcılar, güvenlik önlemi olarak **13 yaş altı kullanıcı gibi** işlem görür ve maksimum koruma sağlanır.

## 3. Toplanan Bilgiler (Detaylı)

### 3.1 Zorunlu Bilgiler (Tüm Kullanıcılar)
* **Hesap Kimlik Doğrulama**: Google veya Apple hesabınız üzerinden giriş yapıldığında, sadece kimlik doğrulama için gereken minimum bilgiler (kullanıcı ID'si - hashlenmiş) alınır.
* **Yaş Kategorisi**: Yaş grubuna uygun içerik sunmak ve çocuk gizlilik yasalarına uyum sağlamak için yaş bilgisi toplanır. **Not:** Tam doğum tarihi değil, sadece yaş kategorisi saklanır.

### 3.2 Teknik Veriler (Tüm Kullanıcılar)
* **Çökme Verileri**: Uygulama performansını iyileştirmek için Firebase Crashlytics aracılığıyla toplanan teknik hatalar. Bu veriler:
  - Kişisel bilgilerinizi içermez
  - Cihaz ID'nizi içermez
  - Sadece hata logları ve teknik detaylar
* **Cihaz Bilgileri**: İşletim sistemi versiyonu, uygulama versiyonu (cihaz modeli veya seri numarası DEĞİL)

### 3.3 İsteğe Bağlı Veriler (Sadece 13+ Yaş)
* **Uygulama Kullanım Verileri**: 
  - Hangi içeriklerin görüntülendiği
  - Ne kadar süre içerik izlendiği
  - Hangi özelliklerin kullanıldığı
  - **Not:** Bu veriler anonim ve toplanmış (aggregated) formdadır
  
* **Analitik Veriler** (Google Analytics):
  - Sayfa görüntülemeleri
  - Oturum süreleri
  - Uygulama içi navigasyon
  - **Not:** IP adresi anonimleştirilir, tam konum toplanmaz
  
* **Pazarlama Verileri** (AppsFlyer):
  - Reklam kampanya performansı
  - Uygulama yüklenme kaynağı (attribution)
  - Kullanıcı etkileşim metrikleri
  - **Not:** Kişiselleştirilmiş reklam profili oluşturulmaz

## 4. Bilgilerin Kullanımı

### 4.1 Kullanım Amaçları
Toplanan bilgileri **yalnızca** şu amaçlarla kullanıyoruz:

**Tüm Kullanıcılar İçin:**
* ✅ Hesap oluşturma ve kimlik doğrulama
* ✅ Yaş grubuna uygun içerik sunma (0-3, 4-7, 8-11, 12-14 yaş)
* ✅ Teknik sorunları tespit etme ve çözme
* ✅ Uygulama performansını iyileştirme
* ✅ Güvenlik ve dolandırıcılık önleme

**Sadece 13+ Yaş İçin:**
* ✅ Kullanıcı deneyimini iyileştirme
* ✅ İçerik önerilerini geliştirme
* ✅ Pazarlama kampanyalarının etkinliğini ölçme (anonim)

### 4.2 Kullanılmayan Amaçlar
Verileriniz **ASLA** şu amaçlarla kullanılmaz:
* ❌ Üçüncü taraflara satış
* ❌ Kişiselleştirilmiş reklam gösterimi (behavioral advertising)
* ❌ Profil oluşturma (profiling)
* ❌ Otomatik karar verme
* ❌ Spam veya istenmeyen pazarlama

## 5. Veri Koruma ve Güvenlik

### 5.1 Güvenlik Önlemleri
* **Şifreleme**: Tüm kullanıcı ID'leri SHA-256 algoritması ile hashlenmiş
* **Güvenli İletişim**: HTTPS/SSL sertifikası ile şifreli veri iletimi
* **Erişim Kontrolü**: Sınırlı personel erişimi, iki faktörlü kimlik doğrulama
* **Düzenli Denetim**: Güvenlik açıkları için düzenli taramalar
* **Veri Minimizasyonu**: Sadece gerekli veriler toplanır

### 5.2 Veri Saklama Konumu
* **Firebase**: Google Cloud Platform (AB ve ABD sunucuları)
* **RevenueCat**: AWS (Amazon Web Services)
* **AppsFlyer**: Çok bölgeli sunucular (GDPR uyumlu)

Tüm üçüncü taraf hizmetler GDPR ve COPPA gerekliliklerini karşılar.

## 6. Veri Saklama ve Silme

### 6.1 Veri Saklama Süreleri
* **Aktif Hesaplar**: Hesabınız aktif olduğu sürece veriler saklanır
* **Çökme Raporları**: 90 gün sonra otomatik silinir
* **Analitik Veriler**: Toplanmış (aggregated) form, 14 ay
* **Kullanıcı ID'leri**: Hashlenmiş form, hesap silininceye kadar

### 6.2 Hesap Silme Hakkı
Kullanıcılar **istediği zaman** hesabını silebilir:

**Silme Adımları:**
1. Uygulama içinden Profil sayfasına gidin
2. "Hesabımı Sil" seçeneğine tıklayın
3. Onay verin

**Silme Sonrası:**
* ✅ Tüm kişisel veriler 30 gün içinde kalıcı olarak silinir
* ✅ Hashlenmiş kullanıcı ID'leri sistemlerden kaldırılır
* ✅ İşlem geri alınamaz
* ⚠️ **Önemli:** Abonelikler otomatik iptal edilmez! App Store/Play Store'dan ayrıca iptal etmelisiniz.

### 6.3 Pasif Hesap Politikası
* **2 yıl** süre ile giriş yapılmayan hesaplar "pasif hesap" olarak işaretlenir
* Pasif hesaplar 2 yıl sonunda silinme hakkımız vardır
* Silme işlemi öncesinde bildirim yapma zorunluluğumuz yoktur
* **Öneri:** Hesabınızı kullanmıyorsanız manuel olarak silin

## 7. Üçüncü Taraf Hizmetleri

### 7.1 Kimlik Doğrulama Hizmetleri
**Google Sign-In ve Apple Sign In with Apple**
* **Toplanan Veri**: Kullanıcı ID (hashlenmiş), e-posta (opsiyonel)
* **Amaç**: Güvenli giriş ve hesap yönetimi
* **Gizlilik Politikası**: 
  - Google: https://policies.google.com/privacy
  - Apple: https://www.apple.com/legal/privacy/

### 7.2 Analitik Hizmetleri

**Google Analytics (Firebase)**
* **Yaş Kısıtı**: Sadece 13+ yaş
* **Toplanan Veri**: Anonim sayfa görüntülemeleri, oturum süreleri
* **IP Anonimleştirme**: Aktif
* **Gizlilik Politikası**: https://firebase.google.com/support/privacy
* **Opt-Out**: iOS/Android sistem ayarlarından "Ad Tracking" kapatılabilir

**Firebase Crashlytics**
* **Yaş Kısıtı**: Tüm kullanıcılar (anonim)
* **Toplanan Veri**: Çökme logları, teknik hatalar
* **Kişisel Bilgi**: İçermez
* **Gizlilik Politikası**: https://firebase.google.com/support/privacy

### 7.3 Pazarlama ve Attribution Hizmetleri

**AppsFlyer**
* **Yaş Kısıtı**: Sadece 13+ yaş
* **Child Mode**: 13 yaş altı için otomatik aktif
* **Toplanan Veri**: 
  - 13+ yaş: Reklam performansı, yüklenme kaynağı
  - <13 yaş: Sadece anonim install sayısı (IDFA/Android ID YOK)
* **Gizlilik Politikası**: https://www.appsflyer.com/privacy-policy/
* **Opt-Out**: ATT dialog ile (iOS), sistem ayarlarından (Android)

### 7.4 Abonelik ve Ödeme Hizmetleri

**RevenueCat**
* **Yaş Kısıtı**: Tüm kullanıcılar
* **Toplanan Veri**: Abonelik durumu, satın alma geçmişi (hashlenmiş user ID ile)
* **Kişisel Bilgi**: İçermez
* **Ödeme Bilgileri**: App Store/Play Store tarafından işlenir, bize iletilmez
* **Gizlilik Politikası**: https://www.revenuecat.com/privacy

**Apple App Store & Google Play Store**
* Tüm ödeme işlemleri platform sağlayıcıları tarafından gerçekleştirilir
* Kredi kartı/banka bilgileri bizimle paylaşılmaz
* **Gizlilik Politikaları**: 
  - Apple: https://www.apple.com/legal/privacy/
  - Google: https://policies.google.com/privacy

### 7.5 Veri Güvenliği Önlemleri (Üçüncü Taraflar)
* ✅ **GDPR Uyumlu**: Tüm hizmetler GDPR gerekliliklerini karşılar
* ✅ **COPPA Sertifikalı**: Çocuk verisi işleme sertifikaları mevcut
* ✅ **Veri İşleme Anlaşmaları**: Yazılı DPA (Data Processing Agreement) imzalanmış
* ✅ **Düzenli Denetim**: Yıllık güvenlik denetimleri

**Kullanıcı Hakkı**: Bu hizmetleri kullanmadan önce ilgili gizlilik politikalarını inceleme hakkına sahipsiniz.

## 8. Çocuk Gizliliği (COPPA/GDPR-K Uyumu)

### 8.1 Ebeveyn Onayı
* **13 yaş altı çocuklar**: Ebeveyn onayı olmadan kişisel veri toplanmaz
* **Ebeveyn Kontrolleri**: Çocuğun hesabını yönetme ve silme hakkı
* **İletişim**: Ebeveynler şu e-postadan bize ulaşabilir: privacy@harmoniakids.com

### 8.2 Çocuk Verilerinin Korunması
* ❌ Kişisel bilgi toplama yok
* ❌ Davranışsal profilleme yok
* ❌ Targeted advertising yok
* ✅ Age-appropriate content (yaşa uygun içerik)
* ✅ Parental controls (ebeveyn kontrolleri)

### 8.3 COPPA Uyum Tablosu

| Gereksinim | Durum | Açıklama |
|------------|-------|----------|
| Ebeveyn bildirimi | ✅ | Bu politikada açıklanmış |
| Veri toplama sınırı | ✅ | Minimum veri toplama |
| Ebeveyn onayı | ✅ | Kişisel veri toplanmıyor (onay gerektiren yok) |
| Veri erişimi | ✅ | Ebeveynler iletişime geçebilir |
| Veri silme | ✅ | Hesap silme özelliği mevcut |
| Güvenlik | ✅ | SHA-256 hashing, HTTPS |

## 9. Uluslararası Veri Aktarımı

### 9.1 Veri Aktarım Mekanizmaları
Verileriniz aşağıdaki mekanizmalarla korunarak aktarılır:
* **AB-ABD Veri Aktarımı**: EU-US Data Privacy Framework
* **Standart Sözleşme Maddeleri**: GDPR Madde 46 uyumlu SCC'ler
* **Adequacy Decisions**: AB Komisyonu onaylı ülkeler

### 9.2 Veri İşleme Konumları
* **Birincil Sunucular**: Avrupa Birliği (Google Cloud EU)
* **Yedek Sunucular**: Amerika Birleşik Devletleri (GDPR korumalı)
* **CDN**: Küresel (Cloudflare - GDPR uyumlu)

## 10. Kullanıcı Hakları (GDPR)

### 10.1 Temel Haklarınız
1. **Erişim Hakkı**: Hangi verilerinizin toplandığını öğrenme
2. **Düzeltme Hakkı**: Yanlış bilgileri düzeltme
3. **Silme Hakkı**: "Unutulma hakkı" - tüm verileri silme
4. **Veri Taşınabilirliği**: Verilerinizi dışa aktarma
5. **İşlemeye İtiraz**: Belirli veri işlemelerini reddetme
6. **Otomatik Karar Vermeye İtiraz**: Profilleme reddi

### 10.2 Haklarınızı Kullanma
**İletişim Kanalları:**
* E-posta: privacy@harmoniakids.com
* Konu: "GDPR Kullanıcı Hakkı Talebi"
* Yanıt Süresi: 30 gün içinde

**Gerekli Bilgiler:**
* Hesap bilgileriniz (kullanıcı adı/e-posta)
* Talep türü (erişim, silme, düzeltme vb.)
* Kimlik doğrulama (güvenlik için)

### 10.3 Denetim Makamlarına Şikayet
Haklarınızın ihlal edildiğini düşünüyorsanız:
* **Türkiye**: Kişisel Verileri Koruma Kurumu (KVKK) - https://www.kvkk.gov.tr
* **AB**: Ülkenizdeki veri koruma otoritesi
* **ABD**: Federal Trade Commission (FTC) - https://www.ftc.gov

## 11. Çerez Politikası (Web Versiyonu İçin - Varsa)

**Not:** Mobil uygulama çerez kullanmaz. Web versiyonu varsa:

* **Zorunlu Çerezler**: Giriş oturumu, güvenlik
* **Analitik Çerezler**: Google Analytics (opsiyonel, reddedilebilir)
* **Pazarlama Çerezleri**: Kullanılmamaktadır

## 12. Değişiklikler ve Güncellemeler

### 12.1 Politika Güncellemeleri
* Bu gizlilik politikası gerektiğinde güncellenebilir
* **Önemli Değişiklikler**: Uygulama içi bildirim ile duyurulur
* **Küçük Değişiklikler**: "Son Güncelleme" tarihi değiştirilir
* **Güncelleme Geçmişi**: Bu sayfanın altında

### 12.2 Değişiklik Bildirimi
Önemli değişiklikler durumunda:
* ✅ Uygulama içi popup bildirimi
* ✅ E-posta bildirimi (kayıtlı e-posta varsa)
* ✅ 30 gün önceden duyuru

**Kullanıcı Hakkı**: Değişiklikleri kabul etmiyorsanız hesabınızı silebilirsiniz.

## 13. Sorumluluk Reddi

### 13.1 Resmi Olmayan Kaynaklardan İndirme
⚠️ **ÖNEMLİ UYARI:**

Harmonia Kids uygulaması **yalnızca** resmi mağazalardan indirilmelidir:
* ✅ Apple App Store
* ✅ Google Play Store

**Resmi olmayan kaynaklardan** (APK dosyaları, üçüncü taraf mağazalar, jailbreak/root cihazlar) indirme durumunda:
* ❌ Güvenlik garantisi verilmez
* ❌ Veri koruma garantisi verilmez
* ❌ Uygulama işlevselliği garanti edilmez
* ❌ Güncellemeler sağlanmaz
* ❌ Teknik destek verilmez

**Riskler:** Güvenlik açıkları, kötü amaçlı yazılım, veri hırsızlığı, cihaz hasarı

**Sorumluluk:** Resmi olmayan kaynaklardan kaynaklanan tüm sorunlar kullanıcının sorumluluğundadır.

### 13.2 Bağlantılı Üçüncü Taraf Siteleri
Uygulama içinde üçüncü taraf web sitelerine bağlantılar olabilir. Bu sitelerin gizlilik politikalarından sorumlu değiliz.

## 14. İletişim

### 14.1 Gizlilik Soruları
Gizlilik politikası hakkında sorularınız için:

**E-posta**: privacy@harmoniakids.com  
**Konu**: "Gizlilik Politikası Sorusu"  
**Yanıt Süresi**: 5 iş günü içinde

### 14.2 Veri Koruma Sorumlusu (DPO)
**İsim**: [DPO İsmi - eklenecek]  
**E-posta**: dpo@harmoniakids.com  
**Rol**: GDPR uyumu ve kullanıcı haklarının korunması

### 14.3 Genel İletişim
**Şirket**: Harmonia Kids  
**Web**: https://harmoniakids.com  
**Destek**: support@harmoniakids.com

## 15. Güncelleme Geçmişi

| Tarih | Versiyon | Değişiklikler |
|-------|----------|---------------|
| 3 Kasım 2025 | 3.0 | iOS 14+ ATT desteği, yaşa göre dinamik veri toplama detayları |
| 25 Ekim 2025 | 2.0 | AppsFlyer child mode açıklamaları |
| 16 Temmuz 2025 | 1.0 | İlk yayın |

---

# PRIVACY POLICY
## Legal Framework
This application is subject to Apple's Standard License Agreement (EULA): 
https://www.apple.com/legal/internet-services/itunes/dev/stdeula/

The following additional terms supplement this EULA:

**Last Updated: November 3, 2025**

## 1. Introduction
Harmonia Kids ("we," "our," or "our company") is committed to protecting the privacy of our users, especially children. This privacy policy explains how information is collected, used, and protected when using our therapeutic storytelling application.

**Child Privacy Commitment**: Our application fully complies with international child privacy laws, including COPPA (Children's Online Privacy Protection Act) and GDPR (General Data Protection Regulation).

## 2. Age-Based Data Collection Policy

### 2.1 Users Under 13 Years Old (Children)
**Protecting your children's privacy is our priority.**

For users under 13 years old:
* ❌ **No personal information collected** (name, email, phone, location, etc.)
* ❌ **No ad tracking** (no IDFA/Android ID collection)
* ❌ **No behavioral marketing**
* ✅ **Only anonymous crash reports** (for app improvement)
* ✅ **User IDs are hashed** (encrypted format)
* ✅ **No data sharing without parental consent**

**Technical Protections:**
* Firebase Analytics: DISABLED
* AppsFlyer: Child Mode (advertising identifiers disabled)
* ATT Dialog (iOS 14+): Not shown
* Google Analytics: Data collection disabled

### 2.2 Users 13 Years and Older
Limited data collection for users 13 years and older:
* ✅ **Anonymous usage statistics** (for app improvement)
* ✅ **Crash reports** (for technical problem solving)
* ✅ **Analytics data** (Google Analytics - anonymous)
* ✅ **Marketing performance data** (AppsFlyer - anonymous)
* ⚠️ **ATT permission** (iOS 14+, optional)

**Important Note:** All user IDs are stored in hashed (encrypted) format using SHA-256 algorithm. Personal information is never collected in plain text.

### 2.3 Users with Unknown Age
Users with unknown age information are treated as **users under 13** as a security measure, with maximum protection provided.

## 3. Information Collected (Detailed)

### 3.1 Required Information (All Users)
* **Account Authentication**: When signing in through Google or Apple account, only minimum information required for authentication (user ID - hashed) is obtained.
* **Age Category**: Age information is collected to provide age-appropriate content and comply with child privacy laws. **Note:** Only age category is stored, not full birth date.

### 3.2 Technical Data (All Users)
* **Crash Data**: Technical errors collected through Firebase Crashlytics to improve app performance. This data:
  - Does not contain personal information
  - Does not contain device ID
  - Only error logs and technical details
* **Device Information**: Operating system version, app version (NOT device model or serial number)

### 3.3 Optional Data (Only 13+ Years)
* **Application Usage Data**: 
  - Which content is viewed
  - How long content is watched
  - Which features are used
  - **Note:** This data is in anonymous and aggregated form
  
* **Analytics Data** (Google Analytics):
  - Page views
  - Session durations
  - In-app navigation
  - **Note:** IP address is anonymized, full location not collected
  
* **Marketing Data** (AppsFlyer):
  - Advertising campaign performance
  - App installation source (attribution)
  - User interaction metrics
  - **Note:** No personalized advertising profile created

## 4. Use of Information

### 4.1 Usage Purposes
We use collected information **only** for the following purposes:

**For All Users:**
* ✅ Account creation and authentication
* ✅ Providing age-appropriate content (0-3, 4-7, 8-11, 12-14 years)
* ✅ Detecting and solving technical issues
* ✅ Improving app performance
* ✅ Security and fraud prevention

**Only for 13+ Years:**
* ✅ Improving user experience
* ✅ Developing content recommendations
* ✅ Measuring marketing campaign effectiveness (anonymous)

### 4.2 Purposes Not Used
Your data is **NEVER** used for:
* ❌ Selling to third parties
* ❌ Showing personalized advertisements (behavioral advertising)
* ❌ Profiling
* ❌ Automated decision making
* ❌ Spam or unwanted marketing

## 5. Data Protection and Security

### 5.1 Security Measures
* **Encryption**: All user IDs hashed with SHA-256 algorithm
* **Secure Communication**: Encrypted data transmission with HTTPS/SSL certificate
* **Access Control**: Limited personnel access, two-factor authentication
* **Regular Audit**: Regular scans for security vulnerabilities
* **Data Minimization**: Only necessary data collected

### 5.2 Data Storage Location
* **Firebase**: Google Cloud Platform (EU and US servers)
* **RevenueCat**: AWS (Amazon Web Services)
* **AppsFlyer**: Multi-regional servers (GDPR compliant)

All third-party services meet GDPR and COPPA requirements.

## 6. Data Storage and Deletion

### 6.1 Data Retention Periods
* **Active Accounts**: Data stored as long as account remains active
* **Crash Reports**: Automatically deleted after 90 days
* **Analytics Data**: Aggregated form, 14 months
* **User IDs**: Hashed form, until account deletion

### 6.2 Right to Account Deletion
Users can delete their account **at any time**:

**Deletion Steps:**
1. Go to Profile page within the app
2. Click "Delete My Account" option
3. Confirm

**After Deletion:**
* ✅ All personal data permanently deleted within 30 days
* ✅ Hashed user IDs removed from systems
* ✅ Process is irreversible
* ⚠️ **Important:** Subscriptions are not automatically cancelled! Must be cancelled separately from App Store/Play Store.

### 6.3 Inactive Account Policy
* Accounts not accessed for **2 years** are marked as "inactive accounts"
* We reserve the right to delete inactive accounts after 2 years
* No obligation to provide notification before deletion
* **Recommendation:** If not using your account, delete it manually

## 7. Third-Party Services

### 7.1 Authentication Services
**Google Sign-In and Apple Sign In with Apple**
* **Data Collected**: User ID (hashed), email (optional)
* **Purpose**: Secure login and account management
* **Privacy Policy**: 
  - Google: https://policies.google.com/privacy
  - Apple: https://www.apple.com/legal/privacy/

### 7.2 Analytics Services

**Google Analytics (Firebase)**
* **Age Restriction**: Only 13+ years
* **Data Collected**: Anonymous page views, session durations
* **IP Anonymization**: Active
* **Privacy Policy**: https://firebase.google.com/support/privacy
* **Opt-Out**: Can disable "Ad Tracking" from iOS/Android system settings

**Firebase Crashlytics**
* **Age Restriction**: All users (anonymous)
* **Data Collected**: Crash logs, technical errors
* **Personal Information**: Does not contain
* **Privacy Policy**: https://firebase.google.com/support/privacy

### 7.3 Marketing and Attribution Services

**AppsFlyer**
* **Age Restriction**: Only 13+ years
* **Child Mode**: Automatically active for under 13
* **Data Collected**: 
  - 13+ years: Advertising performance, installation source
  - <13 years: Only anonymous install count (NO IDFA/Android ID)
* **Privacy Policy**: https://www.appsflyer.com/privacy-policy/
* **Opt-Out**: Via ATT dialog (iOS), system settings (Android)

### 7.4 Subscription and Payment Services

**RevenueCat**
* **Age Restriction**: All users
* **Data Collected**: Subscription status, purchase history (with hashed user ID)
* **Personal Information**: Does not contain
* **Payment Information**: Processed by App Store/Play Store, not transmitted to us
* **Privacy Policy**: https://www.revenuecat.com/privacy

**Apple App Store & Google Play Store**
* All payment transactions processed by platform providers
* Credit card/bank information not shared with us
* **Privacy Policies**: 
  - Apple: https://www.apple.com/legal/privacy/
  - Google: https://policies.google.com/privacy

### 7.5 Data Security Measures (Third Parties)
* ✅ **GDPR Compliant**: All services meet GDPR requirements
* ✅ **COPPA Certified**: Child data processing certificates available
* ✅ **Data Processing Agreements**: Written DPA signed
* ✅ **Regular Audit**: Annual security audits

**User Right**: You have the right to review relevant privacy policies before using these services.

## 8. Child Privacy (COPPA/GDPR-K Compliance)

### 8.1 Parental Consent
* **Children under 13**: No personal data collected without parental consent
* **Parental Controls**: Right to manage and delete child's account
* **Contact**: Parents can reach us at: privacy@harmoniakids.com

### 8.2 Protection of Children's Data
* ❌ No personal information collection
* ❌ No behavioral profiling
* ❌ No targeted advertising
* ✅ Age-appropriate content
* ✅ Parental controls

### 8.3 COPPA Compliance Table

| Requirement | Status | Explanation |
|------------|--------|-------------|
| Parental notification | ✅ | Explained in this policy |
| Data collection limit | ✅ | Minimum data collection |
| Parental consent | ✅ | No personal data collected (no consent required) |
| Data access | ✅ | Parents can contact |
| Data deletion | ✅ | Account deletion feature available |
| Security | ✅ | SHA-256 hashing, HTTPS |

## 9. International Data Transfers

### 9.1 Data Transfer Mechanisms
Your data is transferred with protection through the following mechanisms:
* **EU-US Data Transfer**: EU-US Data Privacy Framework
* **Standard Contractual Clauses**: GDPR Article 46 compliant SCCs
* **Adequacy Decisions**: Countries approved by EU Commission

### 9.2 Data Processing Locations
* **Primary Servers**: European Union (Google Cloud EU)
* **Backup Servers**: United States (GDPR protected)
* **CDN**: Global (Cloudflare - GDPR compliant)

## 10. User Rights (GDPR)

### 10.1 Your Basic Rights
1. **Right to Access**: Learn what data is collected
2. **Right to Rectification**: Correct incorrect information
3. **Right to Erasure**: "Right to be forgotten" - delete all data
4. **Data Portability**: Export your data
5. **Object to Processing**: Refuse certain data processing
6. **Object to Automated Decision Making**: Profiling refusal

### 10.2 Exercising Your Rights
**Contact Channels:**
* Email: privacy@harmoniakids.com
* Subject: "GDPR User Rights Request"
* Response Time: Within 30 days

**Required Information:**
* Your account information (username/email)
* Request type (access, deletion, correction, etc.)
* Identity verification (for security)

### 10.3 Complaint to Supervisory Authorities
If you believe your rights have been violated:
* **Turkey**: Personal Data Protection Authority (KVKK) - https://www.kvkk.gov.tr
* **EU**: Data protection authority in your country
* **US**: Federal Trade Commission (FTC) - https://www.ftc.gov

## 11. Cookie Policy (For Web Version - If Available)

**Note:** Mobile app does not use cookies. If web version exists:

* **Essential Cookies**: Login session, security
* **Analytics Cookies**: Google Analytics (optional, can be refused)
* **Marketing Cookies**: Not used

## 12. Changes and Updates

### 12.1 Policy Updates
* This privacy policy may be updated as necessary
* **Major Changes**: Announced via in-app notification
* **Minor Changes**: "Last Updated" date changed
* **Update History**: At the bottom of this page

### 12.2 Change Notification
In case of major changes:
* ✅ In-app popup notification
* ✅ Email notification (if registered email exists)
* ✅ 30 days advance notice

**User Right**: If you do not accept changes, you can delete your account.

## 13. Disclaimer

### 13.1 Downloads from Unofficial Sources
⚠️ **IMPORTANT WARNING:**

Harmonia Kids application should **only** be downloaded from official stores:
* ✅ Apple App Store
* ✅ Google Play Store

In case of downloading from **unofficial sources** (APK files, third-party stores, jailbreak/root devices):
* ❌ No security guarantee
* ❌ No data protection guarantee
* ❌ App functionality not guaranteed
* ❌ Updates not provided
* ❌ No technical support

**Risks:** Security vulnerabilities, malware, data theft, device damage

**Liability:** All issues arising from unofficial sources are user's responsibility.

### 13.2 Linked Third-Party Sites
There may be links to third-party websites within the app. We are not responsible for these sites' privacy policies.

## 14. Contact

### 14.1 Privacy Questions
For questions about the privacy policy:

**Email**: privacy@harmoniakids.com  
**Subject**: "Privacy Policy Question"  
**Response Time**: Within 5 business days

### 14.2 Data Protection Officer (DPO)
**Name**: [DPO Name - to be added]  
**Email**: dpo@harmoniakids.com  
**Role**: GDPR compliance and protection of user rights

### 14.3 General Contact
**Company**: Harmonia Kids  
**Web**: https://harmoniakids.com  
**Support**: support@harmoniakids.com

## 15. Update History

| Date | Version | Changes |
|------|---------|---------|
| November 3, 2025 | 3.0 | iOS 14+ ATT support, age-based dynamic data collection details |
| October 25, 2025 | 2.0 | AppsFlyer child mode explanations |
| July 16, 2025 | 1.0 | Initial release |

---

# FİKRİ MÜLKİYET / INTELLECTUAL PROPERTY
**Son Güncelleme / Last Updated: 16 Temmuz / July 16, 2025**

**Yazar / Author**: Adil Maviş (Çocuk Gelişimi Uzmanı/SHU / Child Development Specialist/SHU)  
**Seslendiren / Voice Over**: Fatma Maviş (Türk Dili ve Edebiyatı Öğretmeni/Sosyolog/SHU / Turkish Language and Literature Teacher/Sociologist/SHU)  
**Kitap / Book**: Terapötik Masallar / Therapeutic Tales (Yazar/Author: Adil Maviş / Yayın Evi/Publisher: 5.Boyut Yayınları / 2025)  

* Tüm ses içeriği hakları münhasıran Fatma MAVİŞ'e aittir / All audio content rights exclusively belong to Fatma MAVİŞ
* Tüm görseller yapay zeka araçları kullanılarak oluşturulmuştur / All images are created using artificial intelligence tools
* Harmonia Kids mobil uygulaması ve içerikleri Fatma MAVİŞ'e aittir / Harmonia Kids mobile application and its contents belong to Fatma MAVİŞ

---

# KULLANIM SÖZLEŞMESİ / TERMS OF USE
**Son Güncelleme / Last Updated: 16 Temmuz / July 16, 2025**

## 1. Lisans / License
Kullanıcılara, uygulamayı kişisel, ticari olmayan amaçlarla kullanmaları için sınırlı, münhasır olmayan bir lisans verilir. / Users are granted a limited, non-exclusive license to use the application for personal, non-commercial purposes.

## 2. Kullanım Kısıtlamaları / Usage Restrictions
Kullanıcılar / Users may not:
* Uygulamayı kopyalayamaz veya değiştiremez / Copy or modify the application
* Uygulamadan herhangi bir içeriği dağıtamaz veya satamaz / Distribute or sell any content from the application
* Kaynak kodu çıkarmaya teşebbüs edemez / Attempt to extract source code
* Uygulamayı yasa dışı amaçlarla kullanamaz / Use the application for illegal purposes

## 3. Hesap Yönetimi / Account Management
* Kullanıcılar Google veya Apple hesapları aracılığıyla uygulamamıza giriş yapabilirler. / Users can sign into our application through Google or Apple accounts.
* Kullanıcılar hesaplarını profil sayfasındaki "Hesabımı Sil" seçeneğini kullanarak kalıcı olarak silebilirler. / Users can permanently delete their accounts using the "Delete My Account" option on the profile page.
* Hesap silindikten sonra, hesap verileri geri getirilemez. / After account deletion, account data cannot be recovered.

## 4. Abonelik Hizmetleri / Subscription Services

### 4.1 Abonelik Türleri / Subscription Types
* Uygulamamızda aylık ve yıllık abonelik seçenekleri bulunmaktadır. / Our application offers monthly and annual subscription options.
* Abonelik fiyatları bölgesel olarak farklılık gösterebilir. / Subscription prices may vary regionally.
* Güncel fiyatlar satın alma sırasında uygulama içinde görüntülenir. / Current prices are displayed within the application at the time of purchase.

### 4.2 Ödeme İşlemleri / Payment Processing
* Abonelik ödemeleri Google Play Store ve Apple App Store'un kendi ödeme sistemleri (Google Pay/Apple Pay) aracılığıyla gerçekleştirilir. / Subscription payments are processed through Google Play Store and Apple App Store's own payment systems (Google Pay/Apple Pay).
* Ödeme işlemleri ve fatura bilgileri için ilgili platform sağlayıcısının (Google/Apple) şartları geçerlidir. / Payment processing and billing information are subject to the respective platform provider's (Google/Apple) terms.
* İlk ödeme abonelik satın alındığı anda gerçekleşir. / Initial payment is charged immediately upon subscription purchase.

### 4.3 Otomatik Yenileme / Auto-Renewal
* Abonelikler otomatik olarak yenilenir (aylık abonelikler her ay, yıllık abonelikler her yıl). / Subscriptions automatically renew (monthly subscriptions every month, annual subscriptions every year).
* Otomatik yenilemeyi iptal etmek için, abonelik sona erme tarihinden en az 24 saat önce platform ayarlarınızdan (Google Play Store/Apple App Store) iptal etmeniz gerekir. / To cancel auto-renewal, you must cancel through your platform settings (Google Play Store/Apple App Store) at least 24 hours before the subscription expires.
* Otomatik yenileme iptal edilmezse, abonelik ücreti mevcut dönemin bitiminden 24 saat önce hesabınızdan tahsil edilir. / If auto-renewal is not cancelled, the subscription fee will be charged to your account 24 hours before the end of the current period.

### 4.4 İptal ve İade / Cancellation and Refunds
* Abonelik iptali için Google Play Store veya Apple App Store ayarlarınızdan işlem yapmanız gerekir. / To cancel your subscription, you must process through your Google Play Store or Apple App Store settings.
* İade talepleri Google Play Store ve Apple App Store'un kendi iade politikalarına tabidir. / Refund requests are subject to Google Play Store and Apple App Store's own refund policies.
* Abonelik iptal edildikten sonra, mevcut dönemin sonuna kadar premium özelliklere erişiminiz devam eder. / After subscription cancellation, your access to premium features continues until the end of the current period.
* Hesap silme işlemi aboneliği otomatik olarak iptal etmez; abonelik ayrıca iptal edilmelidir. / Account deletion does not automatically cancel subscriptions; subscriptions must be cancelled separately.

### 4.5 Ücretsiz Deneme (Varsa) / Free Trial (If Available)
* Ücretsiz deneme süresi boyunca hiçbir ücret tahsil edilmez. / No charges are made during the free trial period.
* Ücretsiz deneme süresinin bitiminden 24 saat önce iptal edilmezse, seçilen abonelik otomatik olarak başlar ve ücret tahsil edilir. / If not cancelled 24 hours before the end of the free trial period, the selected subscription automatically begins and charges apply.
* Ücretsiz deneme hakkı kullanıcı başına bir kez kullanılabilir. / Free trial rights can only be used once per user.

## 5. İçerik / Content
* İçerik belirli yaş grupları için kategorize edilmiştir: 0-3, 4-7, 8-11 ve 12-14 yaş / Content is categorized for specific age groups: 0-3, 4-7, 8-11, and 12-14 years
* Tüm terapötik sesli masallar tescilli içeriktir / All therapeutic audio stories are proprietary content
* Görseller kullanıcı deneyimini geliştirmek için yapay zeka ile oluşturulmuştur / Images are created with artificial intelligence to enhance user experience

---

**Bu dokümantasyon COPPA ve GDPR gerekliliklerini karşılamak üzere hazırlanmıştır. / This documentation is prepared to meet COPPA and GDPR requirements.**

**İletişim / Contact**: privacy@harmoniakids.com
