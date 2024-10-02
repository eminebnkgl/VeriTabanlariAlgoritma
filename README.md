# VeriTabanlariAlgoritma
Veri Tabanları ve Algoritma PROJE 1
[22,27,16,2,18,6] -> Insertion Sort

[22,27,16,2,18,6] (27>22 oldugu için işlem yapılmaz)
[16,22,27,2,18,6] (16 küçük oldugu için önce 27 sonra 22 ile yer değiştirir.
[2,16,22,27,18,6] (2'de 3 hamle ile başa geçer)
[2,16,18,22,27,6] (18, 2 hamle ile sola kayar, 16<18 olduğu için sola kaydırma işlemi biter.)
[2,6,16,18,22,27] (6'da öncekilerden küçük olmayacak şekilde sola kaydırılır)

Insertion Sort Worstcase: [n*(n+1)]/2 -> Big O(n²)

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer?
Insertion sort sonucunda '18' değeri dizinin ortasında bulunacağı için time complexity'si 'Average Case' olur.


[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
1.	[2,3,5,8,7,9,4,15,6] (En küçük değer 2’dir. 7 ile yer değiştirilir.)
2.	[2,3,5,8,7,9,4,15,6] (3 doğru yerde olduğu için hiç bir işlem gerçekleştirilmez.)
3.	[2,3,4,8,7,9,5,15,6] (5 ile diğer küçük değerin (4’ün) yeri değiştirilir.)
4.	[2,3,4,5,7,9,8,15,6] (8 ile diğer küçük değerin (5’in) yeri değiştirilir.)
4.	adımında dizi elemanları bu şekilde sıralanır -> [2,3,4,5,7,9,8,15,6]




