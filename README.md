# Grade Calculator Application

Öğrencilerin vize, final ve ödev notlarını girerek dönem sonu başarı notunu ve harf notunu (AA, BA, FF vb.) hesaplamalarını sağlayan **Vanilla JavaScript** ile geliştirilmiş interaktif not hesaplama uygulaması.

---


## 📸 Ekran Görüntüsü

<img width="1280" height="720" alt="Screen Recording 2026-08-27 at 10 01 30 57 PM" src="https://github.com/user-attachments/assets/c6fb1d22-7168-4965-82a3-2a9716e70c8a" />


---

## 🚀 Özellikler

* **Dinamik Not Hesaplama:** Vize (%40) ve Final (%60) ağırlıklarına göre dönem sonı notunun otomatik hesaplanması.
* **Harf Notu Değerlendirmesi:** Hesaplanan ortalamaya göre standart 4'lük/100'lük sisteme uygun harf notu (AA, BA, BB, CB, CC, DC, DD, FD, FF) karşılığının verilmesi.
* **Baraj & Geçme/Kalma Durumu:** Geçme notu sınırına göre kullanıcının dersi geçip geçmediğinin anlık olarak renkli rozetlerle (Badge) gösterilmesi.
* **Form Doğrulama (Validation):** 0-100 aralığı dışında değer girilmesini engelleyen ve eksik alanları uyaran kontrol mekanizması.
* **Responsive Arayüz:** Tüm mobil ve masaüstü cihazlarla tam uyumlu, kullanıcı dostu form tasarımı.

---

## 🛠️ Teknolojik Mimari
* **HTML5:** Semantik form elemanları, input türleri (`number`) ve yapısal etiketler.
* **CSS3:** Flexbox/Grid düzeni, custom input stilleri ve durum bildirim renkleri (Yeşil/Kırmızı geçme-kalma durumları).
* **Vanilla JavaScript (ES6+):** 
  * Form event yönetimi (`submit`, `input`)
  * Matematiksel ağırlıklı ortalama algoritmaları
  * Dinamik sınıf ve stil güncellemeleri (DOM Manipulation)


---

## 📂 Proje Dosya Yapısı

```text
grade-calculator/
│
├── assets/
│   └── preview.png       # README ekran görüntüsü
├── index.html            # Form ve sonuç alanı yapısı
├── style.css             # Arayüz, form ve kart stilleri
├── script.js             # Hesaplama algoritmaları ve doğrulama mantığı
└── README.md             # Proje dokümantasyonu


