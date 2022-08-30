# Insertion-Sort-Projesi
https://app.patika.dev/edgucation

[22,27,16,2,18,6] -> dizisinin

1. Insertion Sort türüne göre aşamalar;

    n -> [2,27,16,22,18,6] // 22 ile 2 değişir

    n-1 -> [2,6,16,22,18,27] // 27 ile 6 değişir

    n-2 -> [2,6,16,22,18,27] // değişim olmaz
    
    n-3 -> [2,6,16,18,22,27] // 22 ile 18 değişir
    
    1 -> [2,6,16,18,22,27] // Sıralama tamamlandı

2. Big-O gösterimi;

    n + (n-1) + (n-2) + (n-3) + 1 => n(n-1)/2 => ( n^2 + n )/ 2 => O(n^2)
    
3. Time Complexity:
    Average case: Aradığımız sayının ortada olması -> O(logn)
    Worst case: Aradığımız sayının sonda olması -> O(n^2)
    Best case: Aradığımız sayının dizinin en başında olması -> O(n)    

4. Dizi sıralandıktan sonra 18 sayısı avarage case kapsamına girer.

5. [7,3,5,8,2,9,4,15,6]  dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
 
     n) [2,3,5,8,7,9,4,15,6] // 7 ile 2 yer değiştirdi
     
     n-1) [2,3,5,8,7,9,4,15,6] // 3 sabit kaldı
     
     n-2) [2,3,4,8,7,9,5,15,6] // 5 ile 4 yer değiştirdi
     
     n-3)  [2,3,4,5,7,9,8,15,6] // 8 ile 5 yer değiştirdi
     
     n-4)  [2,3,4,5,6,9,8,15,7] // 7 ile 6 yer değiştirdi
