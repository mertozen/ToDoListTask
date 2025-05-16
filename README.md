# Yapılacaklar Listesi Uygulaması

React kullanarak tek sayfa halinde bir yapılacaklar listesi uygulaması geliştirmeniz bekleniyor. Veriler React içinde statik olarak saklanacaktır.

## Beklenen Özellikler

- **Yapılacaklar listesi oluşturma**  
  Her bir liste bir adı olacaktır.

- **Yapılacaklar listelerinin görüntülenmesi**  
  Var olan tüm listeler listelenir.

- **Yapılacaklar listesini silme**

- **Mevcut bir listeye yapılacak madde ekleme**

- **Yapılacak maddeler arası bağımlılık ekleme**  
  Bir madde, bağımlı olduğu madde tamamlanmadan “tamamlandı” olarak işaretlenemez.

- **Her bir madde için:**  
  - Ad  
  - Açıklama  
  - Bitiş tarihi  
  - Durum

- **Maddeyi “Tamamlandı” olarak işaretleme**

- **Filtreleme**  
  - Duruma göre (tamamlandı / tamamlanmadı)  
  - Süresi dolmuş mu  
  - Ada göre

- **Sıralama**  
  - Oluşturulma tarihine göre  
  - Bitiş tarihine göre  
  - Ada göre  
  - Duruma göre

- **Yapılacak maddesini listeden silme**

## Genel Beklentiler

- Projenizin hiçbir ek bağımlılık olmadan kolayca çalıştırılabilir olması.
- HTML, CSS ve JS kütüphaneleri olarak Tailwind kullanabilirsiniz.
- Ön yüzde tercih ettiğiniz paket yöneticisini kullanın.
- En az 3 birim testi (unit test) yazın.
- ChatGPT tarafından üretilmiş kodları kullanmayın; denetlenecektir.
- Kurulum ve çalıştırma adımlarını açıklayan bir dökümantasyon ekleyin.  
  **[OPSİYONEL]** Ayrıntılı dökümantasyon yerine tüm servislerin `docker-compose up` ile ayağa kalkacağı şekilde konfigürasyon yapabilirsiniz.
- Projenizi paketlenmiş dosya ya da GitHub üzerinden paylaşın.

# To-Do List Uygulaması Mockup Görselleri

![To-Do Uygulaması Mockup Görselleri](mockups.png)

## Ekran Açıklamaları

1. **Ana Ekran (Dashboard)**  
   - Sol panelde tüm yapılacaklar listeleri  
   - Sağ panelde seçili listenin genel görünümü  

2. **Liste Detayı**  
   - Her bir görevin adı, açıklaması, bitiş tarihi ve durumu  
   - Görevler arası bağımlılık okları  

3. **Filtre ve Sıralama**  
   - Duruma (Tamamlandı/Tamamlanmadı), ada veya süresi dolmuş olup olmamasına göre filtre  
   - Oluşturulma tarihi, bitiş tarihi, ada veya duruma göre sıralama  

4. **Yeni Görev Ekleme Modalı**  
   - Görev adı, açıklama, bitiş tarihi ve durum seçeneği  
   - “Ekle” ve “İptal” butonları  

