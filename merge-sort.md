### Merge Sort Adımları

1. **Bölme Aşaması:**
   - Dizi: `[16, 21, 11, 8, 12, 22]`
   - Böl: 
     - Sol Parça: `[16, 21, 11]`
     - Sağ Parça: `[8, 12, 22]`

2. **Sol Parçayı Sırala:**
   - Sol Parça: `[16, 21, 11]`
   - Böl:
     - Sol Parça: `[16]`
     - Sağ Parça: `[21, 11]`
       - `[21, 11]` -> `[11, 21]`
   - Birleştir:
     - `[16]` ve `[11, 21]` -> `[11, 16, 21]`

3. **Sağ Parçayı Sırala:**
   - Sağ Parça: `[8, 12, 22]`
   - Böl:
     - Sol Parça: `[8]`
     - Sağ Parça: `[12, 22]`
       - `[12, 22]` -> `[12, 22]`
   - Birleştir:
     - `[8]` ve `[12, 22]` -> `[8, 12, 22]`

4. **Son Birleştirme:**
   - Sol Parça: `[11, 16, 21]`
   - Sağ Parça: `[8, 12, 22]`
   - Birleştir:
     - `[8, 11, 12, 16, 21, 22]`

### Big-O Gösterimi

- **Zaman Karmaşıklığı:** \(O(n \log n)\)
