# Uydu Görüntülerinde Nesne Tespiti ve Sınıflandırma (Diploma Projesi)

## Proje Özeti
Günümüzde uzaktan algılama teknolojileri, yüksek çözünürlüklü uydu görüntülerinin temin edilmesinde devrim yaratmıştır. Özellikle savunma sanayii, lojistik takip ve şehir planlama gibi alanlarda, uydu verileri üzerinden nesne tespiti yapmak kritik bir karar destek mekanizması haline gelmiştir. Bu bağlamda, askeri ve sivil hava araçlarının uydu görüntüleri üzerinden otomatik olarak tanınması, stratejik öneme sahip bir araştırma konusudur.

Mevcut literatürde nesne tespiti için kullanılan derin öğrenme tabanlı algoritmalar genellikle sahnenin tamamını analiz etmeye odaklanır. Bu çalışmada, nesne tespiti yerine, sınırlayıcı kutu bilgileri kullanılarak nesnelerin tekil görüntüler haline getirildiği ve ardından özelleştirilmiş bir Konvolüsyonel Sinir Ağı (CNN) ile sınıflandırıldığı bir metodoloji baz alınarak modellerinin başarısı test edilmek istenmiştir.

---

## Metodoloji
* **Veri Hazırlama:** Sınırlayıcı kutu (bounding box) tabanlı segmentasyon.
* **Model:** Özelleştirilmiş Konvolüsyonel Sinir Ağı (CNN).
  
