# LiDAR-Pendeteksi-objek-3D-untuk-mengemudi-otomatis

LiDAR merupakan suatu teknologi sensor dalam melakukan pemetaan, pemantauan, serta survei lingkungan atau topografi.
LiDAR merupakan singkatan dari "Light Detection and Raging".
LiDAR biasanya dimanfaatkan dalam kendaraan otonom, pemetaan dan pemodelan objek 3D, navigasi penerbangan dan masih banyak lagi.
Autonomous driving atau pengemudian otomatis membutuhkan pendeteksi objek 3D dalam penggunaanya.
Untuk dapat bisa mendeteksi dan mengenali objek disekitar, biasanya kendaraan otonom menggunakan teknologi LiDAR yang dipadukan dengan sensor lain, seperti kamera atau radar.
Selain itu, teknologi LiDAR pada kendaraan otonom juga dapat digunakan untuk navigasi dan pemetaan yang dapat menjaga posisi, tanda-tanda, serta mengidentifikasi rintangan di jalan.
LiDAR dapat bekerja diberbagai kondisi cuaca yang memungkinkan kendaraan otonom dapat berjalan diberbagai kondisi.
Namun, LiDAR tergolong teknologi yang mahal. Tetapi, LiDAR dapat mendeteksi masukan data objek 3D dengan sangat akurat hingga saat ini.
Karena jika menggunakan pendekatan model berdasar gambar stereo, maka hasil yang ditampilkan akan memiliki akurasi yang sangat rendah.
Sehingga dengan jarak data yang terlampau jauh dari kedua teknologi tersebut, maka dibuatlah pendekatan yang meniru sinyal LiDAR yang menerapkan algoritma berbasis LiDAR dengan menggunakan KITTI Dataset. Hal inilah yang disebut dengan Pseudo-LiDAR.

KITTI atau Karlsruhe Institute of Technology and Toyota Technological Institute merupakan suatu benchmark untuk menguji teknologi kendaraan otonom.
Dataset KITTI menyediakan data realistis dan bervariasi dari berbagai sensor, seperti LiDAR, kamera dan GPS.
KITTI dapat mengevaluasi terkait pengenalan objek, pergerakan kendaraan, serta klasifikasi objjek dalam gambar.
KITTI juga digunakan untuk mengembangkan algoritma kendaraan otonom.
 
Proyek ini membutuhkan python sebagai bahasa pemogram untuk mengestimasi kedalaman model stereo. lalu membutuhkan library python seperti NumPy yang digunakan untuk komputasi numerik, scipy yang merupakan library komputasi sains, serta Scikit-learn yang merupakan library untuk machine learning. Setelah itu, membutuhkan juga KITTI 3D dataset.

Pseudo-LiDAR dapat menjadi alternatif penggunaan LiDAR pada kendaraan otonom yang harganya tergolong mahal. Dengan mengikuti algoritma LiDAR dan menggunakan KITTI dataset dapat meningkatkan akurasi pendeteksian objek dalam jarak 30m dari 22% hingga 74% hal ini membuktikan bahwa Pseudo-LiDAR merupakan teknologi yang dapat dikatakan efisien dan terjangkau.
