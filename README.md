# MyRecyclerView Revisi
RecyclerView adalah sebuah komponen tampilan (widget) yang lebih canggih ketimbang pendahulunya listview. Ia bersifat lebih fleksibel. 
RecyclerView memiliki kemampuan untuk menampilkan data secara efisien dalam jumlah yang besar.
Terlebih jika Anda memiliki koleksi data dengan elemen yang mampu berubah-ubah sewaktu dijalankan (runtime).
[Informasi Selengkapnya](https://developer.android.com/guide/topics/ui/layout/recyclerview?hl=id)
## Perbedaan
Perbedaan dengan yang sebelumnya yaitu:
- [x] Penambahan tampilan judul halaman aplikasi di setiap perubahan bentuk RecyclerView
- [x] Penambahan mode CARD VIEW
- [x] Penambahan item OnClickListener pada ListView
- [x] Tampilan Toast sebagai aksi 
## Tampilan List Mode
Menampilkan sejumlah informasi dalam bentuk list. List adalah komponen yang menampilkan kumpulan item dalam bentuk daftar, sedangkan list item adalah komponen yang merepresentasikan tiap-tiap item di dalam suatu daftar. Perbedaan dari yang sebelumnya terletak pada TITLE/JUDUL halaman di aplikasi setiap perubahan bentuk dari RecyclerView.
[Selengkapnya..](https://developer.android.com/guide/topics/ui/layout/recyclerview?hl=id)

![image](https://user-images.githubusercontent.com/60589670/94274058-68078f00-ff6f-11ea-8f00-22a81eee432e.png)
## Tampilan Grid Mode
Tampilan grid mode menampilkan menu dalam bentuk foto/grid.Perbedaan dari yang sebelumnya terletak pada TITLE/JUDUL halaman di aplikasi setiap perubahan bentuk dari RecyclerView.

![Screenshot_20200925-172815_MyRecyclerView](https://user-images.githubusercontent.com/60589670/94280516-b0c34600-ff77-11ea-994b-884bedd78355.jpg)
## Tampilan Card View
CardView berfungsi sebagai wrapper/frame layout yang akan membungkus layout di dalamnya dengan desain menyerupai kartu. CardView membungkus suatu layout dan biasanya dipakai sebagai container untuk setiap item di dalam ListView atau RecyclerView.
[Selengkapnya..](https://developer.android.com/guide/topics/ui/layout/cardview?hl=id)
[Lebih detail](https://medium.com/easyread/tutorial-android-recyclerview-dan-cardview-9a62aaa6cc0c)

![Screenshot_20200925-172835_MyRecyclerView](https://user-images.githubusercontent.com/60589670/94280588-c7699d00-ff77-11ea-8f7f-c209e76df18b.jpg)
## List View dan Toast
Listview memiliki listener untuk melakukan sebuah aksi ketika salah satu item pada list dipilih. Untuk menandai berjalannya sebuah aksi akan muncul Toast. Toast adalah sebuah mekanisme di Andorid untuk menampilkan popup kecil sebagai sebuah feedback dan akan menghilang setelah beberapa waktu.[Selengkapnya..](https://developer.android.com/guide/topics/ui/notifiers/toasts)
Jika menekan list pahlawan/foto (grid)/card maka akan muncul notifikasi Toast sebagai aksi.

* Tampilan Toast Pada Mode List
![Screenshot_20200925-173642_MyRecyclerView](https://user-images.githubusercontent.com/60589670/94282294-d6514f00-ff79-11ea-80ea-1838f27faf6a.jpg)
* Tampilan Toast Pada Mode Grid
![Screenshot_20200925-173606_MyRecyclerView](https://user-images.githubusercontent.com/60589670/94282358-eec16980-ff79-11ea-9d1c-627d7a1d57b9.jpg)
* Tampilan Toast Pada CardView
![Screenshot_20200925-172844_MyRecyclerView](https://user-images.githubusercontent.com/60589670/94282326-e36e3e00-ff79-11ea-9127-c3fc3a8e1bc5.jpg)

Terima Kasih
