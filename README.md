
Linux_Ownership

===============
Pada gambar 1 --> menjelaskan pembuatan sebuah folder / direktory. Dengan mengetikkan " mkdir nama_folder".
Pada gambar 2 --> melihat kepemilikan dari suatu folder / direktory. Dengan mengetikkan " ls -li ".
Pada gambar 3 --> menjelaskan cara masuk ke dalam sebuah direktory / folder. Dengan mengetikkan " cd nama_folder ".
Pada gambar 4 --> menjelaskan cara untuk membuat sebuah file. Dengan mengetikkan " touch nama_file ".
Pada gambar 5 --> melihat kepemilikan dari suatu file. Dengan mengetikkan " ls -li ".
Pada gambar 6 --> menjelaskan tentang bagaimana cara membuat sebuah group. Dengan mengetikkan " groupadd nama_group ".
Pada gambar 7 --> menjelaskan tentang bagaimana cara membuat user di dalam group. Dengan mengetikkan " useradd -G nama_group nama_user ".
Pada gambar 8 --> merupakan cara merubah ownership dari suatu file, ada beberapa cara tapi yang saya contohkan adalah memasukkan ke dalam user dan group yang sudah kita buat tadi. Dengan mengetikkan " chown nama_user.nama_group nama_file". Kemudian chek dengan perintah " ls -li ".
Pada gambar 9 --> merupakan cara merubah ownership dari suatu folder / direktory, ada beberapa cara tapi yang saya contohkan adalah memasukkan ke dalam user dan group yang sudah kita buat tadi. Dengan mengetikkan " chown nama_user.nama_group nama_folder". Kemudian chek dengan perintah " ls -li ".
CUKUP TAHU : pada perintah dengan menggunakan "SUDO" digunakan pada saat untuk mendapat akses dari super user.