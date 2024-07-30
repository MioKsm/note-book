# Sorting Algorithms

## Insertion Sort

**Verilen dizi:** [22, 27, 16, 2, 18, 6]

### Aşamalar:

1. **Başlangıç:** [22, 27, 16, 2, 18, 6]
2. **İlk iki eleman zaten sıralı:** [22, 27, 16, 2, 18, 6]
3. **16'yı doğru yere yerleştir:** [16, 22, 27, 2, 18, 6]
4. **2'yi doğru yere yerleştir:** [2, 16, 22, 27, 18, 6]
5. **18'i doğru yere yerleştir:** [2, 16, 18, 22, 27, 6]
6. **6'yı doğru yere yerleştir:** [2, 6, 16, 18, 22, 27]

### Big-O Gösterimi

- **En kötü durum zaman karmaşıklığı:** O(n^2)
- ** Aradığımız sayının ortada olmasında dolayı "Average case" durumundadır.

## Selection Sort

**Verilen dizi:** [7, 3, 5, 8, 2, 9, 4, 15, 6]

### Aşamalar:

1. **Başlangıç:** [7, 3, 5, 8, 2, 9, 4, 15, 6]
2. **Adım 1:** En küçük eleman 2, ilk elemanla yer değiştirir: [2, 3, 5, 8, 7, 9, 4, 15, 6]
3. **Adım 2:** En küçük eleman 3, ikinci eleman yerinde kalır: [2, 3, 5, 8, 7, 9, 4, 15, 6]
4. **Adım 3:** En küçük eleman 4, üçüncü elemanla yer değiştirir: [2, 3, 4, 8, 7, 9, 5, 15, 6]
5. **Adım 4:** En küçük eleman 5, dördüncü elemanla yer değiştirir: [2, 3, 4, 5, 7, 9, 8, 15, 6]

