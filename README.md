# 🏛️ Emlucky - Yeni Nesil Gayrimenkul Platformu

Emlucky; yüksek teknoloji, minimalizm ve kusursuz kullanıcı deneyimini (UI/UX) bir araya getiren yeni nesil bir emlak platformudur. 

Her bütçeye uygun ilanları "Exclusive" ve "Fırsat" etiketleriyle kapsayıcı bir dille sunarken, arka planda çalışan canlı REST API mimarisi ile gerçek bir yazılım ürünü (SaaS) deneyimi yaşatır.

🔗 **[Canlı Demoyu İncele](https://gokalpbuyukkoca.github.io/emlucky/)**

---

## ✨ Öne Çıkan Özellikler

- **🌐 Tam Entegre Canlı Portföy (CRUD):** İlanlar statik değildir. Node.js üzerinde çalışan backend API'si sayesinde gerçek zamanlı olarak ilan eklenebilir, silinebilir ve fiyat güncellenebilir.
- **🤖 Emlucky Intelligence (AI Asistan):** Doğal dil işleme simülasyonu ile çalışan, kelime bazlı algılama yaparak kullanıcılara gayrimenkul önerilerinde bulunan interaktif sohbet botu.
- **🎬 Sinematik Arayüz & Animasyonlar:** - **Three.js** kullanılarak donanımsal hızlandırmalı 3D interaktif arka plan.
  - **GSAP & Intersection Observer** ile kaydırdıkça akıcı bir şekilde beliren (Fade In Up) elementler.
  - CSS kullanılarak oluşturulan interaktif ve animasyonlu piyasa analizi (SVG) grafikleri.
- **💎 Glassmorphism & Mega Menü:** Apple'ın tasarım dili olan buzlu cam efekti (`backdrop-filter`) ve kullanıcıyı boğmadan binlerce alt kategori sunabilen ekran genişliğinde mega menü tasarımı.
- **🍱 Bento Grid Layout:** Modern ve asimetrik kart dizilimi ile ilanların "ürün" odaklı sergilenmesi.

---

## 🛠️ Kullanılan Teknolojiler

**Frontend:**
- HTML5 & CSS3 (Vanilla)
- JavaScript (ES6+)
- GSAP (GreenSock Animation Platform)
- Three.js (WebGL)
- FontAwesome (İkonlar)

**Backend / API:**
- RESTful API (Kişisel Backend)
- Hosted on Render (`https://gokalp-emlak-api.onrender.com/ilanlar`)
- `Fetch API` ile asenkron veri iletişimi

---

## 🚀 Kurulum ve Çalıştırma

Proje herhangi bir derleyici (build aracı) gerektirmez. Saf (Vanilla) dillerle yazılmıştır.

1. Projeyi bilgisayarınıza klonlayın:
   ```bash
   git clone [https://github.com/gokalpbuyukkoca/emlucky.git](https://github.com/gokalpbuyukkoca/emlucky.git)
