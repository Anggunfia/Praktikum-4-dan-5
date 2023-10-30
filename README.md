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

Setelah di Run, maka akan diketahui langkah-langkah dalam pencapaian goal state sebegai berikut 
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


       
