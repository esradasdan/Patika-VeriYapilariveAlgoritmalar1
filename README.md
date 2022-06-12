# Patika-VeriYapilariveAlgoritmalar

 # 1- Insertion Sort Project
 
 [22,27,16,2,18,6] -> Insertion Sort

-Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
        [22,27,16,2,18,6]   
        [22,16,27,2,18,6]
        [16,22,27,2,18,6]   
        [16,22,2,27,18,6]
        [16,2,22,27,18,6]
        [2,16,22,27,18,6] 
        [2,16,22,18,27,6]
        [2,16,18,22,27,6] 
        [2,16,18,22,6,27]
        [2,16,18,6,22,27]
        [2,16,6,18,22,27]
        [2,6,16,18,22,27] 

      
-Big-O gösterimini yazınız.
      O(n^2)
      
-Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en       başında olması.
     
     WORST CASE : n(n-1) /2 ----> Big O(n^2)
     
     BEST CASE :  n ----> Big O(n)
     
     AVERAGE CASE : [ (n^2) + (n) ] / 2 ----> Big O(n^2)
     
-Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

    18 sayısı dizinin ortasındadır, average case kapsamına girer.
    
-[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
      
      [3,7,5,8,2,9,4,15,6]
      [3,5,7,8,2,9,4,15,6]
      [3,5,7,8,2,9,4,15,6]
      [3,5,7,2,8,9,4,15,6]
