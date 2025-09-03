<h1 align="center">✨ Stylish Portal</h1>

<p align="center">
  <em>Particles.js arkaplanı ve neon vurgulu inputlarla modern login sayfası</em>
</p>

---

## 🖼️ Demo
<p align="center">
  <img src="./demo.gif?raw=1" width="720" alt="Stylish Portal Demo">
</p>

> `demo.gif` bu README ile aynı klasörde olmalı. Alternatif: raw link kullan — `https://raw.githubusercontent.com/<user>/<repo>/main/demo.gif`

---

## ✨ Özellikler
- 🌌 **Interactive Particles** — Particles.js ile tepkisel arkaplan (hover/repulse, click/push)
- 🧪 **Floating Labels** — form alanlarında dokunmatik/donanımlı sezgisel etkileşim
- 💡 **Neon Glow** — input altı glow-line ve butonda parlama animasyonu
- 🔐 **Login UI** — Remember me, Forgot Password, Register linkleri
- 📱 **Responsive** — modern tipografi (Cinzel & Poppins), mobil/masaüstü uyumlu
- ⚡ **Vanilla** — HTML + CSS + JS; framework bağımlılığı yok (Particles.js CDN)

---

## 🚀 Hızlı Başlangıç

```bash
# Klasörü aç ve dosyaları yerleştir
# Aşağıdaki gibi minimum yapı yeterli:
Stylish-Portal/
├── index.html
├── styles.css
├── demo.gif        # opsiyonel (README için)
└── README.md

# Çalıştırmak için sadece index.html'i tarayıcıda aç
```

> Basit bir server istersen: `npx serve` veya `python -m http.server 8000`

---

## 📜 Kullanılan Kütüphane
- **Particles.js (CDN)** – `https://cdn.jsdelivr.net/particles.js/2.0.0/particles.min.js`

---

## 🧩 Nasıl Çalışır?
- `particlesJS('particles-js', {...})` ile sahne oluşturulur; yoğunluk, bağlantı çizgisi, repulse/push modları aktif.
- Form içinde **floating label** yapısı: `<input>` + `<label>` + dekoratif `.glow-line`.
- Buton içinde `.btn-glow` ile hafif parlama animasyonu.

---

## 🎨 Özelleştirme İpuçları
- Renk paleti: Particles `color.value` ve `line_linked.color` değiştir.
- Yoğunluk/hareket: `number.value`, `move.speed`, `repulse.distance` ile oyna.
- Tipografi/tema: `styles.css` içinde arkaplan, cam efekti, köşeler, gölgeler.

---

## 🔧 Notlar
- Dış `styles.css` bu örnekte harici; istersen inline style'a da gömebilirsin.
- Performans için mobilde `particles.number.value` değerini düşür.

---

## 🧑‍💻 Geliştirici
**Tunahan Coşgun** — <a href="https://github.com/tunacosgun">github.com/tunacosgun</a>
