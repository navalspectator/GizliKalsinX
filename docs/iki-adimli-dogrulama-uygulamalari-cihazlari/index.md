---
title: "Güvenli Not Alma Uygulamaları"
icon: simple/2fas
---


# İki Faktörlü Doğrulama Nedir?

İki faktörlü kimlik doğrulama, kullanıcı adı ve parolanız gibi sizin bildiğiniz bilgiler dışında ek adımlar gerektiren bir güvenlik doğrulama mekanizmasıdır. Bir hesabı koruma altına almada ve ona erişmede en birinci yol sizin bildiğiniz kullanıcı adı/email adresi ve şifre kombinasyonunu girmektir. Eğer bir siber saldırgan bunları ele geçirir veya tahmin ederse hesabınıza rahatlıkla erişebilir.

İki adımlı doğrulama sizin **bildiğiniz bu kombinasyona** ek olarak **sahip olduğunuz** bir bir cihaz, kod veya uygulamada bulunan faktörü kullanarak ikinci bir güvenlik adımı sağlar. İki faktörlü/adımlı doğrulama (2FA, Two-factor authentication) yaygın kullanım olarak hem konuşma diline, hem de dökümantasyonlara yansımış olsa da, aslında doğrusu çok faktörlü/adımlı doğrulamadır (Multi-factor Authentication). Erişilecek hesap veya bilginin önemine göre adım veya faktör sayısı 2, 3, 4 veya 5 olabilir. Burada önemli her adımda **farklı doğrulama metotlarının** kullanılmasıdır, yani iki tane farklı parola ile bir hesaba giriş yapmak bir iki **faktörlü** doğrulama metodu sayılmaz.

## İki faktörlü Doğrulama Çeşitleri

Kullanılan teknolojiye göre farklı 2FA yöntemleri bulunmaktadır. En yaygın ve sanılanın **aksine** en az güvenli 2FA metodlarından birisi SMS tir. Zayıftan güçlüye doğru sayarsak, **SMS, eposta üzerinden gönderilen doğrulama kodları, uygulamalar üzerinden gönderilen doğrulama bildirimleri (push notifications), zamana dayalı tek seferlik şifreler (Time-based One-time password, T-OTP), ve 2fa cihazlarıdır**. Burada güvenlik seviyesini belirleyen ana etken, ikinci faktörün veya adımın **sahip olduğunuz** bir şey olmasıdır.

1. Bahsettiğimiz gibi **SMS** ve **eposta** ile gönderilen tek seferlik şifreler en zayıf 2FA metodur. Çünkü, telefon numarası veya emailinizin ele geçirilmesi ve buraya gelen kodlara erişilebilmesi diğer metodlara göre daha kolaydır. 
2. Uygulama üzerinden gönderilen **doğrulama bildirimleri,** SMS veya epostaya göre daha güvenilir olsa da, uygulama kaydedilen cihazlar, bahse konu uygulamaların ve kullandıkları teknolojinin ne kadar güvenilir olduğuna bağlıdır. Ayrıca farklı hesaplar için farklı uygulamalar yüklemek ve onlara vereceğimiz izinler de bu yöntemin diğer dezavantajlarındandır.
3. Diğer yaygın 2FA metotlarından birisi ise zamana dayalı tek seferlik şifrelerdir. Bu metotta sadece bir doğrulayıcı (authenticator) **uygulamasına** ihtiyacınız vardır. Sonrasında her hesap için bir QR kod okutursunuz veya sizinle paylaşılan gizli anahtarı (secret key) bu uygulamaya girersiniz. Uygulama da size gizli anahtar ile zamanın kombinasyonuna göre tek seferlik kullanım kodları üretir. Dolayısıyla güvenilir bir doğrulayıcı uygulama tercih ettiğiniz takdirde, hesabınızın ele geçirilmesi çok çok zorlaşır.
4. Zamana dayalı tek seferlik şifreleri uygulama yerine bir donanımsal bir güvenlik anahtarında da saklayabilirsiniz. Bu metotta kodlar sadece ve sadece bir usb şeklinde olan bu cihazlar bilgisayara bağladığınızda ve siz cihaz üzerindeki tuşa bastığınızda ilgili siteye gönderilir.
5. Son olarak FIDO2 isimli bir teknoloji kullanan donanımsal güvenlik anahtarları vardır. Pratikte usb belleğe benzer bir cihazı yine bilgisayara veya mobil cihazınıza takmanız gerekir, ancak içerisinde kullanılan teknoloji tek seferlik şifrelerden farklıdır ve daha güvenlidir.

## Benim için En Uygun 2fa Yöntemine Nasıl Karar Verebilirim?

Bu karar tehdit modelinize, bütçenize, korumak istediğiniz hesap ve verilerinizin ne kadar güvenli olduğu gibi etkenlere dayanır. Ama genel bir kural olarak şunu söyleyebiliriz ki, **parola yöneticisinde oluşturduğunuz karmaşık bir şifre ve güvenilir bir authenticator uygulaması kullanmanız durumunda hesaplarınızı büyük oranda güvene almış olursunuz**. 

## Tavsiye Ettiğimiz İki Faktörlü Doğrulama (2FA) Uygulamaları

### 1. [2FAS (iOS, Android, Tarayıcı Eklentisi)](https://2fas.com/)

- 2FAS cihazlar arası senkronizasyona izin veren ve modern bir kullanıcı arayüzü olan bir iki adımlı doğrulama uygulamasıdır.
- Tarayıcı eklentileri sayesinde tek kullanımlık şifrelerinizi cihazlar arasında geçiş yapmanıza gerek hesaplarınıza giriş yapabilirsiniz.
- Google authenticator, Aegis, Raivo OTP ve LastPass gibi popüler uygulamalarda bulunan kodlarınızı 2FAS uygulamasına taşıyabilirsiniz.
- Eğer uygulamaların tasarım ve arayüzleri sizler için önemli ise 2FAS bu konuda gerçekten çok başarılı bir uygulamadır.

### 2. [Aegis Authenticator (Android)](https://getaegis.app/)

- Aegis android işletim sistemi için geliştirilmiş en iyi kullanıcı arayüzü olan iki adımlı doğrulama uygulamalarından birisidir.
- İki adımlı doğrulama anahtarlarınızı yedeklemek isterseniz, telefonunuza şifreli olarak belirli sürelerde otomatik yedekleme özelliğini kullanabilirsiniz.

### 3. [Ente Authenticator (iOS, Android, MacOS, Web sitesi)](https://github.com/ente-io/auth)

- Uçtan uca şifrelemeli fotoğraf yedekleme uygulaması Ente'nin geliştiricileri tarafından kullanıma [sunulmuştur](https://ente.io/blog/auth/). Uçtan uca şifrelenmiş bulut yedeklemeleri ve çoklu cihaz senkronizasyonu sayesinde dizüstü bilgisayarlarınız, mobil cihazlarınız veya websitesi üzerinden tek kullanımlık kodlarınıza erişebilirsiniz.
- Ente uygulamasını kullanmak için email adresi ve parolanızla bir Ente hesabı açmanız gerekmektedir.

## Tavsiye Ettiğimiz Uygulamaları Seçerken Dikkate Aldığımız Zorunlu Kriterler

- Uygulama açık kaynak kodlu olmalı,
- İnternete erişiminiz olmadığı durumlarda kodlarınızı kullanabiliyor olmalısınız.
- Kodlarınız içeri ve dışarı aktarma özelliği olmalı. (Başka bir uygulamaya geçmenize ve kodlarınızı yedeklemenize izin vermeli.)

## İsteğe Bağlı Kriterler

- Mobil işletim sistemleri ile beraber Masaüstü versiyonları da bulunmalı,
- Uçtan uca şifreleme teknolojisini kullanarak bulut üzerinden entegrasyon sağlamalı,
- Otomatik olarak şifrelenmiş 2fa kodlarını belirtilen klasöre yedekleme.

## Donanımsal Güvenlik Anahtarları

Eğer daha güvenli bir iki faktörlü doğrulama yöntemi kullanmak isterseniz Tavsiye edebileceğimiz donanımsal güvenlik anahtarlarını kullanabilirsiniz.

### 1. Yubikey

YubiKey, Yubico tarafından geliştirilen taşınabilir bir donanım kimlik doğrulama cihazıdır. YubiKey, bilgisayarlara veya mobil cihazlara bağlanan bir USB cihazıdır ve kimlik doğrulama istendiğinde sistemle iletişim kurar. Ayrıca NFC teknolojisiyle uyumlu olan cihazlarla da kullanılabilir. YubiKey, Universal 2nd Factor (U2F), OATH-HOTP veya OATH-TOTP algoritmalarını kullanarak tek kullanımlık şifreler oluşturabilir ve birden fazla kimlik bilgisini depolayabilir, bu da birden çok hesap ve hizmetle kullanılabilmesini sağlar.

Yubikey'in çok sayıda modeli vardır, hangi modelin size ait olduğuna karar verebilmek [karşılaştırma tablosunu](https://www.yubico.com/store/compare/) inceleyebilirsiniz.

Ayrıca Arda Kılıçdağı' nın Yubikey ile alakalı kapsamlı [medium yazısı](https://medium.com/@ardakilic/yubi-ney-yubikey-hakk%C4%B1nda-ilk-deneyimlerim-6a15fd556053) da güzel Yubikey'in kullanımı konusunda faydalı Türkçe kaynaklardan birisi.

***Uyarı: Yubikey aygıt yazılımı (firmware) açık kaynak kodlu değildir ve güncelleme özelliği yoktur. Bu yüzden yeni sürümlerle gelen özelliklere erişmek için yeni model bir cihaz almanız gerekir.***

### 2. Nitrokey

Nitrokey serisi Alman Nitro firması tarafından geliştirilen ve hem donanım hem de yazılım açık kaynak kodlu olan bir donanım güvenlik anahtarıdır. FIDO2, WebAuthn, OTP, ve PGP gibi protokolleri destekleyen farklı modelleri vardır.

Nitrokey cihazlarının detaylı özelliklerini ve aralarındaki farklıları incelemek için kendi sitesindeki [karşılaştırma tablosu](https://www.nitrokey.com/#comparison) incelenebilir.

### [3. Solokeys](https://solokeys.com/)

SoloKeys, açık kaynaklı bir donanımsal güvenlik anahtarıdır. İnternet hesaplarınızı kimlik avı saldırılarına ve yetkisiz erişime karşı korumak için en güvenli giriş yöntemini kullanarak iki faktörlü kimlik doğrulama sağlar. SoloKeys, Trussed® ile oluşturulmuştur. U2F ve FIDO2 standardını desteklemektedir.
