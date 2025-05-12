# Kanser Patoloji Raporlama Sistemleri

Bu proje, çeşitli **kanser türleri** için özelleştirilmiş, modern ve kullanıcı dostu **patoloji raporlama sistemleri** sunar. Her sistem, **klinik pratiğe uygun**, tamamen Türkçe içeriklerle geliştirilmiş ve **bilimsel titizlikle tasarlanmıştır**.


📍 Yayında: [https://metinciris.github.io/kanser_raporlama/](https://metinciris.github.io/kanser_raporlama/)

🎯 Amaç: Patoloji raporlarının daha hızlı, daha doğru ve daha sezgisel şekilde oluşturulabilmesi.

Based on CancerReportingTemplate: https://github.com/awiloQMH/CancerReportingTemplate

---

## 🔧 Sistemin Özellikleri

- 🔹 **Tamamen Türkçe**: Tıbbi terminolojiye uygun, sade ve açıklayıcı dil
- 🔹 **Sol Sütun**: Sürekli kayan ve kolay erişilen veri giriş alanları
- 🔹 **Sağ Sütun**: Seçimlere göre eş zamanlı oluşturulan otomatik rapor metni
- 🔹 **Tıklanabilir Seçimler**: Açılır menü yerine doğrudan seçim alanları (örnek: seçenek kartları)
- 🔹 **Renkli Geri Bildirim**: Seçim yapıldığında buton veya kart renginin değişmesi ile kullanıcıya görsel bildirim
- 🔹 **Mobil Uyumlu**: Mobilde tek sütun, masaüstünde çift sütun görünüm
- 🔹 **Raporu Kopyala Butonu**: Tek tıkla tam rapor çıktısını kopyalama

---

## ✨ Tasarım Özellikleri

- 🎨 Modern renk paleti (klinik ortama uygun mavi, gri tonlar)
- 📐 Yuvarlatılmış kenarlar ve gölgeli bilgi kartları
- 📝 Kolay okunabilir "Inter" yazı tipi
- 💡 Animasyonlu geçişler, pürüzsüz UI deneyimi
- 🧠 "Akıllı Form" yapısı: Girişlere göre yeni bölümler dinamik olarak açılır

---

## 🧪 Özel Özellikler

- ✅ Otomatik **AJCC Evreleme** algoritması
  - Girişlere (örneğin pT, pN, metastaz durumu) göre **pTNM evresi ve FIGO gibi ek evreler** otomatik önerilir
- ✅ Rapor içinde otomatik olarak şu formatta görünür:
  - `Patolojik evre (pTNM, AJCC 8. Edisyon): pT2N0`

---

## 📂 Kullanım

Sistemi denemek veya düzenlemek için aşağıdaki bağlantılara göz atabilirsiniz:

- [Canlı Demo Sayfası (index.html)](https://metinciris.github.io/kanser_raporlama/)
- [Bolt Düzenleme Sayfaları ve Şablonlar (index2.html)](https://metinciris.github.io/kanser_raporlama/index2.html)

---

## 🚀 Katkıda Bulunmak

Yeni sistem eklemek veya mevcut sistemi geliştirmek isteyenler `bolt.new` üzerinden düzenleme yapabilir veya önerilerini GitHub Issues üzerinden iletebilir.

---

## 🔗 Lisans

MIT Lisansı ile lisanslanmıştır. Klinik kullanımda doğrulama önerilir.

---

> Bu sistem, patoloji uzmanlarının günlük pratiğini hızlandırmak ve rapor standardizasyonunu artırmak amacıyla geliştirilmiştir. Her sistem, özgün ihtiyaçlara göre uyarlanabilir yapıdadır.
