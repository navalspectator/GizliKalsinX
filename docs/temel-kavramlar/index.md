# Temel Kavramlar

## Gizlilik

Dijital dünyada gizlilik, kişisel verilerinizin korunması ve izinsiz erişimden, kullanımdan ve dağıtımdan sakınma hakkıdır. Dijital gizlilik, kullanıcıların kimliklerini, verilerini ve çevrimiçi etkinliklerini güvence altına alarak özgürlük ve güvenlik sağlar. Kısaca, verilerinizin sadece sizin izin verdiğiniz taraflar tarafından erişilebilmesi ve kullanılabilmesi olarak tanımlanabilir.

## Güvenlik

Güvenlik, bilgisayarlar, akıllı telefonlar, tabletler ve internet gibi teknolojilerin kullanımı sırasında oluşan tehditlere karşı korunmak için alınan önlemlerdir. Bireysel olarak baktığımızda kullandığımız cihaz veya uygulamaların verilerimizi dış saldırı ve tehditlere karşı ne kadar koruyabileceğinin bir ölçüsü olarak tanımlanabilir.

Basitçe, dijital dünyada kişisel verilerinizin ve bilgisayar sisteminizin güvende olmasını sağlamaktır.

## Anonimlik

Anonimlik, kimliğinizin gizli kalması veya ortaya çıkmaması durumudur. Anonimlik internette yaptıklarınız ve paylaştıklarınız şeylerin hiçbir şekilde sizinle ilişkilendirilememesidir.

## Peki aralarındaki farkı nasıl anlayacağım?

Hepimizin evlerinde ve apartmanlarında kapı kilitleri veya alarmlar var. Hatta bazen gerektiğinde odalarımızı da kilitliyoruz. İşte bu kilit ve önlemlerin bizim evlerimizi ne kadar iyi koruyabileceğinin ölçüsü güvenliktir.

Hiçkimse birbirinin evinde ne yaptığını gözetleyemez, ama o evin bize ait olduğu, adresi, dış görünüşü vs. bilinir. Dolayısıyla bu gizliliktir. Anonimlik ise o evin kime ait olduğu ve içinde kimlerin yaşadığını mahallelinin (dijital olarak düşünürsek teknoloji firmaları veya internet servis sağlayıcıları) veya devletler tarafından bilinmemesidir.

Tabi ki bu çok basitleştirilmiş bir anlatım. Kullandığınız perdenin cinsi ve kalınlığı, duvarların yalıtım oranı, kaçıncı katta oturduğunuz gibi birçok etken sizin gizlilik seviyenizi belirler.

Teknolojide de kullanılan şifreleme algoritmaları, hangi veri veya metaverilerin şifrelendiği gibi hususlar da dijital gizliliğin seviyesini belirler. Dolayısıyla bireyler kendi ihtiyaçlarını göz önünde bulundurarak basit bir planlama yapması ve gerçekten neye ne kadar ihtiyacı olduğunu belirlemesi gerekmektedir.

Bu açıklamalardan hareketle diyebiliriz ki, aslında birçoğumuzun anonim olmaya değil gizliliğe ihtiyacı vardır.

## Veri ve Metaveri

Veri temel olarak elimizde bulunan fotoğraf, video, döküman, dosya gibi dijital varlıkları oluşturan ham bilgilerdir.

Metaveri ise verilerin işlenebilmesi, tasnif edilmesi gibi amaçlarla veri hakkında bilgiler içerir. Örneğin bir mektup göndermek istediğinizde, mektup içinde yazılan metin veri iken, zarfın üzerinde bulunan ve tamamen mektubun iletilmesine yardımcı olan bilgiler metaveridir.

## Uçtan Uca Şifreleme ve Transit Halinde Şifreleme

**Transit Halinde Şifreleme,** veri veya metaverilerin internette izleyeceği yol boyunca şifrelenmesidir ve şifreleme anahtarınız ilgili sunucu ile paylaşılır. Bu internet servis sağlayıcı veya diğer tarafların verilerinizi okuyabilmesini engeller ama şifreleme anahtarı sunucuda bulunduğu için ilgili şirket tüm verilerinize erişebilir.

Uçtan uca şifrelemede ise veri veya metaveriler sadece internette transit halinde değil aynı zamanda bu verileri işleyen veya size bu hizmeti sağlayan uygulamanın sunucularında da şifrelenir. Şifreleme anahtarı sadece ve sadece kullanıcıda bulunmaktadır. Bu durumda bir veri sızıntısı (güvenlik) veya herhangi bir devlet tarafından müdahale olsa (gizlilik) bile sunucuda bulunan şahsi verileriniz üçüncü taraflar tarafından okunamayacaktır.

*Mesajlaşma uygulamalarından bir örnek verelim.*

Bir AVM'desiniz ve arkadaşınıza transit halinde şifreleme kullanan bir uygulamadan (mesela Telegram) mesaj attınız. O sırada AVM nin wifisini kullandığınızı farzededelim. Attığınız mesaj bağlı olduğunuz AVM wifisinde gideceği için AVM nin teknik personeli, internet servis sağlayıcısı ve aradaki diğer kişiler tarafından görülemez. Ama şifreleme anahtarınız telegramda olduğu için bütün mesajlarınız Telegram sunucularında kayıt altına alınmaktadır. Dolayısıyla transit halinde şifrelemede sunucu sahibi şirkete güvenmeniz gerekir.

Eğer aynı kişi Signal uygulamasını kullanıyorsa, uçtan uca şifreleme sayesinde signal sunucularında bir sızıntı olsa veya bir mahkeme kararı çıksa bile Signal bu verilere sahip olmadığından sizin hakkınızda hiçbirşey paylaşamaz. Dolayısıyla uçtan uca şifreleme sayesinde başka bir şirkete güvenmenize ihtiyaç kalmaz.

Diğer önemli bir ayrıntı ise kullanılan uygulamalaya göre hangi veri veya metaverilerin uçtan uca şifreleme ile kullanıldığı da önemlidir. Örneğin whatsapp mesajlaşma ve aramalarda uçtan uca şifreleme kullanmakta, ama bunların yanında çok fazla miktarda metaveri toplamakta ve bunları facebook ile paylaşmaktadır.
