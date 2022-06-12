


# Insertion sort project

## [22, 27 16, 2, 18, 6]

### 1. soru Aşamalar: 

* [2,27,16,22,18,6]
* [2,6,16,22,18,27]
* [2,6,16,22,18,27] -> 16 için sıralama değişmedi
* [2,6,16,18,22,27]
* [2,6,16,18,22,27] -> 22 ile 27 karşılaştırmasında sıra değişmedi


### 2. Soru Big(o) Notation 

Big(O) = (n^2) = (n*(n-1)*(n-2)*....) 1'den n'e kadar olan sayıların toplamı n*(n-1)/2 dominant olan n^2 olduğu için n^2 kadar işlem yapılacaktır.

### 3. Soru Time complexity: 

- average case: ortadaki sayıyı bulmak için (örn=3. sıradaki) n*(n-1*(n-2) kadar işlem yapılacağı için complexity yine n^2 olacaktır.
- worst case: (n^2)
- best case: n (dizede n tane sayı varsa n kadar bakacaktır)

### 4. Soru 

Dizinin ortalarında olduğu için 18 sayısı average case kapsamına girmekedir.


## [7,3,5,8,2,9,4,15,6] ilk 4 adımını yazınız.

### Aşamalar:

- [2,3,5,8,7,9,4,15,6] - en küçük elemanı bulup en başa yazar (n kadar süre alır)
- [2,3,5,8,7,9,4,15,6] - 2 nin sağında kalanlar arasında en küçüğü 2den sonraki slota yazar. bu adımda 3 en küçük olduğu için yer değiştirme yapılmaz
- [2,3,4,8,7,9,5,15,6] - 3ün sağında kalan dizide en küçük eleman aranır (4) ve 3ün sağına yazılır ( 5 ile 4 yer değiştirir)
- [2,3,4,5,7,9,8,15,6] 4ün sağında kalanlar arasında en küçük bulunur 4ün yanına yazılır. 8 ile 5 yer değiştirir.
- [2,3,4,5,6,9,8,15,7] - 5 in sağında kalan dizi içerisinde en küçük 6 olduğu için 6 ile 7 nin yerini değiştirir.