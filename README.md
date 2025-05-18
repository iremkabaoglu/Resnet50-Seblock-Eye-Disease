# SE Block ile Geliştirilmiş ResNet50 Mimarisi

Bu proje, göz hastalıklarının sınıflandırılması için kullanılan ResNet50 mimarisinin **Squeeze-and-Excitation (SE) Block** ile geliştirilmiş halini sunmaktadır. SE Block ile kanal bazlı dikkat mekanizması entegre edilerek modelin odaklanma yeteneği artırılmıştır.

## 🔬 SE Block Nedir?

SE Block, 2017 yılında tanıtılan ve ImageNet yarışmasında birinci olan **SENet (Squeeze-and-Excitation Network)** mimarisinin yapı taşıdır. Bu bloklar, özellik haritalarının kanal düzeyinde ağırlıklandırılmasını sağlar. Böylece ağ, daha anlamlı ve önemli özelliklere odaklanır.

## 🧠 Kullanılan Mimari

- **Temel Model:** ResNet50 (ImageNet ön eğitimli)
- **Geliştirme:** SE Block eklendi
- **Son Katmanlar:** Global Average Pooling + Dropout + Dense
- **Eğitim:** Orijinal görüntü seti ile transfer learning
- **Karşılaştırma:** Önceki modellerle performans karşılaştırması yapıldı

## 🧪 Eğitim Süreci

- Model, orijinal veri seti ile eğitildi
- Overfitting’i önlemek için Dropout katmanı eklendi
- Eğitim sonrası doğruluk, precision, recall, F1-score gibi metriklerle değerlendirme yapıldı

## 📈 Performans Karşılaştırması

| Mimari | Accuracy | Precision | Recall | F1-Score |
|--------|----------|-----------|--------|----------|
| ResNet50 | ... | ... | ... | ... |
| ResNet50 + SE Block | ... | ... | ... | ... |

_(Not: Bu tabloyu kendi değerlerinle güncelleyebilirsin)_

## 📌 Model Mimarisi

Geliştirilen mimarinin katman yapısı aşağıda görsel olarak sunulmuştur.

*(Buraya model mimarisinin şematik çizimini veya Keras summary çıktısını görsel olarak ekleyebilirsin)*

---

## 🛠️ Kullanılan Teknolojiler

- Python
- TensorFlow / Keras
- ResNet50
- SE Block (custom)
- Matplotlib / Seaborn (grafik için)

---

## ✍️ Geliştirici

**İrem Kabaoğlu**  
`Sakarya Üniversitesi - Bilişim Sistemleri Mühendisliği`  
`ISE456 - Bilgisayarla Görmeye Giriş`
