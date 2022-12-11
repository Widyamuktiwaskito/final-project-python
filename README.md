# final-project-python
Membuat program transaksi self-service sederhana
Background
Andi adalah seorang pemilik supermarket besar di salah satu kota di Indonesia. Andi memiliki rencana untuk melakukan ekspansi bisnis, yaitu Andi akan membuat sistem kasir yang self-service di supermarket miliknya. Sehingga, customer bisa langsung memasukkan item yang dibeli, jumlah item yang dibeli, dan harga item yang dibeli dan fitur yang lain. Sehingga, customer yang tidak berada di kota tersebut bisa membeli barang dari supermarket tersebut.
Setelah Andi melakukan riset, ternyata Andi memiliki masalah, yaitu Andi membutuhkan Programmer untuk membuatkan fitur-fitur agar bisa sistem kasir self-service di supermarket itu bisa berjalan dengan lancar.
Requirements
Membuat fitur dimana user bisa melakukan hal-hal berikut:
- Membuat ID transaksi
- Memasukan daftar barang ke daftar belanjaan
- Update atau edit daftar belanjaan
- Menghapus barang pada daftar belanjaan
- Reset transaksi
- Melihat/mengecek daftar belanjaan
- Menghitung total harga daftar belanjaan
Untuk bisa menjalankan fitur-fitur tersebut, maka diperlukan data berikut ini:
- Nama barang
- Harga barang per satuan
- Satuan
Workflow
Background --> Requirements --> Solution --> Pseudocode --> Code --> Test Caset --> Conclusion
Solution
Membuat ID transaksi
- transaction_n = Transaction()
Memasukan daftar barang ke daftar belanjaan
- transaction_n.add_to_cart()
Update atau edit daftar belanjaan
- transaction_n.update_cart()
Menghapus barang pada daftar belanjaan
- transaction_n.delete_item()
Reset transaksi
- transaction_n.reset_order()
Melihat/mengecek daftar belanjaan
- transaction_n.check_order()
(Tambahan) Menampilkan daftar barang yang tersedia di supermarket
- transaction_n.check_item()

Sekian dan terima kasih!
