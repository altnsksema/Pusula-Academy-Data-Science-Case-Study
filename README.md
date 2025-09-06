# Pusula-Academy-Data-Science-Case-Study

**Ad Soyad:** Sema Altınışık 
**Email:** altnsksema@gmail.com 

---

## 📌 Proje Hakkında
Bu proje, Pusula Talent Academy Data Science Intern Case çalışması için hazırlanmıştır.  
Veri seti fiziksel tıp ve rehabilitasyon hastalarına ait olup 2235 gözlem ve 13 özelliği içermektedir.  

**Hedef değişken:** `TedaviSuresi`  

Amaç:  
- Veri setini incelemek (EDA)  
- Eksik değerleri ve anomalileri tespit etmek  
- Veri setini modellemeye hazır hale getirmek (preprocessing)  

---

## 🔍 Veri Seti Özellikleri
- **HastaNo**: Hasta ID (anonimleştirilmiş)  
- **Yas**: Yaş  
- **Cinsiyet**: Kadın/Erkek  
- **KanGrubu**: 8 farklı kan grubu  
- **Uyruk**: 5 farklı ülke  
- **KronikHastalik**: Virgülle ayrılmış çoklu değer  
- **Bolum**: Hastanın tedavi olduğu bölüm  
- **Alerji**: Alerjiler
- **Tanilar**: Tanılar   
- **TedaviAdi**: Uygulanan tedavi  
- **TedaviSuresi**: Seans sayısı   
- **UygulamaYerleri**: Tedavi uygulama bölgeleri  
- **UygulamaSuresi**: Uygulama süresi (dakika)  

---

## ⚙️ Yapılan Adımlar

### 1. EDA
- Eksik değer analizi yapıldı  
- Sayısal değişkenlerin dağılımları incelendi (`Yas`, `TedaviSuresi`, `UygulamaSuresi`)  
- Kategorik değişkenlerin frekans dağılımları çıkarıldı  
- Korelasyon matrisi oluşturuldu  

### 2. Preprocessing
- `TedaviSuresi` ve `UygulamaSuresi` string formatından sayısala çevrildi  
- Eksik değerler dolduruldu (median / most frequent)  
- Sayısal değişkenler standardize edildi  
- Kategorik değişkenler One-Hot Encoding ile sayısala çevrildi  
  
---

## 🚀 Çalıştırma
https://colab.research.google.com/drive/1mnjk1skQCUmnt6p0TWLED00k1BPdi7Pm?usp=sharing
