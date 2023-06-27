# UAS_PAAII

Moh Jihad Khalid  
F55121063
Kelas B

### Analisis Algoritma Boblle sort dan selection sort :
> Worst Case:

    Bubble Sort: Worst case terjadi ketika array terurut secara terbalik atau descending. Pada kasus ini, setiap elemen harus dipindahkan ke posisi yang benar dalam setiap iterasi. Kompleksitas waktu Bubble Sort pada worst case adalah O(n^2).
    Insertion Sort: Worst case terjadi ketika array terurut secara terbalik atau descending. Pada kasus ini, setiap elemen harus disisipkan ke posisi yang benar dalam setiap iterasi, dan pergeseran elemen yang ada sebelumnya juga harus dilakukan. Kompleksitas waktu Insertion Sort pada worst case adalah O(n^2).

> Best Case:

    Bubble Sort: Best case terjadi ketika array sudah terurut secara ascending. Pada kasus ini, algoritma hanya perlu melalui satu iterasi tanpa ada pertukaran elemen. Namun, meskipun demikian, algoritma masih melakukan pengecekan untuk mengecek apakah ada pertukaran yang dilakukan atau tidak. Kompleksitas waktu Bubble Sort pada best case adalah O(n).
    Insertion Sort: Best case terjadi ketika array sudah terurut secara ascending. Pada kasus ini, algoritma hanya perlu melalui satu iterasi tanpa ada pergeseran elemen. Kompleksitas waktu Insertion Sort pada best case adalah O(n).

>Average Case:

    Bubble Sort: Rata-rata kasus terjadi ketika elemen-elemen array tidak terurut secara spesifik. Pada kasus ini, algoritma akan melalui beberapa iterasi dan melakukan pertukaran elemen yang tidak terurut. Kompleksitas waktu Bubble Sort pada average case adalah O(n^2).
    Insertion Sort: Rata-rata kasus terjadi ketika elemen-elemen array tidak terurut secara spesifik. Pada kasus ini, algoritma akan melalui beberapa iterasi, dan dalam setiap iterasi, elemen akan disisipkan ke posisi yang benar. Jumlah pergeseran elemen yang ada sebelumnya akan bergantung pada seberapa jauh posisi elemen yang akan disisipkan dari posisi aslinya. Kompleksitas waktu Insertion Sort pada average case adalah O(n^2).


### Analisis algoritma TSP dan Djikstra 

>Worst Case:

    TSP: Worst case terjadi ketika jumlah node dalam graf sangat besar. Dalam TSP, algoritma secara eksponensial mencoba semua kemungkinan jalur untuk mencari jalur terpendek. Kompleksitas waktu TSP dalam worst case adalah O(n!), di mana n adalah jumlah node dalam graf.
    Dijkstra: Worst case terjadi ketika ada banyak edge dalam graf yang harus diperiksa. Dalam kasus ini, algoritma akan memeriksa setiap edge untuk mencari jalur terpendek. Kompleksitas waktu Dijkstra dalam worst case adalah O((V + E) log V), di mana V adalah jumlah node dalam graf dan E adalah jumlah edge.

>Best Case:

    TSP: Best case dalam TSP adalah ketika jumlah node dalam graf sangat kecil, sehingga jumlah kemungkinan jalur yang harus diperiksa juga sangat kecil. Kompleksitas waktu TSP dalam best case tergantung pada implementasi dan kompleksitas solusi algoritma yang digunakan.
    Dijkstra: Best case dalam Dijkstra adalah ketika node tujuan langsung terhubung dengan node awal tanpa melalui node lain. Dalam kasus ini, algoritma hanya perlu memeriksa satu edge untuk mencari jalur terpendek. Kompleksitas waktu Dijkstra dalam best case adalah O(V + E), di mana V adalah jumlah node dalam graf dan E adalah jumlah edge.

>Average Case:

    TSP: Rata-rata kasus dalam TSP terjadi ketika jumlah node dalam graf sedang. Algoritma secara eksponensial mencoba semua kemungkinan jalur untuk mencari jalur terpendek, tetapi jumlah kemungkinan jalur yang harus diperiksa tidak sebesar pada worst case. Kompleksitas waktu TSP dalam average case adalah O(n!), di mana n adalah jumlah node dalam graf.
    Dijkstra: Rata-rata kasus dalam Dijkstra terjadi ketika graf memiliki ukuran sedang dan memiliki keseimbangan antara node dan edge. Algoritma akan memeriksa sejumlah edge untuk mencari jalur terpendek. Kompleksitas waktu Dijkstra dalam average case adalah O((V + E) log V), di mana V adalah jumlah node dalam graf dan E adalah jumlah edge.
