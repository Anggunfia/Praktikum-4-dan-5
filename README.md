# ARTIFICIAL INTELLIGENCE
## Praktikum 4
**TUGAS**
1. Tentukan bagaimana algoritma BFS di atas dapat menentukan node ke 8, 6, dan 7. 2.
2. Ubahlah method static void main sehingga bentuk tree seperti Gambar 4.5 dapat dibentuk. Kemudian tentukan bagaimana algoritma BFS dapat menemukan node 5.
3. Ubahlah method static void main sehingga bentuk tree seperti Gambar 4.6 dapat dibentuk. Kemudian tentukan bagaimana algoritma BFS dapat menemukan node 9.
4. Ubahlah kode program di atas sehingga bentuk tree seperti Gambar 4.7 dapat dibentuk. Kemudian tentukan bagaimana algoritma BFS dapat menemukan node C.

**PENYELESAIAN**
1. Algoritma BFS (Breadth-First Search) adalah salah satu algoritma pencarian dalam ilmu komputer yang digunakan untuk menjelajahi atau mencari informasi dalam graf atau struktur data berdasarkan tingkat jarak atau kedalaman dari node awal. Algoritma ini bekerja dengan cara menjelajahi node-node yang terhubung secara langsung dengan node awal sebelum mengeksplorasi node-node yang lebih dalam atau lebih jauh. Berikut merupakan langkah Pada Algoritma BFS.
>>  a)	  menginisiasi node awal, yaitu node 3, kemudian dimasukkan ke dalam antrian.

>>  b)	Selanjutnya, node 3 akan mengeksplorasi node-node yang terhubung langsung dengan itu, yaitu node 2 dan node 4, karena keduanya memiliki jarak 1 dari node 3. Node 4 akan melanjutkan dengan mengeksplorasi node 1, node 6, dan node 5 yang terhubung dengannya. 

>> c)	Selanjutnya, node 5 akan mengeksplorasi node 8 dan node 7. 

>> d)	Proses ini akan terus berlanjut sampai semua node yang terhubung dengan node awal telah diperiksa.

Oleh karena itu, pada akhir proses BFS, node-node 8, 6, dan 7 akan ditemukan dan diproses sesuai dengan aturan algoritma BFS.

2. Kemudian untuk membuat tree seperti pada gambar 4.5 method static void main diubah seperti berikut:
   ![alt text](https://github.com/Anggunfia/Praktikum-4-dan-5/blob/main/Gambar/Gambar%201.png?raw=true)
   
Selanjutnya Run program maka akan didapatkan hasil sebagai berikut:
 
Hasil tersebut mengkonfirmasi kesesuaian hasil tree yang dihasilkan oleh program dengan gambar 4.5. 
> a)	Untuk mencari node 5, algoritma BFS pertama-tama dimulai dengan langkah memasukkan node 1 ke dalam antrian.
>
> b)	Selanjutnya, node 1 akan mengeksplorasi node 2 dan node 3, yang secara langsung terhubung dengan node 1 atau memiliki kedalaman tingkat 1.
>
> c)	Kemudian, node 3 akan melanjutkan dengan mengeksplorasi node yang memiliki kedalaman 2, dimulai dengan mengecek node 4, node 5, node 6, dan node 7.
>
> d)	Setelah node 5 ditemukan, proses akan terus berlanjut hingga semua node yang terhubung dengan node awal telah diperiksa. 

Oleh karena itu, pada akhir proses BFS, node 5 akan ditemukan dan diolah sesuai dengan ketentuan algoritma BFS.

3.	Pembuatan tree seperti pada gambar 4.6 menggunakan method static void main diubah seperti berikut:
 
 
Kemudian Run program dan didapatkan hasil sebagai berikut:
 
Hasil tersebut sudah menunjukkan bahwa hasil tree yg diperoleh dari program sudah sesuai dengan gambar 4.6. 
> a)	Untuk menemukan node 9 algoritma BFS pertama-tama dimulai dengan memasukkan node 1 ke dalam antrian.
>
> b)	Kemudian dilanjutkan node 1 akan memeriksa node 2, node 3, dan node 4 yang terhubung langsung dengan node 1 atau node yang memiliki tingkat kedalaman 1.
>
> c)	Dilanjutkan node 4 akan memeriksa node yang memiliki tingkat kedalaman 2 dimulai dari memeriksa node 5, node 6, node 7, dan node 8.
>
> d)	Kemudian node 8 akan memeriksa node 9, setelah menemukan node 9 proses akan terus berlanjut untuk memeriksa node 10, node 11, dan node 12 sampai semua node yang terhubung dengan node awal telah diperiksa. 

Dengan demikian, pada akhir proses BFS, node 9 akan ditemukan dan diproses sesuai dengan aturan algoritma BFS.

4.	Pembuatan tree seperti pada gambar 4.7, pada pembuatan tree kali ini akan dilakukan beberapa perubahan pada program.

> 1)	Pada kelas Node, untuk dapat menerima huruf maka Ganti tipe data variabel ’data’ dari yang awalnya ’int’ menjadi ’String’.
>    
> 2)	Kemudian pada Metode main, Masukkan nilai node dengan tipe data string sebagai berikut.
>    
> 3)	Selanjutnya pada Metode addEdge dan bfs, Masukkan logika pemrosesan data untuk tipe data String sebagai berikut.
 
Kemudian Run program maka akan didapatkan hasil sebagai berikut:
 
Hasil tersebut sudah menunjukkan bahwa hasil tree yg diperoleh dari program sudah sesuai dengan gambar 4.7. 
> a)	Untuk menemukan node 3 (C) algoritma BFS pertama-tama dimulai dengan memasukkan node 6 (F) ke dalam antrian.
>
> b)	Kemudian dilanjutkan node 6 akan memeriksa node 2 (B), dan node 7 (G) yang terhubung langsung dengan node 6 atau node yang memiliki tingkat kedalaman 1.
>
> c)	selanjutnya node 7 akan memeriksa node yang memiliki tingkat kedalaman 2 dimulai dari memeriksa node 1 (A), node 4 (D), dan node 9 (I).
>
> d)	 Kemudian node 9 akan memeriksa node 3, setelah menemukan node 3 (C) proses akan terus berlanjut untuk memeriksa node 5 (E), dan node 8 (H) sampai semua node yang terhubung dengan node awal telah diperiksa.

Dengan demikian, pada akhir proses BFS, node 3 (C) akan ditemukan dan diproses sesuai dengan aturan algoritma BFS.


LAMPIRAN
1.	Lampiran 1: 
 
Gambar 4.5 Tree 1

2.	Lampiran 2: 
 
Gambar 4.6 Tree 2

3.	Lampiran 3: 
 
Gambar 4.7 Tree 3


5. a
## Praktikum 5
**TUGAS**
1. Pelajari Class EighPuzzelSearch, EightPuzzleSpace, dan Node.
2. Ubahlah initila dan goal state dari program diatas sehingga bentuk initial dan goal statenya
gambar 8. Kemudian tentukan langkah-langkah mana saja sehingga Puzzle nya mencapai
goal state. Analisa dan bedakan dengan solusi pada point 1.
3. Ubahlah initial dan goal state dari program di atas sehingga bentuk initial dan goal statenya
Gambar 5.9. Kemudian tentukan langkah-langkah mana saja sehingga puzzlenya mencapai
goal state. Analisa dan bedakan dengan solusi pada point 1 dan 2.
4. Ubahlah initial dan goal state dari program di atas sehingga bentuk initial dan goal statenya
Gambar 5.10. Kemudian tentukan langkah-langkah mana saja sehingga puzzlenya
mencapai goal state. Analisa dan bedakan dengan solusi pada point 1, 2, dan 3.
5. Ubahlah initial dan goal state dari program dan class-class di atas sehingga bentuk initial
dan goal statenya Gambar 5.11. Kemudian tentukan langkah-langkah mana saja sehingga
puzzlenya mencapai goal state.

**PENYELESAIAN**
1. Berikut mengenai Class EighPuzzelSearch, EightPuzzleSpace, dan Node

  >   **a) Eight Puzzele Search Class**
   >> EightPuzzleSearch Class bertugas melakukan pencarian solusi untuk masalah
   >> puzzle 8 angka. Kelas ini bergantung pada kelas EightPuzzleSpace untuk
   >> mendapatkan informasi tentang ruang pencarian dan menggunakan kelas Node
   >> untuk  mewakili simpul dalam pencarian. Selain itu, Kelas EightPuzzleSearch
   >> mengelola dua daftar, yaitu daftar terbuka (open) dan daftar tertutup
   >> (closed). Kelas ini menyediakan berbagai metode, termasuk untuk mendapatkan
   >> simpul terbaik dari daftar terbuka (getBestNode), mendapatkan biaya
   >> sebelumnya dari simpul (getPreviousCost), mencetak jalur solusi
   >> (printPath), dan menjalankan algoritma pencarian (run).

>  **b)	EightPuzzleSpace Class**
>>   EightPuzzleSpace Class berperan sebagai wadah yang menangani operasi yang
>  > berhubungan dengan ruang pencarian untuk masalah puzzle 8 angka. Kelas ini
>  > menyediakan metode untuk mendapatkan simpul awal (getRoot), mengambil tujuan
>  > (getGoal), dan menghasilkan daftar suksesor dari suatu simpul tertentu
>  > (getSuccessors). Tugas utama kelas ini adalah mengelola konfigurasi awal dan
>  > tujuan dari puzzle 8 angka serta menentukan langkah-langkah yang dapat
>  > diambil dari suatu keadaan puzzle.

>  **c)	Node Class**  
  >> Node Class  adalah representasi dari simpul atau node dalam struktur data
>  > graf. Setiap simpul memiliki atribut state, yang merupakan array integer
>  > dengan panjang 9, yang menggambarkan keadaan dari puzzle 8 angka. Atribut
>  > lainnya mencakup biaya (cost) yang terkait dengan simpul, parent yang
>  > mengacu pada simpul pendahulu, dan daftar suksesor (successors) yang
>  > merupakan daftar simpul anak dari simpul saat ini. Kelas ini juga memiliki
>  > metode untuk mengubah simpul menjadi bentuk string, memeriksa kesetaraan,
>  > dan mengambil jalur dari simpul ke akar.
    Run Kode program untuk mendapatkan hasil seperti dibawah ini :
2. Mengubah initial dan goal state pada kode program seperti pada gambar 5.8 :

  >   kemudian untuk mendapatkan hasil, makan Run kode program dan akan dihasilkan sebagai berikut :

> Setelah di Run, maka akan diketahui langkah-langkah dalam pencapaian goal state sebegai berikut 
> >  a.	Pada langkah awal menginisialisasi root state terlebih dahulu :

> >  b.	Kemudian, Algoritma akan mencari langkah-langkah dan menggeser angka yang
> >  bersebelahan dengan posisi kosong (0) ke arah yang seharusnya unutk mrndapatkan Goal Statenya.
> > 
> > c.	Pada setiap iterasi menampilkan langkah demi langkah yang di hasilkan
> > 
> >  d.	Kemudian langkah akan berhenti ketika sudah mendapatkan Goal State yang diinginkan

   >  Pada Setiap langkah yang diambil akan menunjukkan perpindahan angka ke angka untuk mencapai Goal State yang diinginkan. Pada hal ini Al goritma akan mencoba berbagai cara atau kombinasi dari perpindahan ubin-ubin angka untuk menemukan jalan yang paling tepat dan efesien untuk mrnuju pada goal State. Pada hasil diatas langkah yang diperlukan 13 langkah untuk menuju dari Root State ke Goal State.
> 
   >  Pada percobaan point 2 untuk mencapai goal state yang diinginkan diperlukan sebanyak 13 langkah sedangkan pada percobaan point 1 hanya diperlukan sebanyak 6 langkah untuk mencapai goal state yang diinginkan. Hal ini dikarenakan puzzle pada point 2 memiliki jarak yang lebih panjang dari root state ke goal state daripada point 1 atau memiliki posisi yang lebih teracak dari point 1. Oleh karena itu pada point 2 diperlukan langkah yang lebih banyak dalam mencapai goal state yang diinginkan.

3. Mengubah initial dan goal state pada program seperti pada gambar 5.9 : 
 
> Kemudian untuk mendapatkan hasil, maka Run Program dan akan dihasilkan sebagai berikut :

 
> Setelah program di run, maka akan diketahui langkah-langkah dalam mencapai Goal State sebagai berikut: 
>> 	a) Pada langkah awal menginisialisasi root state terlebih dahulu : 
 
 >> b) Kemudian, Algoritma akan mencari langkah-langkah dan menggeser angka yang bersebelahan dengan posisi kosong (0) ke arah yang seharusnya utnutk mrndapatkan Goal Statenya.
> > 
> > c) Pada setiap iterasi menampilkan langkah demi langkah yang di hasilkan
> >
> > Kemudian langkah akan berhenti ketika sudah mendapatkan Goal State yang diinginkan:

 
> Pada Setiap langkah yang diambil akan menunjukkan perpindahan angka ke angka untuk mencapai Goal State yang diinginkan. Pada hal ini Al goritma akan mencoba berbagai cara atau kombinasi dari perpindahan ubin-ubin angka untuk menemukan jalan yang paling tepat dan efesien untuk mrnuju pada goal State. Pada hasil diatas langkah yang diperlukan 20 langkah untuk menuju dari Root State ke Goal State. 

> Pada percobaan point 3 untuk mencapai goal state yang diinginkan diperlukan sebanyak 20 langkah sedangkan pada percobaan point 1 hanya diperlukan sebanyak 6 langkah dan percobaan point 2 diperlukan 13 langkah untuk mencapai goal state yang diinginkan. Hal ini dikarenakan puzzle pada point 3 memiliki jarak yang lebih panjang dari root state ke goal state daripada point 1 dan point 2 atau memiliki posisi yang lebih teracak dari point 1 dan point 2. Oleh karena itu pada point 3 diperlukan langkah yang lebih banyak dalam mencapai goal state yang diinginkan.

4.	Mengubah initial dan Goal Staet pada program seperti pada gambar 5.10 :
 
> Kemudian untuk mendapatkan hasil, maka Run Program dan akan dihasilkan sebagai berikut :
 
> Setelah program di run, maka akan diketahui langkah-langkah dalam mencapai Goal State sebagai berikut: 
>> a)	Pada langkah awal menginisialisasi root state terlebih dahulu : 
 
>> b)	Kemudian, Algoritma akan mencari langkah-langkah dan menggeser angka yang bersebelahan dengan posisi kosong (0) ke arah yang seharusnya utnutk mrndapatkan Goal Statenya.
>> 
>> c)	Pada setiap iterasi menampilkan langkah demi langkah yang di hasilkan
>> 
>> d)	Kemudian langkah akan berhenti ketika sudah mendapatkan Goal State yang diinginkan:
 
> Pada Setiap langkah yang diambil akan menunjukkan perpindahan angka ke angka untuk mencapai Goal State yang diinginkan. Pada hal ini Al goritma akan mencoba berbagai cara atau kombinasi dari perpindahan ubin-ubin angka untuk menemukan jalan yang paling tepat dan efesien untuk mrnuju pada goal State. Pada hasil diatas langkah yang diperlukan 16 langkah untuk menuju dari Root State ke Goal State. 

> Pada percobaan ini dapat kita perhatikan bahwa pertama root dari keempat percobaan sangat berbeda. Root dalam percobaan 3 memiliki urutan angka yang lebih kompleks dibandingkan dengan Root dalam percobaan lainnya. Kedua, solusi dari keempat percobaan juga berbeda. Dalam percobaan 1, solusi adalah 1 6 5 8 0 4 2 7 3, dalam percobaan 2, solusi adalah 1 2 3 4 5 6 7 8 0, sedangkan pada percobaan 3, solusi adalah 7 6 5 8 0 4 1 2 3.

> Kesimpulannya, meskipun keempat percobaan dapat mencapai solusi, perbedaan pada Root dan solusi menunjukkan bahwa program dimulai dari keadaan awal yang berbeda dan mencapai tujuan yang berbeda.

5.	Untuk menyelesaikan puzzle seperti pada gambar 5.11 perlu dilakukan perubahan tipe data pada program yang awalnya ’int’ menjadi tipe data ’String’ seperti pada lampiran.
> Ubah initial dan goal pada program seperti dengan gambar 5.10 sebagai berikut: Run program dan didapatkan hasil sebagai berikut:
 
> Setelah program di run, maka akan diketahui langkah-langkah dalam mencapai Goal State sebagai berikut:
> 
>> a)	Pada langkah awal menginisialisasi root state terlebih dahulu : 
 
>> b)	Kemudian, Algoritma akan mencari langkah-langkah dan menggeser angka yang bersebelahan dengan posisi kosong (0) ke arah yang seharusnya utnutk mrndapatkan Goal Statenya.
>> 
>> c)	Pada setiap iterasi menampilkan langkah demi langkah yang di hasilkan
>>  
>> d)	Kemudian langkah akan berhenti ketika sudah mendapatkan Goal State yang diinginkan, namun pada langkah ini tidak menemukan hasil dikarenakan node yang sangat teracak dan jarak antara root dan goal state sangat jauh. 

> Setiap langkah mewakili langkah perpindahan ubin yang dilakukan untuk mencapai goal state. Algoritma mencoba berbagai kombinasi perpindahan ubin untuk menemukan jalur yang paling efisien menuju goal state. 

> Pada percobaan ini untuk mencapai nilai goal state diperlikan langkah yang panjang, dikarenakan posisi pada root state dan goal state sangat jauh, hal ini juga disebabkan karena node sangat teracak. Sehingga pada percobaan ini belum ada hasil yang diperoleh (gagal). 



       
