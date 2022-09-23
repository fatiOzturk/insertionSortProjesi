# Proje-2
### [16,21,11,8,12,22] -> Merge Sort

#### 1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
###### Başlangıçta dizimizi ikiye bölüyoruz. Bölünen dizileri tekrar bölüyoruz. Tek eleman kalana kadar İşleme devam ediyoruz.
                    |16|21|11|8|12|22|
            |16|21|11|      ve      |8|12|22|
       |16|21|   |11|          |8|12|      |22|
    |16|    |21|    |11|            |8|     |12|        |22|
 
 
   ######  Bölme işlemi bitikten sonra, tek elemanlı dizilerimizi ikili ikili birleştiriyoruz. Sıralı dizi elde edinceye kadar bu işleme devam ediyoruz.
    |16|    |21|    |11|            |8|     |12|       |22|
         |16|21|     |11|        |8 |  |12|22|  
          |11|16|21|                  |8 |12|22|  
                
                       |8|11|12|16|21|22|

#### 2. Big-O gösterimini yazınız.

Fonksiyon sürekli kendini çağırarak diziyi hep ikiye bölmektedir. Her bölünmüş dizinin Merge işlemi için de dizinin uzunluğu olan n işlem yapıldığından O(n*(logn)) --> O(6*(log6)) olacaktır.