# Merge-Sort-Project

## [16,21,11,8,12,22] dizisinin Merge Sort a göre aşamalarını yazınız:

-                  [16,21,11,8,12,22]

-                [16,21,11] & [8,12,22]

-            [16,21] & [11] & [8,12] & [22]

-        [16] & [21] & [11] & [8] & [12] & [22]

-            [16,21] & [11] & [8,12] & [22]

-                [11,16,21] & [8,12,22]

-                  [8,11,12,16,21,22]

## Big-O gösterimini yazınız

- Her basamakta n işlem yapılıyor, toplamda log(n) basamak var:

- O(n*log(n))