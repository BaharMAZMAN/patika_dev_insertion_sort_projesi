# patika_dev_insertion_sort_projesi
Proje 1
[22,27,16,2,18,6] -> Insertion Sort
Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Aşama 1 Verilen dizinin en küçük elemanı bul.
Aşama 2 Bulunan en küçük elemanı 2. sıradaki eleman ile yer değiştir.----->[2,27,16,22,18,6]
Aşama 3 İkinci en küçük elemanı bul ve 2.sıradaki eleman ile yer değiştir. 2. sıradaki eleman en küçükse dokunmadan üçüncü küçük elemanı bul döngüyü devam ettir.
Aşama 4 [2,6,16,22,18,27]------>üçüncü elaman 16 sabit kalıyor. dördüncü elamanı 18 22 ile yer değiştirir. [2,6,16,18,22,27]-----> insertion sort tamamlandı.

Big-O gösterimini yazınız.-----> O(n^2)

Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

Dizi sıralandıktan sonra [2,6,16,18,22,27] 18 ortada olacağından Average case olur.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

Aşama 1 [2,3,5,8,7,9,4,15,6]
Aşama 2 [2,3,5,8,7,9,4,15,6] ikinci en küçük eleman doğru yerde olduğu için aynı kaldı.
Aşama 3 [2,3,4,8,7,9,5,15,6]
Aşama 4 [2,3,4,5,7,9,8,15,6]
Aşama 5 [2,3,4,5,6,9,8,15,7]

www.patika.dev 
