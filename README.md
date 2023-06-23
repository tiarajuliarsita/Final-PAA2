# Final-PAA2
Final Perancangan dan Analisi Algoritma 2

### Analisis Bubble Sort

- **Sebelum pengurutan**: [12, 99, 62, 15, 20, 95, 39, 48, 3, 24, 8, 43, 74, 19, 97, 33, 49, 68, 55, 33, 90, 90, 7, 26, 85, 46, 39, 40, 9, 36, 60, 64, 89, 31, 25, 71, 21, 23, 63, 84, 32, 5, 3, 44, 21, 10, 21, 17, 50, 2, 36, 53, 79, 54, 19, 88, 1, 32, 31, 15, 6, 3, 1, 40, 22, 43, 18, 1, 77, 9, 59, 40, 7, 41, 81]

- **Setelah pengurutan**: [1, 1, 1, 2, 3, 3, 3, 5, 6, 7, 7, 8, 9, 9, 10, 12, 15, 15, 17, 18, 19, 19, 20, 21, 21, 21, 22, 23, 24, 25, 26, 31, 31, 32, 32, 33, 33, 36, 36, 39, 39, 40, 40, 40, 41, 43, 43, 44, 46, 48, 49, 50, 53, 54, 55, 59, 60, 62, 63, 64, 68, 71, 74, 77, 79, 81, 84, 85, 88, 89, 90, 90, 95, 97, 99]

- **Waktu eksekusi**: 0.0041697025299072266 detik

Berdasarkan data yang diberikan untuk buble sort, kasus diatas adalah average case, kita dapat menganalisis performa Bubble Sort sebagai berikut:

1. **Best Case**: Skenario kasus terbaik (best case) untuk Bubble Sort terjadi ketika list input sudah terurut. Pada kasus ini, Bubble Sort akan memiliki kompleksitas waktu O(n) karena tidak perlu dilakukan pertukaran. Namun, list input yang diberikan tidak terurut secara awal, sehingga tidak mewakili kasus terbaik.

2. **Worst Case**: Skenario kasus terburuk (worst case) untuk Bubble Sort terjadi ketika list input terurut secara terbalik. Pada kasus ini, Bubble Sort akan melakukan jumlah perbandingan dan pertukaran maksimum, menghasilkan kompleksitas waktu O(n^2). Karena list input yang diberikan tidak terurut secara terbalik, maka tidak mewakili kasus terburuk.

3. **Average Case**: Skenario kasus rata-rata (Average Case ) untuk Bubble Sort terjadi ketika list input diurutkan secara acak. Pada kasus ini
, Bubble Sort akan membutuhkan beberapa iterasi dan perbandingan untuk mengurutkan list. Kompleksitas waktu Bubble Sort pada Average O(n^2). **List input yang diberikan mewakili skenario kasus rata-rata (Average Case)** karena tidak terurut secara awal dan tidak terurut secara terbalik.

Dengan demikian, kita dapat mengatakan bahwa hasil pengurutan dengan Bubble Sort ini mewakili **kasus rata-rata (average case)**. Meskipun kompleksitas waktu Bubble Sort dalam kasus rata-rata juga O(n^2), waktu eksekusi yang Anda berikan menunjukkan bahwa jumlah iterasi yang dilakukan tidak terlalu besar dan kinerjanya relatif baik.
