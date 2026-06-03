# Gizlilik Politikası

**Son Güncelleme:** 4 Haziran 2026

Scriptin sorunsuz çalışması, özelliklerin yönetilmesi ve sistemin kötüye kullanımına karşı korunması için sadece gerekli olan minimum veriyi topluyoruz. Bunun dışında ekstra hiçbir veri izlenmez veya saklanmaz.

## Hangi Veriler Toplanıyor?

Script çalıştırıldığında, hub sistemimiz ve lisanslama yöntemlerimiz aracılığıyla bazı temel bilgiler işlenir. Bu bilgiler şunları içerebilir:

* **Çalıştırma Bilgisi (Execution Info):** Scriptin ne zaman çalıştırıldığı veya kaç kez kullanıldığına dair temel günlükler (loglar).
* **Kullanılan Executor:** Scriptin uyumluluğunu ve kararlılığını sağlamak için kullanılan yazılımın adı (Solara, Wave vb.).
* **Discord Günlükleri:** Sistem bakımı ve hata ayıklama amacıyla, bazı aktiviteler (özelliklerin çalıştırılması veya debug hataları) otomatik webhooks üzerinden iletilebilir.
* **Lisanslama Verileri:** Anahtar (key) paylaşımını ve scriptin kırılmasını (crack) önlemek amacıyla kullanılan Donanım Kimliği (HWID) veya temel kimlik doğrulama jetonları.

Bu veriler tamamen sistemin düzgün çalışmasını sağlamak, suistimalleri önlemek ve bir şeyler ters gittiğinde hataları çözmek amacıyla kullanılır.

## Üçüncü Taraf Hizmetler

Güncellemeleri sunmak, bağlantıları yönetmek ve performansı sağlamak için bazı üçüncü taraf hizmetlerden yararlanıyoruz. Bunlar şunları içerir:

* **GitHub / Gist:** En son kodları (`overseer.lua`) ve script yapılandırmalarını güvenli ve uzaktan çekmek için kullanılır.
* **Discord Webhookları:** Otomatik operasyonel logları ve hata ayıklama bilgilerini göndermek için kullanılır.
* **Lisanslama Araçları:** Script koruması, anahtar üretimi ve kullanıcı kimlik doğrulaması için kullanılır.

*Lütfen unutmayın: Bu üçüncü taraf platformlar, verileri kendi gizlilik ilkelerine göre işler. Onların bağımsız altyapılarını nasıl yönettikleri üzerinde doğrudan bir kontrolümüz yoktur.*

## Veriler Nasıl Kullanılıyor?

Toplanan veriler yalnızca şu amaçlarla kullanılır:

* Kimlik doğrulama ve script kararlılığını takip etme.
* Yazılımın kötüye kullanılmasını, scriptin kırılmasını veya anahtar paylaşımını önleme.
* Destek sağlama ve hataları (bug) çözme.

**Verilerinizi asla hiç kimseye satmıyor, kiralamıyor veya paylaşmıyoruz.**

## Destek

Herhangi bir sorunuz varsa, bir sorunla karşılaşırsanız veya teknik yardıma ihtiyacınız olursa, resmi Discord sunucumuzda bir destek bileti (ticket) açabilir veya doğrudan geliştirme ekibiyle iletişime geçebilirsiniz.

## Değişiklikler

Bu gizlilik politikası, yeni özellikler eklendikçe zaman zaman güncellenebilir. Scripti kullanmaya devam etmeniz, bu politikanın en güncel sürümünü kabul ettiğiniz anlamına gelir.
