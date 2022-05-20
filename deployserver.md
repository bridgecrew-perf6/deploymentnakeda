
Cara deployment web baru di server

-	Upload source code ke dalam /var/www/nama-domain/public_html
-	Buka  /etc/apache2/site-available
-	Copy salah satu config  yg berekstensi .conf
-	Ganti nama dengan subdomain baru, dan edit file nya
-	lalu ketik command . “sudo a2ensite nama-domain.conf”
-	restart apache2 dengan ketik command. “Sudo service apache2 restart”
-	kemudian aktifkan ssl pada web. Ketik command “certbot”
-	lalu pilih domain yg mau di daftarkan ssl. Lanjut pilih no redirect


