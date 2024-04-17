# [22,27,16,2,18,6] -> Insertion Sort
# Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
- min = 2 -->    [2,27,16,22,18,6]
- min = 6 -->    [2,6,16,22,18,27]
- min = 16 -->   [2,6,16,22,18,27]
- min = 18 -->   [2,6,16,18,22,27] 

## Big-O gösterimini yazınız.
- n + (n-1) + (n-2) + (n-3) + ... + 1 = (n(n+1))/2 = (n^2+n)/2 ==> O(n^2)

## Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız.
1) Average case: Aradığımız sayının ortada olması
2) Worst case: Aradığımız sayının sonda olması
3) Best case: Aradığımız sayının dizinin en başında olması.
- Cevap = 1, Average Case

# [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
- [2,3,5,8,7,9,4,15,6]
- [2,3,5,8,7,9,4,15,6]
- [2,3,4,8,7,9,5,15,6]
- [2,3,4,5,7,9,8,15,6]
