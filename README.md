# Proje 1

* [22,27,16,2,18,6] -> Insertion Sort

1. Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.

* 2 ile 22 yer değişir.
* 6 ile 27 yer değişir.
* 18 ile 22 yer değişir.
* Sonuç -> [2,6,16,18,22,27]

2. Big-O gösterimini yazınız.
    * İlk turda n elemanımız olsun ve biz en küçüğü bulmak n elemanı kontrol ederiz. Sonrasında ise geri kalan elemanları kontrol ederiz yani n-1 elamana bakarız. Böyle devam eder ve n+(n-1)+(n-2).. şeklinde ilerler. Yani 1'den n'e kadar olan sayıların toplamından (n.(n-1))/2 gelir buradan da Big-O Notation'umuz O(n2) olur yani O(62) yani O(36)'dır.

3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
    * Avarage Case: 16,18   
    * Worst Case : 27   
    * Best Case: 2

4.  Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
    * Average Case

5. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

    * 2 ile 7 yer değiştirir.
    * 5 ile 4 yer değişir.
    * 5 ile 8 yer değişir.
    * 6 ile 7 yer değişir.