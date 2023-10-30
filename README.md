# ARTIFICIAL INTELLIGENCE
## Praktikum 4
**TUGAS**
1. Tentukan bagaimana algoritma BFS di atas dapat menentukan node ke 8, 6, dan 7. 2.
2. Ubahlah method static void main sehingga bentuk tree seperti Gambar 4.5 dapat dibentuk. Kemudian tentukan bagaimana algoritma BFS dapat menemukan node 5.
3. Ubahlah method static void main sehingga bentuk tree seperti Gambar 4.6 dapat dibentuk. Kemudian tentukan bagaimana algoritma BFS dapat menemukan node 9.
4. Ubahlah kode program di atas sehingga bentuk tree seperti Gambar 4.7 dapat dibentuk. Kemudian tentukan bagaimana algoritma BFS dapat menemukan node C.

**PENYELESAIAN**
1. Algoritma BFS (Breadth-First Search) adalah salah satu algoritma pencarian dalam ilmu komputer yang digunakan untuk menjelajahi atau mencari informasi dalam graf atau struktur data berdasarkan tingkat jarak atau kedalaman dari node awal. Algoritma ini bekerja dengan cara menjelajahi node-node yang terhubung secara langsung dengan node awal sebelum mengeksplorasi node-node yang lebih dalam atau lebih jauh. Berikut merupakan langkah Pada Algoritma BFS.
   * aj
   * ass
2. aba\
   ![alt text](https://github.com/Anggunfia/Praktikum-4-dan-5/blob/main/Gambar/Gambar%201.png?raw=true)
4. a
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



       
