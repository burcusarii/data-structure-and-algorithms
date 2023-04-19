## <span style="color:darkblue">Insertion Sort Ödevi</span>

<hr>

#### <span style="color:darkred">Soru 1</span>
[22,27,16,2,18,6] -> Insertion Sort

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

2. Big-O gösterimini yazınız.

3. Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.
.


#### <span style="color:darkred">Cevap 1</span>
1.
- [22,27,16,2,18,6] --------- n sayı bulunur.
- [2,27,16,22,18,6] --------- (2 ile 22 yer değiştirdi.) (n-1 sorgulama)
- [2,6,16,22,18,27] --------- (6 ile 27 yer değiştirdi.)  (n-2 sorgulama)
- [2,6,16,18,22,27] --------- (18 ile 22 yer değiştirdi.) (n-3 sorgulama, son sorgulama olduğu için 1 alınır.)

<br>

2. Toplam yapılan sorgulama;

    n+(n-1)+(n-2)+ 1 = n(n+1)/2 = (n^2 + n) / 2 yapar.

    en yüksek kat sayı n^2 olduğu için;
    <span style="color:darkred; font-weight: bold">Big-O: *O(n^2)*</span>
    
<br>

3. 18 sayısı için sorgulama yapıldığında sayı dizinin ortasında olduğu için;
    Time Complexity:     <span style="color:darkred; font-weight: bold">Average Case.</span>

<hr>

#### <span style="color:darkred">Soru 1</span>

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

#### <span style="color:darkred">Cevap 1</span>

1. [7,3,5,8,2,9,4,15,6] (başlangıç dizisi)
2. [2,3,5,8,7,9,4,15,6]
3. [2,3,4,8,7,9,5,15,6]
4. [2,3,4,5,7,9,8,15,6]
5. [2,3,4,5,6,9,8,15,7]