# SHS Store

## Tugas 1

### Apa perbedaan utama antara stateless dan stateful widget dalam konteks pengembangan aplikasi Flutter?
1. **StatelessWidget**
    - Tidak Berubah: Sebuah StatelessWidget tidak dapat mengubah statenya selama masa hidupnya. Ini berarti bahwa setelah widget dibuat, nilai-nilai dan konfigurasinya tetap sama.
    - Sederhana dan Cepat: Karena tidak ada manajemen state, pembuatan ulang widget (rebuilding) berlangsung dengan sangat cepat.
    - Contoh Penggunaan: Cocok untuk bagian UI yang sederhana dan tidak berubah, seperti ikon, teks, dan gambar yang statis.
2. **StatefulWidget**
    - Dinamis: Sebuah StatefulWidget mampu mengubah statenya sepanjang masa hidupnya. Ini berarti bahwa widget dapat memperbarui UI berdasarkan interaksi pengguna atau data eksternal.
    - Lebih Kompleks: Dibandingkan dengan StatelessWidget, StatefulWidget memerlukan manajemen state yang lebih kompleks. Ini mempengaruhi performa terutama jika banyak pembaruan state terjadi.
    - Pemeliharaan State: StatefulWidgets memiliki objek state terpisah yang menyimpan state. Objek state ini bertahan meski terjadi hot reload dan pembuatan ulang widget.
    - Contoh Penggunaan: Cocok untuk bagian UI yang memerlukan interaksi pengguna atau pembaruan data, seperti formulir, animasi, atau timer.

### Sebutkan seluruh widget yang kamu gunakan untuk menyelesaikan tugas ini dan jelaskan fungsinya masing-masing.
1. **MyHomePage:** Kelas ini merepresentasikan halaman utama aplikasi Anda. Ia mengextends StatelessWidget, yang berarti ia tidak mempertahankan state apapun antar pemanggilan build.
2. **Scaffold:** Widget yang menyediakan struktur dasar tampilan visual untuk aplikasi, termasuk AppBar, body, dan floatingActionButton.
3. **AppBar:** Sebuah Material Design app bar. Biasanya digunakan untuk menampilkan judul aplikasi, branding, atau navigasi.
4. **Text:** Widget yang menampilkan serangkaian karakter dengan gaya yang dapat disesuaikan.
5. **SingleChildScrollView:** Sebuah box yang dapat scroll, yang cocok untuk box tunggal yang akan memiliki beberapa anak tetapi tidak semua anak terlihat sekaligus.
6. **Padding:** Widget yang memberikan padding pada widget anaknya.
7. **Column:** Sebuah box yang menampilkan anak-anaknya dalam urutan vertikal.
8. **GridView:** Sebuah scrollable grid yang menampilkan widget sebagai tiles.
9. **ShopCard:** Kelas widget buatan sendiri yang menerima objek ShopItem dan menampilkan informasinya dalam bentuk card.
10. **Material:** Sebuah widget yang memberikan tampilan berdasarkan Material Design.
11. **InkWell:** Sebuah rectangle area yang dapat diklik dan memberikan efek visual saat ditekan.
12. **Container:** Sebuah box yang mengandung widget lain dan dapat diatur untuk memberikan padding, margin, ukuran, dan lain-lain.
13. **Icon:** Widget yang menampilkan sebuah ikon Material Design.
14. **Center:** Sebuah widget yang menengahkan widget anaknya.

### Jelaskan bagaimana cara kamu mengimplementasikan checklist di atas secara step-by-step (bukan hanya sekadar mengikuti tutorial)