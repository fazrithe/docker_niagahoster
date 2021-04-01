1. Clone git@github.com:fazrithe/docker_niagahoster.git
2. Masuk ke docker_file
3. setup file image di folder sites
4. project ada di dalam forlder www
5. dokcer-compose up
6. setup host jika di perlukan, berada di /etc/host atau dapat menggunakan IP Address 
   untuk mengkonfigurasi host ada di folder sites/niagahoster.conf
7. Update server_name dengan IP Address/host pada line 11
8. setelah selesai maka jalankan docker-compose up 
9. untuk menjalankan file dokcer-compose excec php /bin/bash

BOXBILLING
1. Masuk ke folder www
2. CLone git clone https://github.com/boxbilling/boxbilling
3. cd boxbilling
4. make all
5. remove folder install dalam folder boxbilling

Niagahoster
1. Masuk ke folder www
2. Clone git@github.com:fazrithe/niagahoster_test.git
3. Composer install
4. Update .env
	- DB_CONNECT=mysql
	- DB_HOST="Menggunakan IP Address"
	- DB_PORT="9009"
5. php artisan  key:generate
6. php artisan migrate


1. Clone git@github.com:fazrithe/docker_niagahoster.git
2. In to docker_file
3. setup image file in sites filder
4. project in forlder www
5. dokcer-compose up
6. host setup if needed, in /etc/host or can use the IP Address
   To configure the host is in the sites / niagahoster.conf folder
7. Update server_name with IP Address/host in line 11
8. when finished then run docker-compose up 
9. to run the docker-compose exec php / bin / bash file

BOXBILLING
1. in to www folder
2. CLone git clone https://github.com/boxbilling/boxbilling
3. cd boxbilling
4. make all
5. remove install folder in boxbilling folder

Niagahoster
1. in to www folder
2. Clone git@github.com:fazrithe/niagahoster_test.git
3. Composer install
4. Update .env
	- DB_CONNECT=mysql
	- DB_HOST="Menggunakan IP Address"
	- DB_PORT="9009"
5. php artisan  key:generate
6. php artisan migrate


