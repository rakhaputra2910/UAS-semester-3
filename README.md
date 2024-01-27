# UAS-semester-3
NO1
{
  "universitas": "Djuanda",
  "prodi": "Ilmu Komputer",
  "iat": 1674270000
}

NO 2
Struktur Aplikasi
•	Arsitektur Monolitik
  o	Aplikasi tunggal yang terdiri dari semua komponen yang diperlukan untuk menjalankannya.
  o	Komponen-komponen ini dapat berupa kode, data, dan sumber daya lainnya.
  o	Aplikasi monolitik biasanya dibangun dengan satu teknologi dan bahasa pemrograman.
•	Arsitektur Microservices
  o	Aplikasi terdistribusi yang terdiri dari beberapa layanan independen yang saling berkomunikasi.
  o	Setiap layanan bertanggung jawab untuk satu fungsi atau logika bisnis tertentu.
  o	Layanan-layanan ini dapat dibangun dengan teknologi dan bahasa pemrograman yang berbeda.
Skalabilitas
•	Arsitektur Monolitik
  o	Skalabilitas horizontal sulit karena semua komponen aplikasi harus diskala secara bersamaan.
•	Arsitektur Microservices
  o	Skalabilitas horizontal mudah karena setiap layanan dapat diskala secara independen.
Pengembangan dan Pemeliharaan
•	Arsitektur Monolitik
  o	Pengembangan dan pemeliharaan lebih mudah karena semua komponen aplikasi berada dalam satu tempat.
o	Pengembang dapat dengan mudah memahami bagaimana aplikasi bekerja dan membuat perubahan.
•	Arsitektur Microservices
  o	Pengembangan dan pemeliharaan lebih kompleks karena setiap layanan harus dikelola secara terpisah.
  o	Pengembang harus memahami bagaimana setiap layanan bekerja dan bagaimana layanan-layanan tersebut saling berinteraksi.
Ketergantungan antar komponen
•	Arsitektur Monolitik
  o	Ketergantungan antar komponen yang sangat tinggi.
  o	Setiap komponen bergantung pada komponen lain untuk berfungsi.
  o	Hal ini dapat menyebabkan masalah jika salah satu komponen mengalami masalah.
•	Arsitektur Microservices
  o	Ketergantungan antar komponen yang lebih rendah.
  o	Setiap layanan hanya bergantung pada layanan lain yang diperlukan untuk menjalankan fungsinya.
  o	Hal ini dapat membantu mengurangi risiko masalah jika salah satu layanan mengalami masalah.
Teknologi dan Bahasa Pemrograman
•	Arsitektur Monolitik
  o	Teknologi dan bahasa pemrograman yang digunakan harus kompatibel dengan semua komponen aplikasi.
  o	Hal ini dapat membatasi pilihan teknologi dan bahasa pemrograman yang dapat digunakan.
•	Arsitektur Microservices
  o	Teknologi dan bahasa pemrograman dapat berbeda untuk setiap layanan.
  o	Hal ini dapat memberikan lebih banyak fleksibilitas dan pilihan bagi pengembang.
Pengelolaan Data
•	Arsitektur Monolitik
  o	Biasanya menyimpan data dalam satu database atau penyimpanan data.
  o	Hal ini dapat memudahkan pengelolaan data karena semua data berada di satu tempat.
•	Arsitektur Microservices
  o	Dapat menyimpan data di beberapa database atau penyimpanan data.
  o	Hal ini dapat meningkatkan kinerja dan keamanan data.
  
NO 3

Middleware adalah perangkat lunak yang menjembatani komunikasi antara aplikasi dan sistem operasi atau perangkat keras. Middleware dapat digunakan untuk berbagai tujuan, termasuk:
    •	Komunikasi antara aplikasi: Middleware dapat digunakan untuk menghubungkan aplikasi yang berjalan di komputer yang berbeda atau di platform yang berbeda.
    •	Pengelolaan data: Middleware dapat digunakan untuk mengelola data yang dibagikan oleh beberapa aplikasi.
    •	Keamanan: Middleware dapat digunakan untuk menyediakan keamanan untuk aplikasi dan data.
    •	Manajemen aplikasi: Middleware dapat digunakan untuk mengelola aplikasi, termasuk penyebaran, pemeliharaan, dan pemantauan.
Keuntungan dari penerapan middleware antara lain:
    •	Meningkatkan skalabilitas: Middleware dapat membantu meningkatkan skalabilitas aplikasi dengan memungkinkan aplikasi untuk didistribusikan ke beberapa server.
    •	Meningkatkan kinerja: Middleware dapat membantu meningkatkan kinerja aplikasi dengan memindahkan tugas-tugas yang tidak penting dari aplikasi ke middleware.
    •	Meningkatkan keamanan: Middleware dapat membantu meningkatkan keamanan aplikasi dengan menyediakan fitur-fitur keamanan, seperti otentikasi dan enkripsi.
    •	Meningkatkan kemudahan pengembangan dan pemeliharaan: Middleware dapat membantu menyederhanakan pengembangan dan pemeliharaan aplikasi dengan menyediakan fungsi-fungsi yang umum digunakan.
Berikut adalah beberapa contoh middleware yang umum digunakan:
    •	Web server: Web server adalah jenis middleware yang digunakan untuk menyajikan halaman web kepada pengguna.
    •	Database server: Database server adalah jenis middleware yang digunakan untuk menyimpan dan mengelola data.
    •	Application server: Application server adalah jenis middleware yang digunakan untuk menjalankan aplikasi.
    •	Message broker: Message broker adalah jenis middleware yang digunakan untuk mengirimkan pesan antar aplikasi.
    •	Enterprise service bus (ESB): ESB adalah jenis middleware yang digunakan untuk menghubungkan aplikasi yang berbeda.

NO 4
Unit testing adalah metode pengujian perangkat lunak yang berfokus pada unit-unit kecil kode, biasanya berupa fungsi atau metode. Unit testing bertujuan untuk memastikan bahwa setiap unit kode berfungsi dengan benar.
Metode unit testing yang umum digunakan:
    •	Black box testing: Pengujian tanpa melihat kode sumber.
    •	White box testing: Pengujian dengan melihat kode sumber.
    •	Boundary value testing: Pengujian dengan memberikan input yang berada di batas-batas nilai yang diperbolehkan.
    •	Error handling testing: Pengujian dengan memberikan input yang menyebabkan kesalahan.
    •	Performance testing: Pengujian untuk mengukur kinerja unit kode.
Manfaat unit testing:
    •	Meningkatkan kualitas kode: Unit testing dapat membantu menemukan bug dan kekurangan dalam kode.
    •	Meningkatkan produktivitas: Unit testing dapat membantu mempercepat proses pengembangan dan pemeliharaan kode.
    •	Meningkatkan dokumentasi: Unit testing dapat menjadi dokumentasi fungsional kode.
    •	Meningkatkan kemudahan perawatan: Unit testing dapat membantu mempermudah proses perawatan kode.

NO 5
    •	Kontainerisasi adalah teknologi yang memungkinkan pengembang untuk mengemas aplikasi dan semua dependensinya ke dalam unit mandiri yang disebut kontainer. Kontainer dapat berjalan       di berbagai platform dan infrastruktur, sehingga dapat membantu meningkatkan portabilitas dan skalabilitas aplikasi.
    •	Docker adalah platform kontainerisasi yang populer yang menyediakan alat dan layanan yang memudahkan pengembang untuk membuat, menjalankan, dan mengelola kontainer.
    •	Kubernetes adalah sistem orkestrasi kontainer yang terbuka dan sumber terbuka yang menyediakan fitur-fitur untuk mengotomatiskan penyebaran, penskalaan, dan pengelolaan kontainer 
      di lingkungan yang kompleks.

NO 6 
CI/CD adalah praktik pengembangan perangkat lunak yang menggabungkan proses pembangunan, pengujian, dan penyebaran kode secara otomatis dan berulang.
Manfaat CI/CD antara lain:
    •	Meningkatkan kualitas kode: CI/CD membantu untuk mendeteksi dan memperbaiki bug sejak dini.
    •	Meningkatkan produktivitas: CI/CD membantu untuk mempercepat proses pengembangan dan penyebaran kode.
    •	Meningkatkan keandalan: CI/CD membantu untuk memastikan bahwa kode yang didistribusikan ke produksi adalah kode yang berkualitas dan berfungsi dengan baik.
Tools CI/CD yang umum digunakan antara lain:
    •	Jenkins: Jenkins adalah alat CI/CD open source yang populer.
    •	Travis CI: Travis CI adalah alat CI/CD open source yang populer.
    •	GitLab CI/CD: GitLab CI/CD adalah alat CI/CD yang terintegrasi dengan GitLab.
    •	CircleCI: CircleCI adalah alat CI/CD berbayar.

