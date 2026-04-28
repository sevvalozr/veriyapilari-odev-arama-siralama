# VERİ YAPILARI ÖDEVİ  
# Arama ve Sıralama Algoritmaları

---

# PROJE BİLGİLERİ  

Ders: Veri Yapıları  
Teslim Eden Öğrenci: Şevval Özer
Teslim Tarihi: 20.04.2026  

---

# PROJE HAKKINDA  

Bu proje Veri Yapıları dersi kapsamında hazırlanmıştır. Projede temel arama ve sıralama algoritmaları Python dili kullanılarak geliştirilmiştir.  

Ödevin amacı:  
- Arama algoritmalarını öğrenmek  
- Sıralama algoritmalarını anlamak  
- Algoritmaların çalışma mantığını kavramak  
- Big-O zaman karmaşıklıklarını incelemek  
- Algoritmaların performanslarını karşılaştırmak  

---

# KULLANILAN ALGORİTMALAR  

## Arama Algoritmaları  
- Linear Search  
- Binary Search  

## Sıralama Algoritmaları  
- Bubble Sort  
- Selection Sort  
- Insertion Sort  
- Merge Sort  
- Quick Sort  

---

# ARAMA ALGORİTMALARI  

## 1. Linear Search  

Linear Search algoritması listedeki elemanları baştan sona tek tek kontrol eder. Aranan değer bulunana kadar tüm liste taranır. Bulunduğu anda indeks döndürülür, bulunamazsa -1 döner.  

### Avantajları  
- Sıralama gerektirmez  
- Basit yapılıdır  

### Dezavantajları  
- Büyük listelerde yavaştır  

### Big-O  
- En iyi: O(1)  
- Ortalama: O(n)  
- En kötü: O(n)  

---

## 2. Binary Search  

Binary Search sadece sıralı listelerde çalışır. Liste sürekli ikiye bölünerek arama yapılır. Ortadaki değer ile karşılaştırma yapılır.  

### Avantajları  
- Çok hızlıdır  
- Büyük veri setlerinde etkilidir  

### Dezavantajları  
- Liste sıralı olmalıdır  

### Big-O  
- En iyi: O(1)  
- Ortalama: O(log n)  
- En kötü: O(log n)  

---

# SIRALAMA ALGORİTMALARI  

## 1. Bubble Sort  

Yan yana elemanlar karşılaştırılır ve büyük olan sağa alınır. Her turda en büyük eleman sona gider.  

### Big-O  
- En iyi: O(n)  
- Ortalama: O(n²)  
- En kötü: O(n²)  

---

## 2. Selection Sort  

Her turda en küçük eleman bulunur ve başa alınır.  

### Big-O  
- En iyi: O(n²)  
- Ortalama: O(n²)  
- En kötü: O(n²)  

---

## 3. Insertion Sort  

Elemanlar tek tek doğru yerine yerleştirilir. Kart dizme mantığına benzer.  

### Big-O  
- En iyi: O(n)  
- Ortalama: O(n²)  
- En kötü: O(n²)  

---

## 4. Merge Sort  

Liste ikiye bölünür, sıralanır ve tekrar birleştirilir.  

### Big-O  
- En iyi: O(n log n)  
- Ortalama: O(n log n)  
- En kötü: O(n log n)  

---

## 5. Quick Sort  

Bir pivot seçilir. Küçükler sola, büyükler sağa ayrılır. Alt listeler tekrar aynı şekilde sıralanır.  

### Big-O  
- En iyi: O(n log n)  
- Ortalama: O(n log n)  
- En kötü: O(n²)  

---

# ALGORİTMALARIN KARŞILAŞTIRILMASI  

| Algoritma | Tür | Ortalama Karmaşıklık | En Kötü Durum |
|----------|-----|----------------------|---------------|
| Linear Search | Arama | O(n) | O(n) |
| Binary Search | Arama | O(log n) | O(log n) |
| Bubble Sort | Sıralama | O(n²) | O(n²) |
| Selection Sort | Sıralama | O(n²) | O(n²) |
| Insertion Sort | Sıralama | O(n²) | O(n²) |
| Merge Sort | Sıralama | O(n log n) | O(n log n) |
| Quick Sort | Sıralama | O(n log n) | O(n²) |

---

# BIG-O ZAMAN KARMAŞIKLIĞI TABLOSU  

| Algoritma | En İyi Durum | Ortalama Durum | En Kötü Durum |
|----------|--------------|----------------|---------------|
| Linear Search | O(1) | O(n) | O(n) |
| Binary Search | O(1) | O(log n) | O(log n) |
| Bubble Sort | O(n) | O(n²) | O(n²) |
| Selection Sort | O(n²) | O(n²) | O(n²) |
| Insertion Sort | O(n) | O(n²) | O(n²) |
| Merge Sort | O(n log n) | O(n log n) | O(n log n) |
| Quick Sort | O(n log n) | O(n log n) | O(n²) |

---

# PROGRAMI ÇALIŞTIRMA  

Proje klasörüne girildikten sonra terminalde şu komut çalıştırılır:  

```bash
python main.py
