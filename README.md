# Interactive Quiz Application

Kullanıcıların bilgilerini test etmesini sağlayan, dinamik soru yapısına ve anlık skor takibine sahip **Vanilla JavaScript** ile geliştirilmiş interaktif bilgi yarışması uygulaması.

---

## 📸 Ekran Görüntüsü

<img width="1280" height="720" alt="Screen Recording 2026-08-27 at 10 01 30 57 PM" src="https://github.com/user-attachments/assets/c6fb1d22-7168-4965-82a3-2a9716e70c8a" />


---

## 🚀 Özellikler

* **Dinamik Soru Yükleme:** Soruların ve şıkların veritabanı veya nesne dizisinden (Array of Objects) dinamik olarak DOM'a aktarılması.
* **Anlık Şık Kontrolü & Skor Hesaplama:** Doğru/yanlış cevapların anında değerlendirilmesi ve kullanıcıya toplam skorun gösterilmesi.
* **Seçim Zorunluluğu:** Kullanıcı bir şık seçmeden sonraki soruya geçilmesini engelleyen doğrulama (validation) mekanizması.
* **Yeniden Başlatma (Restart):** Quiz bitiminde skoru sıfırlayıp testi baştan başlatma seçeneği.
* **Responsive Arayüz:** Mobil ve masaüstü ekranlarda sorunsuz çalışan kart tasarımı.

---

## 🛠️ Teknolojik Mimari

* **HTML5:** Form elemanları, radyo butonları ve semantik yapı.
* **CSS3:** Card layout, Flexbox, custom radio button stilleri ve responsive medya sorguları.
* **Vanilla JavaScript (ES6+):** 
  * Array & Object manipülasyonu
  * DOM seçicileri ve dinamik içerik basma (`innerHTML`, `innerText`)
  * Event Listeners ve koşullu durum yönetimi (State)

---

## 📂 Proje Dosya Yapısı

```text
quiz-app/
│
├── assets/
│   └── preview.png       # Proje ekran görüntüsü
├── index.html            # İskelet ve kart yapısı
├── hesaplam.css             # Arayüz ve seçim stilleri
├── hesaplama.js             # Soru verileri, skor ve ilerleme mantığı
└── README.md             # Dokümantasyon


