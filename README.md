## Proje-1
1. Insertion Sort 

[22,27,16,2,18,6] dizisini ınsortion sort algoritması ile çalıştırırsak, başlangıç elemanı 27 seçilir. 27 ve 22 kıyaslanarak küçük olan sola büyük olan sağa yazılır. Bu durumda 27, 22 den büyük olduğu için sağda kalır.

Dizinin 3. elemanı 16, 22 ve 27 ile kıyaslanır. Küçük olduğu için sola geçer.
[16,22,27,2,18,6] dizinin yeni hali bu şekildedir.

Dizinin 4. elemanı 2 kıyaslanıp sola yazılır.
[2,16,22,27,18,6] dizinin yeni hali bu şekildedir.

Dizinin 5. elemanı 18 kıyaslanıp sola yazılır.
[2,16,18,22,27,6] dizinin yeni hali bu şekildedir.

Dizinin son elemanı 6 da kıyaslanıp sola yazılır.
[2,6,16,18,22,27] son olarak sıralı dizi elde edilir.

18 sayısı dizinin en son basamağından bir önce yerleştirildiği için Worst Case'e yakındır ama Average Case senaryosu kapsamına girer.

Big O Notation = İşlem sayısı n, n-1, n-2...1 şeklinde olacağından, işlem sayısı toplamı n.(n+1)/2; dominant faktörü n²'dir. O(n²)

2. Selection Sort

[7,3,5,8,2,9,4,15,6] dizisini Selection Sort algoritması ile çalıştırdığımızda ilk 4 adımı:

En küçüğü bulup baştaki elemanla yer değiştirerek çalıştığı için;

2 ile 7 yer değişecek [2,3,5,8,7,9,4,15,6]
4 ile 5 yer değişecek [2,3,4,8,7,9,5,15,6]
5 ile 8 yer değişecek [2,3,4,5,7,9,8,15,6]
6 ile 7 yer değişecek [2,3,4,5,6,9,8,15,7] yeni dizi bu şekilde olur.



