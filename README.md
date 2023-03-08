## SELECTION SORT PORJESİ
[22,27,16,2,18,6] -> Insertion Sort

### Yukarı verilen dizinin sort türüne göre aşamaları.
1. Aşama : İlk önce dizinin ikinci sayısı ile bir öndekini kıyaslıyoruz, 27 22'den büyük olduğu için sıralama değişmiyor.
[22,27,16,2,18,6]

2. Aşama : Sıradaki sayı olan 16'ya geçiyoruz, kendinden bir önceki sayı 27'den küçük olduğu için sola geçiyor sonra 22 ile kıyaslıyoruz, ondan da küçük olduğu için onun da önüne geçiyor.
[16,22,27,2,18,6]

3. Aşama : Sıradaki sayı olan 2'ye geçiyoruz, kendinden bir önceki sayı 27'den küçük olduğu için sola geçiyor sonra 22 ve 16 ile kıyaslıyoruz, hepsinden küçük olduğu için en başa geçiyor.
[2,16,22,27,18,6]

4. Aşama : Sıradaki sayı olan 18'e geçiyoruz, kendinden bir önceki sayı 27'den küçük olduğu için sola geçiyor sonra 22 ve 16 ile kıyaslıyoruz, 22'den küçük, 16'dan büyük olduğu için ikisinin arasında yer alıyor.
[2,16,18,22,27,6]

5. Aşama : Sıradaki sayı olan 6'ya geçiyoruz,sonra 27,22,18,16 ve 2 ile kıyaslıyoruz, 27,22,18 ve 16'dan üçük olduğu için onların soluna 2'den büyük olduğu için sağına geçiyor ve sıralama işlemi bitiyor.
[2,6,16,18,22,27]

Big-O gösterimi  O(n^2)
---
**Time Complexity:** Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız
Average case: Aradığımız sayının ortada olması Worst case: Aradığımız sayının sonda olması Best case: Aradığımız sayının dizinin en başında olması.

[2,6,16,18,22,27] diziliminde 18 sayısı ortadadır.

**Cevap :** Average case

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımı.
---

1. Aşama : Önce dizideki en küçük sayıyı buluyoruz. En küçük sayı 2 olduğu için en baştaki 7 ile yer değiştiriyor.
[2,3,5,8,7,9,4,15,6]

2. Aşama : 2 ve 3 sıralı olduğu için sonraki sayılar arasından en küçük olan 4 ile 5'in yeri değişiyor.
[2,3,4,8,7,9,5,15,6]

3. Aşama : 4'den sonraki sayılar için aynı işlemi yapıyoruz, en küçük olan 5 ile 8 yer değiştiriyor.
[2,3,4,5,7,9,8,15,6]

4. Aşama : 5'den sonraki sayılar için aynı işlemi yapıyoruz, en küçük olan 6 ile 7 yer değiştiriyor.
[2,3,4,5,6,9,8,15,7]
