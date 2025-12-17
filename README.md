# 🎨 AI Görsel Prompt Koleksiyonu

> **İnternetten derlediğim 55+ AI görsel oluşturma prompt'u** - eğitimler ve örneklerle birlikte.

[![Promptlar](https://img.shields.io/badge/Prompt_Sayısı-55+-blue.svg)](#-prompt-koleksiyonu)
[![Notion](https://img.shields.io/badge/Orijinal-Notion-black.svg)](https://promptlar.notion.site/)

---

## 📖 Hakkında

Bu repo, internetten derlediğim ve test ettiğim AI görsel oluşturma prompt'larını içeriyor. Gerçekçi fotoğraflar, stilize çizimler, infografikler veya teknik renderlar oluşturmak istiyorsanız burada işinize yarayacak prompt'lar bulacaksınız.

### İçerik

- 🎓 **Eğitimler**: Görsellerden detaylı prompt nasıl oluşturulur
- ✏️ **Değiştirme Rehberi**: Mevcut prompt'lar nasıl özelleştirilir
- 📚 **55+ Prompt**: Kategorize edilmiş koleksiyon ve örnek çıktılar

---

## 🎓 Prompt Nasıl Oluşturulur

Herhangi bir görselden detaylı prompt çıkarmak için bu meta-prompt'u kullanın:

```
Generate Highly detailed prompt from this image. Like every tiny detail: 
hair, face, camera, style, accessories, subject, background, 
environment, clothing, items, lightning - all in JSON format
```

### Örnek Çıktı

Bu prompt'u bir görsele uyguladığınızda şöyle bir JSON alırsınız:

```json
{
  "subject": {
    "identity": "Kişi açıklaması",
    "pose": "Ayakta, oturuyor vb.",
    "expression": "Yüz ifadesi detayları"
  },
  "physical_features": {
    "skin_tone": "...",
    "hair": "...",
    "body_type": "..."
  },
  "clothing": { ... },
  "background": { ... },
  "lighting": { ... },
  "camera": { ... },
  "style": { ... }
}
```

---

## ✏️ Prompt Değiştirme

Herhangi bir prompt'u belirli bölümlerini değiştirerek özelleştirebilirsiniz.

### Örnek: Bayrak Değiştirme

**Orijinal:**
```json
"primary_prop": "A large United States flag (Stars and Stripes)."
```

**Türk Bayrağı:**
```json
"primary_prop": "A large Turkish Flag.",
"prop_details": "The crescent is on the viewer's left."
```

### Örnek: Kıyafet Değiştirme

**Orijinal:**
```json
"upper_body": "White Nike Team USA basketball jersey."
```

**Kendi Görseliniz:**
```json
"upper_body": "[uploaded image]"  // Kendi görselinizi referans verin
```

---

## 📚 Prompt Koleksiyonu

### 🗺️ Konum ve Haritalar

| # | İsim | Prompt |
|---|------|--------|
| 1 | Google Maps Fotoğrafı | `"Show a screenshot from Google Maps with an image of this place with a photo and its coordinates"` |
| 40 | Tarihi Olay | Konum + tarih bazlı tarihi sahne oluşturma (JSON format) |
| 42 | Spesifik Koordinat | `"Create an image at 31.7785° N, 35.2296° E, April 3, 33 CE, 15:00 hours."` |
| 45 | Ultra Gerçekçi Konum | Detaylı hava fotoğrafçılığı prompt'u (JSON format) |

### 👤 Karakter ve Portre

| # | İsim | Prompt |
|---|------|--------|
| 2 | Sims 4 Karakter | `"Make her the sims character that is currently editing on the Create-a-Sim character creation in Sims 4"` |
| 3 | Holografik Sticker | `"Make a iPhone shot of old 2000s holographic glitter sticker of this person without background..."` |
| 26 | Polaroid Y2K | `"Take a photo taken with a Polaroid camera..."` |
| 27 | Karakter Figürü | `"Turn this photo into a character figure..."` |
| 31 | Mermer Heykel | `"A photorealistic image of an ultra-detailed sculpture of the subject made of shining marble..."` |
| 47 | Karakter Referans Sayfası | Profesyonel 12 panelli karakter sheet'i |
| 50 | LEGO Figür | `"Create a highly detailed, miniature LEGO-style 3D figure of [NAME]..."` |

### 📸 Kamera ve Fotoğraf Stilleri

| # | İsim | Prompt |
|---|------|--------|
| 9 | Güvenlik Kamerası | `"Check the city's surveillance cameras to see where I last had it"` |
| 11 | Bodega Güvenlik Kamerası | Bodega güvenlik kamerası estetiği |
| 12 | Photo Booth | MacBook Photo Booth 2000'ler webcam stili |
| 13 | VX1000 Kaykay | Sony VX1000 kamera fisheye estetiği |
| 14 | Özel Jet Puro | Fujifilm 35mm flaş fotoğrafçılığı, film grain |
| 15 | iPhone 3G | Erken iPhone kamera kalitesi simülasyonu |
| 44 | Y2K Dijital Kamera | 2000'ler kompakt dijital kamera LCD selfie |
| 55 | Disposable Camera | Düşük kaliteli tek kullanımlık kamera parti fotoğrafı |

### 🏛️ Mimari ve Landmark

| # | İsim | Prompt |
|---|------|--------|
| 4 | Mimari İnfografik | Blueprint tarzı teknik açıklamalar |
| 8 | Mühendislik Anıt | El çizimi mühendislik açıklamaları |
| 29 | İzometrik Bina | `"Make Image Daytime and Isometric [Building Only]"` |
| 33 | Theme Park Stili | Theme Park oyunu tarzı izometrik |
| 43 | İzometrik Render | Detaylı izometrik 3D mimari görselleştirme |
| 48 | Şehir Mıknatısları | 3D mıknatıs knolling düzeni |
| 49 | Stadyum İzometrik | Kapasite ve logo ile stadyum |
| 52 | Şehir Hava Durumu | Hava durumu entegrasyonlu şehir |
| 53 | Pastel Boya Şehir | Çocuk çizimi tarzı şehir illüstrasyonu |

### 🎨 Tasarım ve Tipografi

| # | İsim | Prompt |
|---|------|--------|
| 5 | MS Paint Ekran Görüntüsü | Eski bilgisayar MS Paint uygulama ekranı |
| 16 | 3D Tipografi | Canlı retro halftone tipografi tasarımı |
| 17 | Minimalist Logolar | 8 ifade edici kelime logosu |
| 18 | İmkansız Şekil | "Impossible" kelimesi imkansız şekil olarak |
| 19 | Yemek Logoları | Yemek temalı tipografi logoları |
| 34 | Spiral Defter | Çizgili kağıt üzerinde el yazısı |
| 35 | Hip-Hop Albüm Kapağı | 90'lar/2000'ler hip-hop albüm estetiği |

### 📊 İnfografikler ve Teknik

| # | İsim | Prompt |
|---|------|--------|
| 6 | Tarif Malzemeleri | `"Show me a photo of all the ingredients for this dish, labeled with names and quantities."` |
| 7 | Profesör Tahtası | Görsel diagram açıklaması |
| 20 | Güneş Enerjisi İnfografik | DIY flat lay infografik |
| 21 | Bitki İnfografik | Bitki bilgi görselleştirmesi |
| 22 | Elaichi Chai Tarifi | Adım adım tarif infografik |
| 39 | Teknik Exploded View | Ultra detaylı patlatılmış teknik infografik (JSON) |
| 41 | Parça Aile Portresi | Top-down teardown grid düzeni (JSON) |
| 54 | X-Ray Termal | False color termal x-ray render (JSON) |

### 🛍️ Ürün ve Marka

| # | İsim | Prompt |
|---|------|--------|
| 23 | Marka Mockup'ları | Logonun çeşitli ürünlere uygulanması |
| 24 | Moodboard Stili | `"Generate an image in the style of this moodboard"` |
| 25 | Teknik Çizim | `"Create a technical drawing of this speaker"` |
| 37 | Online Mağaza Sayfası | `"Make an online shop page for this watch"` |
| 38 | Gardırop Katalogu | `"Make an online wardrobe catalog from this outfit"` |
| 46 | Yüksek Kaliteli Kompozisyon | Obje entegrasyonu ve doku geliştirme (JSON) |

### 🎬 Sinematik ve Görünümler

| # | İsim | Prompt |
|---|------|--------|
| 10 | Kıyafet Flat Lay | `"Give each piece of his clothing separately on the asphalt"` |
| 28 | AR Lokasyon | Konum bazlı AR deneyimi açıklamaları |
| 30 | Kuşbakışı Görünüm | `"Convert the photo to a top-down view and mark the location of the photographer."` |
| 32 | Çok Açılı Görünüm | Ön, Arka, Sol, Sağ, Üst, Alt görünümler |
| 36 | Sahne Arkası | `"Show me the exact backstage of this cinematic shot."` |
| 51 | Sinematik Contact Sheet | 3x3 sinematik çekim türleri grid'i |

---

## 📁 Dosya Yapısı

```
ai-image-prompts/
├── README.md              # Bu dosya
├── PROMPTS.md             # Tüm prompt'ların tam metinleri
└── images/                # Örnek çıktı görselleri
    ├── image 1.png
    ├── image 2.png
    └── ...
```

---

## 📌 Notlar


- `[LANDMARK]`, `[CITY]`, `[NAME]` gibi placeholder'ları kendi değerlerinizle değiştirin
- Tüm prompt'ların tam metinleri için [PROMPTS.md](PROMPTS.md) dosyasına bakın

---

## 👤 Derleyen

**Yiğitcan Ural** - [@yigitcanural](https://github.com/yigitcanural)

**Notion Linki:** [promptlar.notion.site](https://promptlar.notion.site/)
