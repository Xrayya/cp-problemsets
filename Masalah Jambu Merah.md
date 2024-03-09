# Masalah Jambu Merah
## Deskripsi
Mbah Kakung memiliki $n$ jambu merah. Jambu merah ke- $i$ memiliki jumlah vitamin C sebesar $a_i$ g. Jadi, dengan memakan jambu merah ke- $i$, Mbah Kakung mengonsumsi jumlah vitamin C sebesar $a_i$ g.<br>

Mbah Kakung akan bertanya kepadamu sebanyak $q$ pertanyaan mengenai jambunya. Untuk pertanyaan ke- $j$, kamu harus menjawab berapa jumlah **minimum** jambu merah yang harus dimakan Mbah Kakung agar mencapai jumlah vitamin C **lebih besar atau sama dengan** $x_j$, atau cetak $-1$ jika tidak mungkin mencapai jumlah tersebut. Dengan kata lain, kamu harus mencetak nilai $k$ minimum yang mungkin sehingga setelah memakan $k$ jambu merah, Mbah Kakung mengonsumsi jumlah vitamin C setidaknya $x_j$ g, atau katakan bahwa tidak ada $k$ yang mungkin.<br>

Perhatikan bahwa Mbah Kakung tidak dapat memakan jambu merah yang sama dua kali, dan pertanyaan tidak berhubungan satu sama lain (Mbah Kakung dapat mengonsumsi jambu merah yang sama dalam pertanyaan-pertanyaan yang berbeda).<br>

## Input
Baris pertama input berisi satu bilangan bulat $t$ ($1≤t≤1000$) — jumlah kasus uji. Deskripsi setiap kasus uji adalah sebagai berikut.<br>

Baris pertama berisi 2 bilangan bulat $n$ dan $q$ ($1≤n,q≤1.5⋅10^5$) — jumlah jambu merah yang dimiliki Mbah Kakung dan jumlah pertanyaan yang harus Anda jawab.

Baris kedua berisi $n$ bilangan bulat $a1,a2,…,a_n$ ($1≤a_i≤10^4$) — jumlah vitamin C dalam masing-masing jambu merah secara berturut-turut.

Kemudian ada $q$ baris berikutnya.

Setiap baris dari $q$ baris berikutnya berisi satu bilangan bulat $x_j$ ($1≤x_j≤2⋅10^9$) – jumlah vitamin C yang ingin dicapai oleh Mbah Kakung untuk pertanyaan yang diberikan.

Dijamin bahwa jumlah $n$ dan jumlah $q$ dari semua kasus uji tidak melebihi $1.5⋅10^5$.

## Output
Untuk setiap kasus uji, keluarkan $q$ baris. Untuk baris ke- $j$, keluarkan jumlah jambu merah yang harus dimakan Mbah Kakung agar mencapai jumlah vitamin C lebih besar atau sama dengan $x_j$, atau cetak $-1$ jika tidak mungkin mencapai jumlah tersebut.

## Test Case
### Input
```
3
8 7
4 3 3 1 1 4 5 9
1
10
50
14
15
22
30
4 1
1 2 3 4
3
1 2
5
4
6
```

### Output
```
1
2
-1
2
3
4
8
1
1
-1
```
