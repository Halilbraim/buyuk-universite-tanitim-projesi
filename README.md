# 🎓 Fırat Üniversitesi Tanıtım Projesi

Fırat Üniversitesi'ne yeni başlayacak veya üniversiteyi tanımak isteyen öğrenciler için hazırlanmış; kampüs yaşamı, bölümler ve yurt imkânları hakkında detaylı bilgi sunan modern, kullanıcı dostu bir web tanıtım platformu.

> Şu an yalnızca Fırat Üniversitesi'ni kapsıyor; ileride diğer üniversiteleri de ekleyerek genişletilmesi planlanıyor.

---

## 🚀 Özellikler

- **Ana Sayfa (`index.html`):** Ziyaretçileri karşılayan, üniversitenin genel atmosferini ve öne çıkan istatistiklerini (öğrenci sayısı, fakülte sayısı, kuruluş yılı vb.) tanıtan ana arayüz.
- **Bölümler (`bolumler.html`):** Fakülteler ve bölümler hakkında detaylı bilgilerin yer aldığı, isim/fakülte/puan türüne göre arama ve filtreleme yapılabilen sayfa.
- **Kampüs Yaşamı (`kampus.html`):** Tarihçe, yerleşkeler, ulaşım, yemekhane, kütüphane, sosyal yaşam, teknoloji ve kariyer imkânları gibi başlıklar altında tıklanabilir kartlarla detay modalları sunan rehber.
- **Yurt İmkânları (`yurt.html`):** KYK yurtları, özel yurtlar/apartlar, kiralık ev seçenekleri ve KYK başvuru süreci hakkında rehber içerikler.
- **Kaydırma ile beliren animasyonlar (reveal):** Sayfa kaydırıldıkça bölümlerin yumuşak geçişle görünür hale gelmesi.

---

## 🛠️ Kullanılan Teknolojiler

- **HTML5** — sayfa yapı taşları ve semantik iskelet
- **CSS3 (`style.css`)** — modern tasarım, esnek grid düzenleri ve karanlık tema
- **JavaScript (`script.js`)** — arama/filtreleme, modal kontrolü, kaydırma animasyonları
- **`data.js`** — bölüm (`departmentsData`) ve kampüs/yurt modal (`modalData`) içeriklerini besleyen veri dosyası

---

## 📁 Proje Dosya Yapısı

```
firat-universitesi-tanitim/
│
├── index.html       # Ana sayfa
├── bolumler.html    # Bölümler ve fakülteler sayfası
├── kampus.html      # Kampüs olanakları ve yaşam
├── yurt.html         # Barınma ve yurt bilgileri
├── style.css         # Tasarım ve stiller
├── script.js         # Fonksiyonellik ve interaktif kodlar
└── data.js           # Bölüm ve modal içerik verileri
```

---

## ▶️ Yerelde Çalıştırma

Herhangi bir kurulum veya derleme adımı gerekmez, tamamen statik bir site:

1. Depoyu klonla: `git clone <repo-linki>`
2. `index.html` dosyasını bir tarayıcıda aç (veya VS Code'da Live Server eklentisiyle çalıştır).

---

## 🌐 Canlı Demo

_(GitHub Pages üzerinden yayınlandığında linki buraya ekle)_

---

## 📌 Bilinen Eksikler / Yapılacaklar

- [ ] `data.js` dosyasının içeriği (bölümler ve modal metinleri) doldurulacak
- [ ] Kampüs ve yurt istatistikleri resmî kaynaklardan (firat.edu.tr, KYK) teyit edilecek
- [ ] Ekran görüntüleri eklenecek
- [ ] Mezunlar & Kariyer, Topluluklar & Sosyal Yaşam, Elazığ Şehir Rehberi sayfaları hazırlanacak

---

## 📄 Lisans

Bu proje kişisel bir tanıtım çalışmasıdır. Lisans eklenmemiştir; kullanmadan önce proje sahibiyle iletişime geçin.
