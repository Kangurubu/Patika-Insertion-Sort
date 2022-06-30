# Patika-Insertion-Sort

This is for www.patika.dev project.

Q] [22,27,16,2,18,6] -> Insertion Sort
1-> Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
-1 [22,27,16,2,18,6] 22<27, değişiklik olmaz.

-2 [22,16,27,2,18,6] 27>16, 27 ve 16 yer değiştirir.
-2 [16,22,27,2,18,6] 22>16, 22 ve 16 yer değiştirir.
-2 [16,22,27,2,18,6] 16 listenin başında. Değişiklik olmaz.

-3 [16,22,2,27,18,6] 27>2, 27 ve 2 yer değiştirir
-3 [16,2,22,27,18,6] 22>2, 22 ve 2 yer değiştirir.
-3 [2,16,22,27,18,6] 16>2, 16 ve 2 yer değiştirir.
-3 [2,16,22,27,18,6] 2 listenin başında. Değişiklik olmaz.

-4 [2,16,22,18,27,6] 27>18, 27 ve 18 yer değiştirir.
-4 [2,16,18,22,27,6] 22>18, 22 ve 18 yer değiştirir.
-4 [2,16,18,22,27,6] 16<18, değişiklik olmaz.

-5 [2,16,18,22,6,27] 27>6, 27 ve 6 yer değiştirir.
-5 [2,16,18,6,22,27] 22>6, 22 ve 6 yer değiştirir.
-5 [2,16,6,18,22,27] 18>6, 18 ve 6 yer değiştirir.
-5 [2,6,16,18,22,27] 16>6, 16 ve 6 yer değiştirir.
-5 [2,6,16,18,22,27] 2<6, değişiklik olmaz.

2-> Big-O gösterimi O(n^2).

3-> Worst case olduğu zaman O(n). Aranan eleman listenin sonunda. Bu liste için 27 sayısı
    Average case olduğu zaman O(n) Aranan eleman listenin ortasında. Bu liste için 16 ve 18 sayıları
    Best case olduğu zaman O(1) Aranan eleman listenin başında. Bu liste için 2 sayısı
    
4-> 18 sayısı bu liste için average case




Q] [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
-> [3,7,5,8,2,9,4,15,6]
-> [3,5,7,8,2,9,4,15,6]
-> [3,5,7,2,8,9,4,15,6]
-> [3,5,2,7,8,9,4,15,6]
