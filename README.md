# MyRecyclerView
RecyclerView adalah sebuah komponen tampilan (widget) yang lebih canggih ketimbang pendahulunya listview. Ia bersifat lebih fleksibel. 
RecyclerView memiliki kemampuan untuk menampilkan data secara efisien dalam jumlah yang besar.
Terlebih jika Anda memiliki koleksi data dengan elemen yang mampu berubah-ubah sewaktu dijalankan (runtime).
[Informasi Selengkapnya](https://developer.android.com/guide/topics/ui/layout/recyclerview?hl=id)
## Komponen Recycler View
- [x] 1.	**RecyclerView dan LayoutManager**: Komponen antarmuka yang bertugas untuk menampilkan data set yang dimiliki di dalamnya. Layoutmanager akan mengatur posisi tampilan data baik itu secara list (vertikal), grid (baris dan kolom) atau staggered grid (grid yang memiliki susunan tak seragam / tak beraturan).
- [x] 2.	**Adapter**: Komponen yang akan mengatur bagaimana menampilkan data set ke dalam RecyclerView. Di sinilah terjadi proses pengisian tampilan (ViewInflate) dari file layout xml untuk tiap elemen dari data yang sebelumnya terpasang (bind) ke dalam RecyclerView.
- [x] 3.	**Dataset**: Kumpulan data yang dimiliki dan ingin ditampilkan. Bisa berupa array, list maupun obyek map.
- [x] 4.  **Item Animator**: Ini yang spesial. Kita bisa pasang animasi untuk tiap item di dalamnya. Contoh animasi yang umum seperti penambahan (add) dan penghapusan (removal) item. Kita akan mempelajari hal ini pada materi terpisah.
## Tampilan List Mode
![Screenshot_20200918-201642_MyRecyclerView](https://user-images.githubusercontent.com/60589670/93603995-fb304a00-f9ee-11ea-99fa-f97ab4afec56.jpg)
![Screenshot_20200918-201655_MyRecyclerView](https://user-images.githubusercontent.com/60589670/93604002-fcfa0d80-f9ee-11ea-9687-10e98ecd5073.jpg)
## Tampilan Grid Mode
![Screenshot_20200918-201742_MyRecyclerView](https://user-images.githubusercontent.com/60589670/93604168-3763aa80-f9ef-11ea-8683-9b492bd0016c.jpg)
## Tampilan Full
![Screenshot_20200918-201625_MyRecyclerView](https://user-images.githubusercontent.com/60589670/93604137-2dda4280-f9ef-11ea-9665-0a6ed5bc11c9.jpg)
## Tampilan Menu
![Screenshot_20200918-201732_MyRecyclerView](https://user-images.githubusercontent.com/60589670/93604151-33378d00-f9ef-11ea-8f72-b8d9a916fcff.jpg)

