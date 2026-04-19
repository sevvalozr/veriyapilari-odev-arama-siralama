# Veri Yapıları Ödevi  
## Arama ve Sıralama Algoritmaları

## Proje Hakkında

Bu proje, Veri Yapıları dersi kapsamında hazırlanmıştır.  
Amaç, temel arama ve sıralama algoritmalarını öğrenmek, Python dili ile kodlamak ve çalışma mantıklarını anlamaktır.

Bu projede hem algoritmaların kodları yazılmış hem de zaman karmaşıklıkları incelenmiştir.

---

## Kullanılan Programlama Dili

- Python

---

## Kullanılan Algoritmalar

### Arama Algoritmaları

- Linear Search
- Binary Search

### Sıralama Algoritmaları

- Bubble Sort
- Selection Sort
- Insertion Sort
- Merge Sort
- Quick Sort

---

# Arama Algoritmaları

## 1. Linear Search

Listedeki elemanlar baştan sona tek tek kontrol edilir.  
Aranan değer bulunduğunda indeks numarası döndürülür.

### Örnek:

```python
[4, 7, 2, 9]
Aranan = 2
Sonuç = 2
Zaman Karmaşıklığı:
Best Case: O(1)
Worst Case: O(n)
2. Binary Search

Sadece sıralı listelerde çalışır.
Liste ortadan ikiye bölünerek arama yapılır.

Örnek:
[1, 3, 5, 7, 9]
Aranan = 7
Sonuç = 3
Zaman Karmaşıklığı:
O(log n)
Sıralama Algoritmaları
1. Bubble Sort

Yan yana elemanlar karşılaştırılır. Büyük olan sağ tarafa geçer.

Örnek:
[5,2,1]
Sonuç = [1,2,5]
Zaman Karmaşıklığı:
O(n²)
2. Selection Sort

Her turda en küçük eleman bulunur ve başa alınır.

Zaman Karmaşıklığı:
O(n²)
3. Insertion Sort

Elemanlar tek tek uygun yere yerleştirilir.

Zaman Karmaşıklığı:
O(n²)
4. Merge Sort

Liste parçalara ayrılır, sıralanır ve birleştirilir.

Zaman Karmaşıklığı:
O(n log n)
5. Quick Sort

Bir pivot seçilir. Küçükler sola, büyükler sağa ayrılır.

Zaman Karmaşıklığı:
Ortalama O(n log n)
Algoritmaların Karşılaştırılması
Algoritma	Tür	Zaman Karmaşıklığı
Linear Search	Arama	O(n)
Binary Search	Arama	O(log n)
Bubble Sort	Sıralama	O(n²)
Selection Sort	Sıralama	O(n²)
Insertion Sort	Sıralama	O(n²)
Merge Sort	Sıralama	O(n log n)
Quick Sort	Sıralama	O(n log n)
Dosya Yapısı
veri-yapilari-odev-arama-siralama/
│── main.py
│── arama.py
│── siralama.py
│── README.md
Programı Çalıştırma
python main.py
Örnek Çıktı
Liste: [5,2,8,1,3]

Bubble Sort:
[1,2,3,5,8]

Linear Search (8):
2

Binary Search (3):
2
Sonuç

Bu projede temel arama ve sıralama algoritmaları başarıyla uygulanmıştır.
Algoritmaların mantığı öğrenilmiş ve performans farkları incelenmiştir.
