# patikadev_veriyapilarivealgoritmalar
Patika.dev Veri Yapıları ve Algoritmalar Eğitimi bitirme projesidir.
# Merge Sort Projesi
[16,21,11,8,12,22] -> Merge Sort

- 1.Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
- 2.Big-O gösterimini yazınız.

## 1.Yukarıdaki dizinin sort türüne göre aşamaları
 ```
 Adım 1: [16,21,11,8,12,22] dizisini ikiye böleriz.
 Adım 2: [16,21,11] | [8,12,22] dizileri tekrar ikiye böleriz.
 Adım 3: [16,21] [11] | [8,12] [22] dizileri <=2 eleman sayısına ulaştığı için bölme işlemini durdururuz ve dizileri kendi içerisinde sıralarız.
 Adım 4: [16,21] [11] | [8,12] [22] dizileri birleştiririz.
 Adım 5: [11,16,21]   | [8,12,22]   dizileri birleştiririz.
 Adım 6: [8,11,12,16,21,22] dizi sıralanmıştır.
 ```
 ## 2.Big-O gösterimi
  ```
  O(n*logn)
  ```
