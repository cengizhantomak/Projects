Proje 2

[16,21,11,8,12,22] -> Merge Sort

1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.


CEVAP1

1. adım diziyi ikiye böl:

    16, 21, 11 ve 8, 12, 22

2. adım çıkan bu dizileri de ikiye böl:

    16, 21; 11;  8, 12;  22;

3. adım elde edilen parçalar 2 veya daha küçük eleman sayısına ulaştığı için dur (aksi durumda bölme işlemi devam edecekti

4. adım her parçayı kendi içinde sırala

    16, 21; 11; 8,12; 22;

5. Her bölünmüş parçayı birleştir ve birleştirirken sıraya dikkat ederek birleştir (1. ve 2. parçalar ile 3. ve 4. parçalar aynı gruptan bölünmüştü)

    11, 16, 21 ve 8, 12, 22

6. adım, tek bir bütün parça olmadığı için birleştirmeye devam et

    8, 11, 12, 16, 21, 22

7. adım sonuçta bir bütün birleşmiş parça olduğu için dur. İşte bu sonuç dizisi ilk dizinin sıralanmış halidir.

    dizimiz : [8, 11, 12, 16, 21, 22] 



CEVAP2

    Best case    : O(n*logn)
    Average case : O(n*logn)
    Worst case   : O(n*logn)