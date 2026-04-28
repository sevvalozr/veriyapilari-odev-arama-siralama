Veri Yapıları Ödevi
Arama ve Sıralama Algoritmaları

Proje Bilgileri
Ders: Veri Yapıları
Teslim Eden Öğrenci: Şevval
Teslim Tarihi: 20.04.2026

Proje Hakkında
Bu proje, Veri Yapıları dersi kapsamında hazırlanmıştır. Projede temel arama ve sıralama algoritmaları Python programlama dili kullanılarak geliştirilmiştir.
Bu ödevin temel amacı, algoritmaların nasıl çalıştığını öğrenmek, farklı yöntemleri karşılaştırmak ve performans açısından değerlendirmektir. Ayrıca diziler ve listeler üzerinde işlem yapma becerisi geliştirilmiştir.
Bu proje sayesinde:


Arama algoritmaları uygulanmıştır


Sıralama algoritmaları uygulanmıştır


Algoritmaların çalışma mantığı incelenmiştir


Big-O zaman karmaşıklıkları öğrenilmiştir


Python ile fonksiyon kullanımı geliştirilmiştir



Kullanılan Algoritmalar
Arama Algoritmaları


Linear Search


Binary Search


Sıralama Algoritmaları


Bubble Sort


Selection Sort


Insertion Sort


Merge Sort


Quick Sort



Dosya Yapısı
veri-yapilari-odev-arama-siralama/
main.py
arama.py
siralama.py
README.md

Arama Algoritmaları
1. Linear Search
Linear Search algoritması, listedeki elemanları baştan sona tek tek kontrol eder. Aranan değer bulunana kadar listedeki tüm elemanlar sırayla incelenir. Eğer aranan değer bulunursa bulunduğu indeks numarası döndürülür. Eğer listede yoksa -1 değeri döndürülür.
Bu yöntem en temel arama algoritmalarından biridir. Küçük veri kümelerinde kullanımı kolaydır ve sıralı liste gerektirmez.
Avantajları


Kodlaması kolaydır


Sıralı liste gerektirmez


Küçük verilerde etkilidir


Dezavantajları


Büyük listelerde yavaş çalışır


Her eleman tek tek kontrol edilir



2. Binary Search
Binary Search algoritması yalnızca sıralı listelerde kullanılabilir. Arama işlemi sırasında listenin ortasındaki eleman kontrol edilir. Eğer aranan değer ortadaki eleman ise sonuç bulunur. Eğer aranan değer büyükse sağ tarafa, küçükse sol tarafa geçilir.
Bu işlem liste her adımda ikiye bölündüğü için oldukça hızlıdır.
Avantajları


Çok hızlı çalışır


Büyük veri kümelerinde etkilidir


Dezavantajları


Liste sıralı olmak zorundadır


Önce sıralama işlemi gerekebilir



Sıralama Algoritmaları
1. Bubble Sort
Bubble Sort algoritmasında yan yana bulunan elemanlar karşılaştırılır. Soldaki eleman büyükse yer değiştirme işlemi yapılır. Her tur sonunda en büyük eleman listenin sonuna geçer.
Avantajları


Öğrenmesi kolaydır


Basit mantığa sahiptir


Dezavantajları


Büyük listelerde yavaştır


Çok fazla karşılaştırma yapar



2. Selection Sort
Selection Sort algoritmasında her turda listedeki en küçük eleman bulunur ve listenin başına alınır. Daha sonra kalan elemanlar için aynı işlem devam eder.
Avantajları


Kod yapısı basittir


Bellek kullanımı düşüktür


Dezavantajları


Büyük listelerde yavaştır


Sabit sayıda çok karşılaştırma yapar



3. Insertion Sort
Insertion Sort algoritmasında elemanlar tek tek alınır ve doğru konuma yerleştirilir. Kart dizer gibi çalışır. Küçük veri kümelerinde oldukça kullanışlıdır.
Avantajları


Küçük listelerde hızlıdır


Kısmen sıralı listelerde başarılıdır


Dezavantajları


Büyük listelerde performansı düşer



4. Merge Sort
Merge Sort algoritmasında liste iki parçaya ayrılır. Her parça kendi içinde sıralanır ve daha sonra birleştirilir. Böl ve yönet mantığıyla çalışan güçlü algoritmalardan biridir.
Avantajları


Büyük veri kümelerinde hızlıdır


Her durumda kararlı performans verir


Dezavantajları


Ek bellek kullanır


Kod yapısı diğerlerine göre daha uzundur



5. Quick Sort
Quick Sort algoritmasında bir pivot eleman seçilir. Pivot değerinden küçük olanlar sola, büyük olanlar sağa alınır. Daha sonra alt listelerde aynı işlem tekrar edilir.
Avantajları


Genellikle çok hızlıdır


Büyük verilerde başarılıdır


Dezavantajları


Kötü pivot seçimi performansı düşürür



Algoritmaların Karşılaştırılması
AlgoritmaTürOrtalama KarmaşıklıkEn Kötü DurumLinear SearchAramaO(n)O(n)Binary SearchAramaO(log n)O(log n)Bubble SortSıralamaO(n²)O(n²)Selection SortSıralamaO(n²)O(n²)Insertion SortSıralamaO(n²)O(n²)Merge SortSıralamaO(n log n)O(n log n)Quick SortSıralamaO(n log n)O(n²)

Big-O Zaman Karmaşıklıkları Tablosu
AlgoritmaEn İyi DurumOrtalama DurumEn Kötü DurumLinear SearchO(1)O(n)O(n)Binary SearchO(1)O(log n)O(log n)Bubble SortO(n)O(n²)O(n²)Selection SortO(n²)O(n²)O(n²)Insertion SortO(n)O(n²)O(n²)Merge SortO(n log n)O(n log n)O(n log n)Quick SortO(n log n)O(n log n)O(n²)

Programı Çalıştırma
Terminal veya komut istemcisi açılır. Proje klasörüne girilir. Daha sonra aşağıdaki komut çalıştırılır.
python main.py

Sonuç
Bu projede temel arama ve sıralama algoritmaları başarıyla uygulanmıştır. Algoritmaların çalışma mantıkları öğrenilmiş, farklı yöntemlerin performansları karşılaştırılmış ve Big-O zaman karmaşıklıkları incelenmiştir.
Bu çalışma sayesinde algoritma mantığı, problem çözme becerisi ve Python programlama pratiği geliştirilmiştir.
