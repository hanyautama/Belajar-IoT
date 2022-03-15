## Pendahuluan

IoT (internet of things), Jika internet menghubungkan setiap orang dengan informasi, bahkan dapat berinteraksi. IoT adalah internet yang memungkinkan mesin sebagai partisipan dari jaringan, ya kamu tidak salah, mesin saling terhubung ke internet, memungkinkan untuk saling berinteraksi, baik mengambil data atau berinteraksi secara fisik melalui kapabilitas mesin untuk mengubah keadaan fisik yg ia miliki. Pernyataan terkait IoT tersebut dapat disebut juga sebagai Cyber Physical Systems (CPS). Mesin tersebut bisa menangkap fenomena fisik dengan sensor dan melakukan perubahan fisik dengan aktuator.

IoT sendiri bisa berupa kumpulan sensor, aktuator, atau gabungan keduanya. tergantung dari kebutuhan dari IoT itu sendiri.

Sebelum Iot kita mengenal adanya SCADA (Supervisory Control And Data Acquisition) yg menggunakan PLC untuk kebutuhan otomasi. SCADA memeungkinkan untuk melakukan supervisory pada unit-unit PLC di suatu otomasi, walaupun sudah memperoleh level supervisory, SCADA tidak kompatibel dengan internet karena menggunakan proprietary protocol tentu saja solusi PLC eksklusif untuk suatu merek tertentu saja, merek yg berbeda tidak bisa saling terhubung.  sehingga protokol machine to machine sebenarnya sudah ada sejak lama tapi penggunaan protokol proprietary menyebabkan solusi ini terkurung dalam silo (tempurung). dukungan TCP/IP dan semakin tingginya tingakt itntegrasi ygn memungkins chip menjadi SoC (system on Chip), satu chip memiliki banyak kapabilitas salah satunya stack TCP/Ip pada perangkat controller memungkinkan berinteraksi menggunakan protokol standar. bayangkan sekarang ESP886 dan ESP32 memiliki kapabilitas wifi TCP/IP dengan ukuran yg sangat kecil. sedangkan untuk PLC kita memerlukan komponen yg cukup besar dan mahal.

IoT adalah leverage untuk membuka akses SCADA yg berbentuk silo-silo yg tidak saling terhubung, untuk dapat diakses dengan protokol internet yg standar. IoT memberikan kapabilitas untuk memperoleh data aktual di lapangan, jika anda menginginkan kontrol maka IoT akan memberikan hal paling penting dari internet yaitu akses dari manapun dan kapanpun. tentu saja penggunaan IoT memiliki dampak baik dan buruk.

kapabilitas TCP/IP memungkinkan mesin ini terhubung ke internet yg berarti kemungkinan tanpa batas. semua data yg dikumpulkan secara aktual tentu saja membuat sistem penentuan keputusan akan semakin baik, selain itu surveillance akan menjadi hal yg menarik sekaligus menakutkan. 