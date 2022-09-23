# Insertion Sort Projesi 

### [22,27,16,2,18,6] -> Insertion Sort
1.  Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
    - **Birinci iterasyonda;**
    En küçük elemanı bul ve listenin başındaki değer ile yer değiştir(2 ve 22 yer değiştirdi). Sonuç; `[2, 27, 16, 22, 18, 6] `

    - **İkinci iterasyonda;**
    Listenin ikinci elemanından itıbaren en küçük elemanı bul ve listenin 2. elemanı ile yer değiştir(6 ve 27 yer değiştirdi).Sonuç; `
    [2, 6, 16, 22, 18, 27] 
    `
    - Aynı mantık ile devam edildiğinde **üçüncü iterasyonda;** `[2, 6, 16, 22, 18, 27]`
    - **Dördüncü iterasyonda;** `[2, 6, 16, 18, 22, 27]`
    - **Beşinci iterasyonda;** listenin son hali **`[2, 6, 16, 18, 22, 27]`**
2. Big-O gösterimini yazınız.
    - ***O(n^2)*** (average case - worst case)
    - ***O(n)*** (best case)
3. Time Complexity:
    - **Average case:** Aradığımız sayının ortada olması. => **[6,16,18,22]**
    - **Worst case:** Aradığımız sayının sonda olması.=> **[2]**
    - **Best case:** Aradığımız sayının dizinin en başında olması. => **[27]**

4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
    - Dizi sıralandıktan sonra 18 sayısı dizinin orta kısmında olduğundan, aranması **average case** kapsamına girer.

---

### [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
1. Adım:
    >[2, 3, 5, 8, 7, 9, 4, 15, 6] => 2 ve 7 yer değiştirdiler.`
2. Adım:
    >[2, 3, 5, 8, 7, 9, 4, 15, 6] => 2. en küçük sayı olan '3' zaten ikinci sıradaydı. O yüzden herhangi bir yer değiştirme olmadı.
3. Adım:
    >[2, 3, 4, 8, 7, 9, 5, 15, 6] => 3. en küçük sayı olan 4 ile 3. sıradaki 5 yer değiştirdiler.
4. Adım:
    >[2, 3, 4, 5, 7, 9, 8, 15, 6] => 4. en küçük sayı olan 5 ile 4. sıradaki 8 yer değiştirdiler.
