[22,27,16,2,18,6] -> Insertion Sort

#Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

1- [22,27,16,2,18,6] İlk aşamada dizideki en küçük sayıyı bulup başa yazıyoruz. > [2,27,16,22,18,6]
2- [2,27,16,22,18,6] İkinci en küçük sayıyı bulup ikinsi sıraya yazıyoruz. > [2,6,16,22,18,27]
3- [2,6,16,22,18,27] Üçüncü en küçük sayı 16 olduğu için değişiklik yapmıyoruz. [2,6,16,22,18,27]
4- [2,6,16,22,18,27] Dördüncü en küçük sayı olan 18 ile 22'yi yer değiştiriyoruz. [2,6,16,18,22,27]
5- [2,6,16,18,22,27] Dizimiz son halini alıyor.

#Big-O gösterimini yazınız.

Big-O = O(n^2)

#Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız.

18 sayısı dizinin ortalarında bulunduğundan dolayı Average Case kapsamına girer.

#[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

[2,3,5,8,7,9,4,15,6] İlk aşamada dizideki en küçük sayıyı bulup başa yazıyoruz.
[2,3,5,8,7,9,4,15,6] İkinci en küçük sayıyı bulup ikinsi sıraya yazıyoruz. > [2,3,4,8,7,9,5,15,6]
[2,3,4,8,7,9,5,15,6] Üçüncü en küçük sayıyı arıyoruz > [2,3,4,5,7,9,8,15,6]
[2,3,4,5,7,9,8,15,6] Dördüncü en küçük sayıyı bulup yer değiştiriyoruz. > [2,3,4,5,6,9,8,15,7]
