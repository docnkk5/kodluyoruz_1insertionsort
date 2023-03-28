# kodluyoruz_1insertionsort
veri yapıları ve algoritmalar proje ödevi 


 



[22,27,16,2,18,6] -> Insertion Sort
 
Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.


 [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
 
 

Dizinin en küçük elemanını bulmak için ilk eleman 7 ile geri kalan tüm elemanları (3, 5, 8, 2, 9, 4, 15, 6) karşılaştırıyoruz. En küçük eleman 2 olduğu için, 2 ile ilk eleman olan 7'nin yerini değiştiriyoruz [2, 3, 5, 8, 7, 9, 4, 15, 6].

İkinci elemanı (3) alıp geri kalan elemanları (5, 8, 7, 9, 4, 15, 6) ile karşılaştırıyoruz. En küçük eleman yine 2 olduğu için, ikinci eleman olan 3 yerinde sabit şekilde kalıyor [2, 3, 5, 8, 7, 9, 4, 15, 6].

Üçüncü elemanı (5) alıp geri kalan elemanları (8, 7, 9, 4, 15, 6) ile karşılaştırıyoruz. En küçük eleman bu sefer 4 olduğu için, 4 ile üçüncü eleman olan 5'in yerini değiştiriyoruz [2, 3, 4, 8, 7, 9, 5, 15, 6].

Dördüncü elemanı (8) alıp geri kalan elemanları (7, 9, 5, 15, 6) ile karşılaştırıyoruz. En küçük eleman 5 olduğu için, 5 ile dördüncü eleman olan 8'in yerini değiştiriyoruz: [2, 3, 4, 5, 7, 9, 8, 15, 6].

Big-O  en kötü durumda n kare  adım gerektirir.
 [7, 3, 5, 8, 2, 9, 4, 15, 6] dizisi için Selection Sort algoritması 9üssü 2 den 81 adım dır 
 
 



 [22, 27, 16, 2, 18, 6]

İlk adımda, ikinci eleman olan 27, ilk elemandan 22'den daha büyük olduğu için yerleri değiştirilir ve dizi şöyle olur [27, 22, 16, 2, 18, 6]

Üçüncü eleman olan 16, birinci elemandan 27'den küçük olduğu için ilk elemanın soluna yerleştirilir: [16, 27, 22, 2, 18, 6]

Dördüncü eleman olan 2, ilk üç elemandan daha küçük olduğu için dizinin en başına yerleştirilir [2, 16, 27, 22, 18, 6]

Beşinci eleman olan 18, ilk dört elemandan daha büyük olduğu için 27'nin soluna yerleştirilir [2, 16, 18, 27, 22, 6]

Altıncı eleman olan 6, ilk dört elemandan daha küçük olduğu için 2'nin sağına yerleştirilir [2, 6, 16, 18, 27, 22]

Sonuç olarak, dizi sıralanmış hale gelir: [2, 6, 16, 18, 22, 27]

Verilen dizi 6 eleman içerdiği için Insertion Sort'un Big-O gösterimi O(nkare) olur.




Verilen dizi sıralandıktan sonra 18 sayısı, Best case senaryosuna girmez. Çünkü 18 sayısı, verilen dizinin en başında yer almamaktadır. En iyi durum senaryosu, verilen dizinin zaten sıralı olmasıdır. Ancak bu durumda bile, Insertion Sort algoritmasının çalışma zamanı O(n kare) olacaktır.

Verilen dizi sıralandıktan sonra 18 sayısı, Worst case senaryosuna girer, çünkü bu sayı, dizinin son bölümünde yer almaktadır.



