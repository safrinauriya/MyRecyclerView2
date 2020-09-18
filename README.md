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
