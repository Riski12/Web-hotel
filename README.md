# Web-hotel
untuk lebih jelas klik web
http://www.dicsr-qnt.com/2019/06/source-code-website-hotel-dan-booking.html

Terlebih dahulu edit file pada direktori booking>common>config.php
define('DB_PORT', '3306');
define('DB_USER', 'root');
define('DB_PASS', '');

akses localhost pada xampp dengan localhost/booking/admin
user  : admin
Pass  : admin123

untuk upload file banyak edit file php.ini pada xampp>php
edit logo pada direktori :
C:\xampp\htdocs\booking\templates\default\common\header.php edit bagian  getFromTemplate("images/2.png");
ganti 2.png menjadi nama file yg sesuai dengan file pada direktori C:\xampp\htdocs\booking\templates\default\images


