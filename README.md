# -Topologi-Jaringan-Enterprise-Skala-Menengah-dengan-OSPF-dan-DHCP-Terpusat-
Proyek simulasi jaringan tingkat enterprise yang mengintegrasikan 4 area terpisah (LAN/VLAN) melalui koneksi WAN berkecepatan tinggi. Repositori ini menampilkan implementasi OSPF routing dinamis untuk memastikan konektivitas end-to-end, serta konfigurasi DHCP Relay yang kompleks untuk layanan terpusat. dan konfigurasi router tersedia.


## topologi :
<img width="707" height="697" alt="image" src="https://github.com/user-attachments/assets/052d9751-1d93-47a8-b002-791c8c9535e8" />

Nah dibagian atas aku menggunakan spanning-tree rapid-pvst karna pas buat switch diatas terjadi loop


## Verifikasi rute subnet ospf 
#### ini di router tengah:

<img width="579" height="188" alt="image" src="https://github.com/user-attachments/assets/4f8e154d-4c9d-4811-a7c3-5ffad3664f09" />

Alasan aku memakai OSPF dari pada RIP dan EIGRP karena OSPF menerutku lebih mudah dengan membuat area menggunakan perintah
ruote ospf 


## bukti keberhasilan :
### liat pesan berhasil dari gedung A(Biru tua) biru ke server dan Gedung B(Kuning) ke Gedung 3(ungu)
<img width="767" height="184" alt="image" src="https://github.com/user-attachments/assets/17139ebf-dbb4-421d-9330-fca696a7187a" />

di file itu semua nya berhasil udah dicoba satu-satu jika ada yg failed biasanya dari cisconya yg butuh waktu untuk recovory coba aja terus sampai berhasil

