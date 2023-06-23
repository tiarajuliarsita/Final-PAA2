# Final-PAA2
Final Perancangan dan Analisi Algoritma 2
<H1>Buble sort & insertion sort</H1>

<H2>Analisis Algoritma Insertion Sort</H2>

- **Sebelum pengurutan**: [12, 99, 62, 15, 20, 95, 39, 48, 3, 24, 8, 43, 74, 19, 97, 33, 49, 68, 55, 33, 90, 90, 7, 26, 85, 46, 39, 40, 9, 36, 60, 64, 89, 31, 25, 71, 21, 23, 63, 84, 32, 5, 3, 44, 21, 10, 21, 17, 50, 2, 36, 53, 79, 54, 19, 88, 1, 32, 31, 15, 6, 3, 1, 40, 22, 43, 18, 1, 77, 9, 59, 40, 7, 41, 81]

- **Setelah pengurutan**: [1, 1, 1, 2, 3, 3, 3, 5, 6, 7, 7, 8, 9, 9, 10, 12, 15, 15, 17, 18, 19, 19, 20, 21, 21, 21, 22, 23, 24, 25, 26, 31, 31, 32, 32, 33, 33, 36, 36, 39, 39, 40, 40, 40, 41, 43, 43, 44, 46, 48, 49, 50, 53, 54, 55, 59, 60, 62, 63, 64, 68, 71, 74, 77, 79, 81, 84, 85, 88, 89, 90, 90, 95, 97, 99]

- **Waktu eksekusi**: 0.004955768585205078 seconds

Berdasarkan data yang diberikan untuk buble sort, kasus diatas adalah average case, kita dapat menganalisis performa Bubble Sort sebagai berikut:

1. **Best Case**: Skenario kasus terbaik (best case) untuk Bubble Sort terjadi ketika list input sudah terurut. Pada kasus ini, Bubble Sort akan memiliki kompleksitas waktu O(n) karena tidak perlu dilakukan pertukaran. Namun, Data yang yang diberikan pada kasus diatas tidak terurut secara awal, sehingga tidak mewakili kasus terbaik.

2. **Worst Case**: Skenario kasus terburuk (worst case) untuk Bubble Sort terjadi ketika list input terurut secara terbalik. Pada kasus ini, Bubble Sort akan melakukan jumlah perbandingan dan pertukaran maksimum, menghasilkan kompleksitas waktu O(n^2). Karena pada kasus diatas data yang diberikan tidak terurut secara terbalik, maka program diatas tidak mewakili kasus terburuk.

3. **Average Case**: Skenario kasus rata-rata (Average Case ) untuk Bubble Sort terjadi ketika list input diurutkan secara acak. Pada kasus ini
, Bubble Sort akan membutuhkan beberapa iterasi dan perbandingan untuk mengurutkan list. Kompleksitas waktu Bubble Sort pada Average O(n^2). **pada kasus diatasList input yang diberikan mewakili skenario kasus rata-rata (Average Case)** karena tidak terurut secara awal dan tidak terurut secara terbalik.

Dengan demikian, kita dapat mengatakan bahwa hasil pengurutan dengan Bubble Sort ini mewakili **kasus rata-rata (average case)**. Meskipun kompleksitas waktu Bubble Sort dalam kasus rata-rata juga O(n^2), waktu eksekusi yang Anda berikan menunjukkan bahwa jumlah iterasi yang dilakukan tidak terlalu besar dan kinerjanya relatif baik.

 <H2>Analisis Algoritma Insertion Sort</H2>

Dalam kasus ini, digunakan algoritma pengurutan Insertion Sort untuk mengurutkan data awal yang tidak terurut. Berikut adalah hasil pengurutan menggunakan algoritma Insertion Sort:

- **Data sebelum diurutkan:** [12, 99, 62, 15, 20, 95, 39, 48, 3, 24, 8, 43, 74, 19, 97, 33, 49, 68, 55, 33, 90, 90, 7, 26, 85, 46, 39, 40, 9, 36, 60, 64, 89, 31, 25, 71, 21, 23, 63, 84, 32, 5, 3, 44, 21, 10, 21, 17, 50, 2, 36, 53, 79, 54, 19, 88, 1, 32, 31, 15, 6, 3, 1, 40, 22, 43, 18, 1, 77, 9, 59, 40, 7, 41, 81]

- **Data setelah diurutkan:** [1, 1, 1, 2, 3, 3, 3, 5, 6, 7, 7, 8, 9, 9, 10, 12, 15, 15, 17, 18, 19, 19, 20, 21, 21, 21, 22, 23, 24, 25, 26, 31, 31, 32, 32, 33, 33, 36, 36, 39, 39, 40, 40, 40, 41, 43, 43, 44, 46, 48, 49, 50, 53, 54, 55, 59, 60, 62, 63, 64, 68, 71, 74, 77, 79, 81, 84, 85, 88, 89, 90, 90, 95, 97, 99]

- **Waktu Eksekusi:** 0.004044771194458008 seconds
1. **Average Case**
Dalam analisis kasus ini, dapat disimpulkan bahwa pengurutan dengan menggunakan Insertion Sort mewakili kasus rata-rata (average case). Meskipun kompleksitas waktu Insertion Sort dalam kasus rata-rata juga O(n^2), waktu eksekusi yang diperoleh menunjukkan bahwa jumlah iterasi yang dilakukan tidak terlalu besar dan kinerjanya relatif baik.Perlu dicatat bahwa hasil ini didapatkan karena data awalnya tidak terurut secara terbalik secara ekstrim. 
2. **Best Case**
Jika data awalnya sudah terurut, maka Insertion Sort akan memiliki kinerja terbaik dengan kompleksitas waktu O(n). namun datanya awal nya tidak  terurut sehingga kasus tersebut bukan merupakan best case.
3. **worst case**
   jika data awalnya terurut secara terbalik secara ekstrim, maka Insertion Sort akan mencapai kasus terburuk (worst case) dengan kompleksitas waktu O(n^2). namun data yang diberikan tidak terurut secara terbalik secara ekstrim,seingga bukan merupakan worst case.


<H1>Traveling Salesman Problem & Djikstra Algorithm</H1>
<H2>Analisis Algoritma TSP</H2>

Dalam program ini, kita menerapkan algoritma TSP (Traveling Salesman Problem) untuk mencari jalur terpendek yang melintasi semua vertex dalam sebuah graph. Untuk melakukan analisis kompleksitas waktu pada algoritma TSP, kita dapat mempertimbangkan tiga kasus: worst case, best case, dan average case.

**1. Worst Case:**
Worst case pada algoritma TSP terjadi ketika semua permutasi jalur mungkin harus diuji untuk mencari jalur terpendek. Dalam kasus ini, kompleksitas waktu akan bergantung pada jumlah vertex pada graph. Jumlah permutasi yang mungkin untuk N vertex adalah (N-1)!. Oleh karena itu, kompleksitas waktu pada worst case adalah O((N-1)!).

**2. Best Case:**
Best case pada algoritma TSP terjadi ketika ada jarak langsung dari satu vertex ke semua vertex lainnya. Dalam hal ini, hanya satu jalur yang perlu diuji dan tidak perlu menghitung permutasi jalur. Sehingga kompleksitas waktu pada best case adalah O(1).

**3. Average Case:**
Pada kasus rata-rata, kompleksitas waktu algoritma TSP dapat bervariasi tergantung pada karakteristik graph dan pendekatan yang digunakan. Dalam program ini, kita menggunakan pendekatan brute force dengan menguji semua permutasi jalur yang mungkin. Jumlah permutasi yang diuji untuk N vertex adalah (N-1)!. Kompleksitas waktu rata-rata pada pendekatan ini juga dapat dianggap sebagai O((N-1)!).

Kasus tersebut dapat digolongkan sebagai **average case**, karena kompleksitas waktu algoritma TSP pada kasus tersebut akan bervariasi tergantung pada jumlah vertex yang harus diuji. Dalam hal ini, kompleksitas waktu akan dipengaruhi oleh jumlah permutasi yang mungkin, yang pada kasus ini adalah (7-1)! = 6!, yaitu 720 permutasi.
Pada kasus yang diberikan, output program menunjukkan waktu komputasi sekitar 1.478879 detik untuk menyelesaikan algoritma TSP pada graph dengan 7 vertex. Namun, penting untuk dicatat bahwa waktu komputasi dapat bervariasi tergantung pada sistem komputer dan lingkungan eksekusi program.

<H2>Analisis Algoritma Djikstra</H2>

**1. Worst case:**
Worst case pada algoritma Dijkstra terjadi ketika semua node terhubung satu sama lain dengan jarak yang sama. Dalam kasus ini, algoritma Dijkstra akan memeriksa semua kemungkinan jalur, sehingga kompleksitas waktu akan mencapai O(V^2), di mana V adalah jumlah node dalam graf. Dalam contoh kasus Anda, kompleksitas waktu terburuk dapat terjadi ketika setiap node terhubung langsung dengan node lainnya. Dalam hal ini, terdapat 7 node, sehingga kompleksitas waktu adalah O(7^2) = O(49).

**2. Best case:**
Best case pada algoritma Dijkstra terjadi ketika node tujuan dapat dicapai langsung dari node awal tanpa harus melalui node lainnya. Dalam kasus ini, algoritma Dijkstra akan memeriksa setiap node sekali, sehingga kompleksitas waktu adalah O(V), di mana V adalah jumlah node dalam graf. Dalam contoh kasus Anda, jika misalnya Anda mencari shortest path dari node A ke node G, yang dapat dicapai langsung, kompleksitas waktu terbaiknya adalah O(7).

**3. Average case:**
Rata-rata kompleksitas waktu pada algoritma Dijkstra dapat bervariasi tergantung pada struktur graf dan jarak antara node-node. Dalam kasus umum, kompleksitas waktu algoritma Dijkstra adalah O(V^2), di mana V adalah jumlah node dalam graf. Namun, dalam beberapa implementasi yang dioptimalkan, seperti menggunakan antrian prioritas, kompleksitas waktu dapat ditingkatkan menjadi O((V + E) log V), di mana E adalah jumlah tepi dalam graf. Dalam contoh kasus Anda, dengan 7 node, kompleksitas waktu rata-rata berkisar antara O(7^2) hingga O((7 + 14) log 7).

Jadi, berdasarkan analisis ini, algoritma Dijkstra pada contoh kasus Anda termasuk dalam kasus worst case (terburuk) dan average case (rata-rata) sesuai dengan kompleksitas waktu yang telah dijelaskan sebelumnya.
