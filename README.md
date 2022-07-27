[22,27,16,2,18,6] -> Insertion Sort

# 1. Soru
[22,27,16,2,18,6]
[2,27,16,22,18,6]   # 22 <> 2
[2,6,16,22,18,27]   # 27 <> 6
[2,6,16,18,22,27]   # 22 <> 18

[2,6,16,18,22,27] Son Hali


# 2.Soru Big-O gösterimini yazınız.
n+(n-1)+(n-2)...+1 ==> n.(n+1)/2 ==> O(n^2) => O(6^2) = 36

# 3. Soru
Time Complexity: 

Average case: Aradığımız sayının ortada olması,
[2,6,16,18,22,27] ==> 16,18 gibi sayılar dizinin ortasında bulunduğu için Average Case grubuna girmektedir.


Worst case: Aradığımız sayının sonda olması, 
[2,6,16,18,22,27] ==> 22,27 gibi sayılar dizinin sonunda bulunduğu için Worst Case grubuna girmektedir.


Best case: Aradığımız sayının dizinin en başında olması.
[2,6,16,18,22,27] ==> 2,6 gibi sayılar dizinin başında bulunduğu için Best Case grubuna girmektedir.


# 4.Soru
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

[2,6,16,18,22,27]    18 Sayı dizinin ortasında bulunduğu için Average Case kapsamındadır


# [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

1. Adım => [2,3,5,8,7,9,4,15,6]  7 <> 2
2. Adım => [2,3,4,8,7,9,5,15,6]  5 <> 4 (Burada 2' den sonra en küçük 3 olsa da yerinde olduğu için ellemedim(adım olarak saymadım))
3. Adım => [2,3,4,5,7,9,8,15,6]  8 <> 5
4. Adım => [2,3,4,5,6,9,8,15,7]  7 <> 6 




