# Boss Lab Arena savunma kontrol listesi

Bu sayfa, **Boss Lab: Robot Battle Builder** oyununda Arena'ya boss yayınlamadan önce bakılacak maddeleri toplayan bir başvuru listesidir. Boss Lab, 2026'da çıkan ücretsiz bir Android robot otomatik savaş oyunudur. Ayrıntılı taktikler resmi [Arena savunma rehberinde](https://www.bosslab.xyz/blog/arena-defense?utm_source=readthedocs&utm_campaign=sprint_rtd-tr) yer alıyor.

> Bu sayfayı **Boss Lab'in geliştiricisi Boss Lab Studio** hazırladı. Oyun tasarımı, kod ve denge ekibe aittir; görseller ve sesler yapay zekâ desteğiyle üretilmiştir.

## Arena nasıl çalışır?

Arena **asenkron PvP**'dir. Boss'unu yayınlarsın ve diğer oyuncuların boss'ları, sen çevrimdışıyken bile ona saldırır. Canlı rakip beklemezsin. Savaş otomatiktir ve yandan görünümde oynanır; yani savunma sırasında hiçbir şeye dokunmazsın. Boss'unun nasıl davranacağını tamamen parçaların ve yapay zekâ beyni belirler.

## Hızlı bilgiler

| Konu | Bilgi |
|---|---|
| Platform | Sadece Android (Google Play); iOS sürümü yok |
| Ücret | Ücretsiz, uygulama içi satın alımlar var |
| Bağlantı | İnternet bağlantısı gerekir |
| Parça sayısı | 60+ |
| Beyinler | Hunter, Counterstrike, Berserker |
| Kampanya | 20 bölgede 100 boss |

## Yayınlamadan önce kontrol listesi

- [ ] **Kurulum kampanyada denendi mi?** Aynı boss'a karşı birkaç kez kazanmış bir kurulumla başla.
- [ ] **Silah ile hareket uyumlu mu?** Boss, silahının işe yaradığı mesafeye ulaşabiliyor mu?
- [ ] **Gövde yeterince dayanıklı mı?** Silahlar devreye girmeden boss düşüyorsa gövdeyi gözden geçir.
- [ ] **Destek modülü bir sorunu çözüyor mu?** Sadece yer doldurmak için takılan modülü çıkar.
- [ ] **Beyin silaha uygun mu?** Aşağıdaki tabloya bak.
- [ ] **Tek değişiklik kuralı:** Son testte yalnızca bir parçayı veya beyni değiştirdin mi?

## Beyin seçimi tablosu

| Beyin | Davranış | Savunmada ne zaman? |
|---|---|---|
| **Hunter** | Hedefi kovalar | Yakına gitmesi gereken kurulumlarda |
| **Counterstrike** | Rakibe tepki verir, karşılık verir | Rakibin hamlesine cevap vermesi gereken kurulumlarda |
| **Berserker** | Hasar aldıkça daha öfkeli olur | Uzun dayanan, dövüş ilerledikçe sertleşmesi istenen kurulumlarda |

## Yayın sonrası adımlar

1. Boss'unu Arena'ya yayınla.
2. Kurulumun Arena'daki performansını takip et; ayrıntılar [Arena savunma rehberinde](https://www.bosslab.xyz/blog/arena-defense?utm_source=readthedocs&utm_campaign=sprint_rtd-tr).
3. Sürekli aynı şekilde kaybediyorsan kampanyaya dön ve sorunu orada test et.
4. Tek bir değişiklik yapıp kurulumu yeniden yayınla.

## Sık yapılan hatalar

- Kampanyada test edilmemiş bir kurulumu doğrudan yayınlamak.
- Aynı anda hem parçaları hem beyni değiştirmek.
- Boss Lab'i bir bölüm editörü sanmak: oyunda seviye editörü ve kullanıcı içerik araçları yoktur. Boss tasarlarsın, harita değil.

## İndir

[Boss Lab'i Google Play'den indir](https://play.google.com/store/apps/details?id=com.bosslab.game&utm_source=readthedocs&utm_campaign=sprint_rtd-tr)
