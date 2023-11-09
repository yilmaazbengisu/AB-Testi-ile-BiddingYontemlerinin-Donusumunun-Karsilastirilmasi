# İŞ PROBLEMİ

Facebook, kısa bir süre önce mevcut olan "maximumbidding" olarak adlandırılan teklif verme türüne alternatif olarak yeni bir teklif türü olan "averagebidding"i tanıttı. Müşterilerimizden biri olan bombabomba.com, bu yeni özelliği test etmeye karar verdi ve averagebidding'in maximumbidding'den daha fazla dönüşüm getirip getirmediğini anlamak için bir A/B testi yapmak istiyor.

![image](https://github.com/yilmaazbengisu/AB-Testi-ile-BiddingYontemlerinin-Donusumunun-Karsilastirilmasi/assets/113296702/9c67f4e7-296c-44d2-af79-45bace423748)


A/B testi 1 aydır devam ediyor ve bombabomba.com şimdi sizden bu A/B testinin sonuçlarını analiz etmenizi bekliyor. Bombabomba.com için nihai başarı ölçütü "Purchase"dır. Bu nedenle, istatistiksel testler için "Purchase" metriğine odaklanılmalıdır.


Bir firmanın web site bilgilerini içeren bu veri setinde kullanıcıların gördükleri ve tıkladıkları reklam sayıları gibi bilgilerin yanı sıra buradan gelen kazanç bilgileri yer almaktadır.Kontrol ve Test grubu olmak üzere iki ayrı veri seti vardır. Bu veri setleri __ab_testing.xlsx__ excel dosyasının ayrı sayfalarında yer almaktadır. Kontrol grubuna Maximum Bidding, test grubuna Average Bidding uygulanmıştır.

## Değişkenler

__Impression__ : Reklam görüntüleme sayısı

__Click__ : Görüntülenen reklama tıklama sayısı

__Purchase__ : Tıklanan reklamlar sonrası satın alınan ürün sayısı

__Earning__ : Satın alınan ürünler sonrası elde edilen kazanç
