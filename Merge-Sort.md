## [16,21,11,8,12,22] -> Merge Sort
 * Yukarıdaki dizinin sort türüne göre aşamalarını yazınız. 
 * Big-O gösterimini yazınız.
<hr>

- diziyi ortadan iki ye böldük 
[16,21,11]             [8,12,22]
- Tek eleman kalana kadar bölmeye devam

 [16,21]      [11]             [8,12]     [22]    

[16] [21]     [11]            [8] [12]    [22]  

- sıaralayıp birleştiriyoruz
[16][21]      [11]            [8] [12]    [22]  
ilk elemanlar en küçük oldugu için sırayla bakarak sıralama yapıp birleştir
 [11][16][21]                [8][12][22] 
ilk elemanlar en küçük oldugu için sırayla bakarak sıralama yapıp birleştir
 [11][8] 8 küçük o sekilde sıarala birleştir
 [8][11]
 16 12 sıarala birleştir
 21 22 sıarala birleştir
 
 [8][11][12][16][21][22]
 
 birleştiriyoeuz
 big-o = O(nlogn)
 
