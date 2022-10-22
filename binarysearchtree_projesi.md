# patikadev_veriyapilarivealgoritmalar
# Binary Search Tree Projesi
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.
## Binary Search Tree Aşamaları

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisini soldan okumaya başlıyoruz. İkili arama ağacı, her düğümün solundaki koldan ulaşılabilecek bütün verilerin düğümün değerinden küçük, sağ kolundan ulaşılabilecek verilerin değerinin o düğümün değerinden büyük olmasını şart koşar.
```
7 = root
```
```
  7
 /   5 elemanı 7'den küçük olduğu için sol tarafa ekledik.
5

```
```
    7
   /
  5
 /
1
```
```
    7
   / \
  5   8
 /
1
```
```
    7
   / \
  5   8
 /
1
 \
  3
```
```
    7
   / \
  5   8
 / \
1   6
 \
  3
```
```
       7
      / \
     5   8
    / \
   1   6
 /  \
0    3
```
```
       7
      / \
     5   8
    / \   \
   1   6   9
 /  \
0    3
```
```
       7
      / \
     5   8
    / \   \
   1   6   9
 /  \
0    3
      \
       4
```
```
       7
      / \
     5   8
    / \   \
   1   6   9
 /  \
0    3
    /  \
   2    4
```
