# MERGE SORT PROJESİ

## [16,21,11,8,12,22] -> Merge Sorta göre aşamalarını yazınız.
- [16,21,11] ve [8,12,22] olarak iki parçaya ayırıyoruz. 
- [16,21,11] olan soldaki parçayı ise [16] ve [21,11] olarak parçaya ayırıyoruz.  
- [21,11] olan parçayı [11,21] şeklinde sıralıyoruz. 
- [16] ve [11,21] parçalarını [11,16,21] şeklinde sıralıyoruz. 
- [8,12,22] olan sağdaki parçanın sırası düzgün olduğundan parçalamıyoruz. 
- En son [11,16,21] ve [8,12,22] parçaları  sağdan 8'i en başa daha sonra soldaki 11'i sonra sağdan 12'yi, soldan 16'yı arkasından 21'i ve en son sağdan 22'yi alarak düzgünce sıralayıp bitiriyoruz. 
- En son sıralama bu şekil; 
- [8,11,12,16,21,22]

## Big-O gösterimini yazınız.

- O(nlogn) --> O(6log6)

