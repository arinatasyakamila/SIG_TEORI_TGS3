# SIG_TEORI_TGS3
 importing spritsheet csv file
 
 Langkah Kerja :

1. Periksa sumber data tabular Anda. Basis data gempa yang diunduh berisi bidang Lintang dan Bujur yang menunjukkan lokasi pusat gempa dan atribut terkait lainnya. Kami akan menggunakan bidang ini untuk mengimpor file sebagai lapisan titik. Buka data dalam editor teks seperti Notepad/TextMate untuk melihat isinya. Anda akan melihat bahwa TAB memisahkan setiap bidang.

2. QGIS hadir dengan pengelola data terpadu yang memungkinkan Anda memuat semua berbagai format data yang didukung. Klik tombol Buka Pengelola Sumber Data pada Bilah Alat Sumber Data. Anda juga dapat menggunakan pintasan keyboard Ctrl + L.

3. Dalam kotak dialog Pengelola Sumber Data, alihkan ke tab Teks Dibatasi. Klik tombol … di sebelah nama File.

4. Tergantung pada sistem operasinya, Anda mungkin atau mungkin tidak melihat file di lokasi yang diunduh. Dalam format File, alihkan ke Semua file (; *.) untuk melihat file tsv.

5. Sekarang Anda akan melihat file yang diunduh. Pilih itu dan klik Buka.

6. Di kotak dialog Pengelola Sumber Data, jalur ke file akan tersedia di Nama File. Ubah nama Layer menjadi 1900_2000_earthquakes. Di bagian Format file, pilih Pembatas khusus dan centang Tab. Di bagian Definisi geometri, pilih Koordinat titik. Secara default, nilai bidang X dan bidang Y akan terisi secara otomatis jika menemukan bidang nama yang sesuai di input. Dalam kasus kami, mereka adalah Bujur dan Lintang. Anda dapat mengubahnya jika impor memilih bidang yang salah. Anda dapat membiarkan Geometry CRS ke default EPSG:4326 - WGS 84 CRS. Jika file Anda berisi koordinat dalam CRS yang berbeda, Anda dapat memilih CRS yang sesuai di sini. Klik Tambahkan.

7. Anda sekarang akan melihat bahwa data akan diimpor dan ditampilkan di kanvas QGIS sebagai layer baru yang disebut 1900_2000_earthquakes dengan CRS EPSG:4326
