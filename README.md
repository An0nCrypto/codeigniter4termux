#Install codeigniter4 Via termux
pertama install composer, Caranya ada di https://www.abrahamyusuf.my.id/2020/11/cara-install-composer-di-termux-coding.html
step pertama install composer:
 
 $ pkg up
 
 $ pkg instal curl
 
 $ pkg instal php
 
 $ curl -sS https://getcomposer.org/installer | php -- --install-dir=/data/data/com.termux/files/usr/bin --filename=composer
 
 setelah itu verifikasi
 Menggunakan perintah
 $ composer
 
 anda akan melihat versi termux beserta about dan commandnya.
 Jika perlu update silahkan ikuti command atau perintah seperti dibawah
 $ composer self-update
 
 Periksa ini
 $ which composer
 anda akan melihat output :
 $ /data/data/com.termux/files/usrt/bin/composer
 selamat, anda sukses install composer.
 
 step selanjutnya install CodeIgniter 4.
 ketikkan perintah ditermux
 
 $ composer create-project codeigniter4/appstarter project-root
 
 note : project-root adalah nama folder codeigniter yang anda install, bisa anda ganti.
 
 atau cara kedua, dengan menginstall app starter 
 
 $ composer create-project codeigniter4/appstarter --no-dev
 
 silahkan update terlebih dahulu.
  $ composer update
  
  Done, silahkan jalankan dengan localhost kalian atau webserver yang kalian buat
