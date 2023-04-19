## <span style="color:darkblue">Merge Sort Ödevi</span>

<hr>

#### <span style="color:darkred">Soru</span>

[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

#### <span style="color:darkred">Cevap 1</span>

1. [16,21,11] - [8,12,22]
2. [16,21] [11] - [8,12] [22]
3. [16] [21] [11] - [8] [12] [22]
4. [16,21] [11] - [8,12] [22]
5. [11,16,21] - [8,12,22]
6. [8,11,12,16,21,22]

- Big-O : O(nlogn)