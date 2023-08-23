[22,27,16,2,18,6]-> Insertion Sort

 * Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
 * Big-O gösterimini yapınız.
 * Time Complexity;

Average case: Aradığımız sayının ortada olması,

Worst case: Aradığımız sayının sonda olması,

Best case: Aradığımız sayının dizinin en başında olması.

 * Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

 * - [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

Aşamalar:

[2,27,16,22,18,6]

[2,6,16,22,18,27]

[2,6,16,18,22,27]

Big-O notation;

Worst case: n+(n-1)+(n-2)+.....+1 = (n)*(n+1)/2 --> O(n²)

Average Case: O(n²)

Best Case: O(n)

Time Complexity;

Worst case: [27,22,18,16,6,2]

Avarage Case: [2,6,16,18,22,27]

Best case: [2,6,16,18,22,27]

Dizi sıralandıktan sonra 18 sayısı ortada olduğu için average case kapsamına girer.

İlk dört adım;

Bİrinci adım: [2,3,5,8,7,9,4,15,6]

İkinci adım: [2,3,4,8,7,9,5,15,6]

Üçüncü adım: [2,3,4,5,7,9,8,15,6]

Dördüncü adım: [2,3,4,5,6,9,8,15,7]