# Bypass Admin Brute Force
Coded by : Revan AR
Team : IndoSec

NB : Tools ini gak work di semua website ^^
kalian bisa kembangin sendiri tools nya sesuai keinginan dan kebutuhan kalian :v :D 

Tutorial :

pertama, kalian harus tau dulu bahwa data username & password mau di kirim kemana..
kedua, kalian juga harus tau nama dari form input username & passwordnya, kalian juga harus tau nama
dari tombol submitnya..

contoh : misal web targetnya => www.target.com/admin/login.php
kalian buka dulu webnya.. klik CTRL + U (atau bisa juga pakai view-source:www.target.com/admin/login.php)

cari tag html yg seperti dibawah ini atau sejenisnya :D

<form action="cek_login.php" method="post"> // ini untuk URL POST
  <input type="text" name="username" placeholder="your username"> // ini untuk FORM USER NAME
  <input type="password" name="password" placeholder="your password"> // ini untuk FORM PASSWORD NAME
  <input type="submit" name="submit" value="login"> // ini untuk BUTTON SUBMIT NAME
</form>

jalankan file tools nya,
di bagian URL POST kalian isi dengan www.target.com/admin/cek_login.php
di bagian FORM USER NAME diisi dengan username
di bagian FORM PASSWORD NAME diisi dengan password
terakhir, di bagian BUTTON SUBMIT NAME diisi dengan submit

setelah itu tinggal tunggu hasilnya ^^

Jika di bagian form action dia kosong, contoh ==> <form action="" method="post">
di bagian URL POST kalian isi sesuai halaman login web target
  
contoh, jika web targetnya www.target.com/administrator
berarti di bagian URL POST kalian isi sesuai web target ==> www.target.com/administrator


Thanks to Yogi Rahmat (member Error Violence)
kemarin dia yg kasih ide buat bikin tools ini hehe ^_^



