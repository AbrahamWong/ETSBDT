# Tugas ETS Basis Data Terdistribusi

Buatlah infrastruktur basis data terdistribusi menggunakan skema replikasi multi-master. Kemudian, gunakan infrastruktur dalam sebuah aplikasi.

1. Desain dan implementasi infrastruktur
	a. Desain infrastruktur basis data terdistribusi + load balancing
	b. Implementasi infrastruktur basis data terdistribusi

2. Penggunaan basis data terdistribusi dalam aplikasi
	a. Instalasi aplikasi tambahan (misal: Apache web server, PHP, dsb)
	b. Konfigurasi aplikasi tambahan tersebut
	c. Deskripsi aplikasi yang dipakai (bisa berupa project yang pernah dibuat sebelumnya, web CMS yang tinggal pakai (Wordpress, Joomla, Moodle, dsb), aplikasi desktop dengan backend database, dll).
	d. Konfigurasi aplikasi untuk menggunakan basis data terdistribusi yang telah dibuat.

3. Simulasi fail-over
	a. Lakukan fail-over dengan cara mematikan salah satu server basi data.
	b. Tunjukkan bahwa aplikasi tetap dapat berjalan dengan baik
	c. Jalankan kembali server yang sebelumnya mati
	d. Tunjukkan bahwa server yang sebelumnya mati telah kembali normal dan memiliki data yang sama dengan server yang lain


## Desain dan Implementasi Infrastruktur
### Desain infrastruktur basis data terdistribusi + load balancing
![Design dari infrastruktur BDT](Pic/Design.png)

Ada 4 server dalam desain infrastruktur ini:
	- Database Server
		1. Database Server 1
			- OS = ```Ubuntu 16.04```
			- RAM = ```1024 MB```
			- IP = ```192.168.17.65```
		2. Database Server 2
			- OS = ```Ubuntu 16.04```
			- RAM = ```1024 MB```
			- IP = ```192.168.17.66```
		3. Database Server 3
			- OS = ```Ubuntu 16.04```
			- RAM = ```1024 MB```
			- IP = ```192.168.17.67```
	- Load Balancer
		1. Load Balancer / Proxy Server
			- OS = ```Ubuntu 16.04```
			- RAM = ```1024 MB```
			- IP = ```192.168.17.68``` 

### Implementasi infrastruktur basis data terdistribusi



## Penggunaan Basis Data Terdistribusi dalam Aplikasi

## Simulasi Fail - Over