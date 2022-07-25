# Proje 1 (insertion sort projesi)

[22,27,16,2,18,6]

a) Yukarı verilen dizinin insertion sort türüne göre aşamalarını yazınız.

  [2,27,16,22,18,6] n-1
  [2,6,16,22,18,27] n-2
  [2,6,16,18,22,27] 1

b) Big-O gösterimini yazınız.

  Bu dizinin Big-O notasyonu n(n+1)/2 işleminden ve kat sayıların önemsizliği ve dominant olanın yazılacağından n^2 şeklindedir. Yani O(n^2).

c) Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
  
    Average case: dizinin ortalama sıralanması : O(n^2)
    Worst case: dizinin tersten sıralı olması : O(n^2)
    Best case: dizinin sıralı olması : O(n)

d) Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

  18 sayısının ortada olması average case kapsamına girer.

e) [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
  
  1) [2,3,5,8,7,9,4,15,6]
  2) [2,3,4,8,7,9,5,15,6]
  3) [2,3,4,5,7,9,8,15,6]
  4) [2,3,4,5,6,9,8,15,7]
