<h1 text align="center">Tugas 2</h1>

Mata Kuliah | Sistem Operasi
--------|--------
Nim | 2110131110003
Nama | Ady Mutalib

<h1 align=center>Komponen Sistem Operasi, Layanan Sistem Operasi, Sistem Call</h1>
<br>

> # Komponen Sistem Operasi
Sebuah sistem operasi dapat dibagi menjadi beberapa komponen. Secara umum, para pakar sepakat bahwa terdapat sekurangnya empat komponen manajeman utama yaitu: 
1. Manajemen Proses, 
2. Manajemen Memori, 
3. Manajamen Sistem Berkas, dan  
4. Manajemen Masukan/Keluaran.

Selain keempat komponen di atas, Avi Silberschatz, dan kawan-kawan menambahkan beberapa komponen seperti: 
1. Manajemen Penyimpanan Sekunder. 
2. Manajemen Sistem Proteksi. 
3. Manajemen Jaringan. 
4. Command-Interpreter System.

## Contoh Komponen Sistem Operasi yang ada pada laptop saya adalah:
**Manajemen Proses**
- *Proses* adalah sebuah program yang sedang dieksekusi. Sebuah proses membutuhkan beberapa sumber daya untuk menyelesaikan tugasnya.
- *Alokasi sumber daya* tersebut dikelola oleh Sistem Operasi Umpamanya penggunaan CPU, memori, berkas-berkas, dan perangkat-perangkat Masukan/Keluaran. 
- Ketika proses tersebut berhenti dijalankan, sistem operasi akan mendapatkan kembali semua sumber daya yang bisa digunakan kembali. 
- Sistem operasi bertanggung-jawab atas aktivitas-aktivitas yang berkaitan dengan manajemen proses seperti: 
    - Membuat dan menghapus proses pengguna dan sistem proses.
    - Menunda atau melanjutkan proses.
    - Menyediakan mekanisme untuk sinkronisasi proses.
    - Menyediakan mekanisme untuk komunikasi proses.
    - Menyediakan mekanisme untuk penanganan deadlock

Disini saya akan memperlihatkan manajemen proses:

<br>

*Gambar ini diambil dilaptop saya (Task Manager)*

<img src="img/1.png" style="width:40%">
<br>

**Penjelasan :**

- Pada gambar diatas memperlihatkan proses manajemen sistem operasi Task Manager.
- Aplikasi yang berjalan ada 4 :
    - Google Chrome
    - Task Manager
    - Visual Stodio Code
    - Windows Exploler
- Penjelasan masing-masing komponen yang digunakan oleh keempat aplikasi tersebut :
    1. Google Chrome
        - CPU yang digunakan 0.1%
        - Memory yang digunakan 752.5MB
        - Disk yang digunakan 0.1MB/s
        - Network 0.1 Mbps
        - GPU yang digunakan 0%
    2. Taks Manager
        - CPU yang digunakan 0.5%
        - Memory yang digunakan 23.9MB
        - Disk yang digunakan 0.1MB/s
        - Network 0 Mbps
        - GPU yang digunakan 0%
    3. Visual Stodio Code
        - CPU yang digunakan 0%
        - Memory yang digunakan 204.8MB
        - Disk yang digunakan 0 MB/s
        - Network 0 Mbps
        - GPU yang digunakan 0%
    4. Windows Exploler
        - CPU yang digunakan 0.1%
        - Memory yang digunakan 26.6MB
        - Disk yang digunakan 0.1 MB/s
        - Network 0 Mbps
        - GPU yang digunakan 0%

<br>
<br>

> # Layanan Sistem Operasi
Layanan sistem operasi dirancang untuk membuat pemrograman menjadi lebih mudah. 
- *Pembuatan Program*: Sistem operasi menyediakan berbagai fasilitas yang membantu programer dalam membuat program seperti editor. Walaupun bukan bagian dari sistem operasi, tapi layanan ini diakses melalui sistem operasi. 
- *Eksekusi Program*: Sistem harus bisa me-load program ke memori, dan menjalankan program tersebut. Program harus bisa menghentikan pengeksekusiannya baik secara normal maupun tidak (ada error). 
- *Operasi Masukan/Keluaran*: Program yang sedang dijalankan kadang kala membutuhkan Masukan/Keluaran. Untuk efisiensi dan keamanan, pengguna biasanya tidak bisa mengatur peranti Masukan/Keluaran secara langsung, untuk itulah sistem operasi harus menyediakan mekanisme dalam melakukan operasi Masukan/Keluaran. 
- *Manipulasi Sistem Berkas*: Program harus membaca dan menulis berkas, dan kadang kala juga harus membuat dan menghapus berkas. 
- *Komunikasi*: Kadang kala sebuah proses memerlukan informasi dari proses yang lain. Ada dua cara umum dimana komunikasi dapat dilakukan. Komunikasi dapat terjadi antara proses dalam satu komputer, atau antara proses yang berada dalam komputer yang berbeda, tetapi dihubungkan oleh jaringan komputer. Komunikasi dapat dilakukan dengan share-memory atau message-passing, dimana sejumlah informasi dipindahkan antara proses oleh sistem operasi. 
- *Deteksi Error*: Sistem operasi harus selalu waspada terhadap kemungkinan error. Error dapat terjadi di CPU dan memori perangkat keras, Masukan/Keluaran, dan di dalam program yang dijalankan pengguna. Untuk setiap jenis error sistem operasi harus bisa mengambil langkah yang tepat untuk mempertahankan jalannya proses komputasi. Misalnya dengan menghentikan jalannya program, mencoba kembali melakukan operasi yang dijalankan, atau melaporkan kesalahan yang terjadi agar pengguna dapat mengambil langkah selanjutnya. 

## Contoh layanan sistem operasi yang ada pada laptop saya adalah:

**1. Windows Exploler**

<img src="img/3.png" style="width:40%">

- Cara membuat folder baru
    - Klik kana pada mouse atau Touchpad
    - Maka akan muncul menu
        - <img src="img/4.png" style="width:40%">
    - Lalu pilih New
    - Lalu pilih folder
        - <img src="img/5.png" style="width:40%">
    - Lalu buat nama foldernya contoh DATA KULIAH
        - <img src="img/6.png" style="width:40%">
        - <img src="img/7.png" style="width:40%">

<br>
<br>

**2. CorelDraw 2020**

<img src="img/8.png" style="width:40%">

- Cara membuat folder baru di COrelDraw 2020
    - Buka aplikasi CoreDraw 2020
    - Maka akan muncul menu
        - <img src="img/9.png" style="width:40%">
    - Lalu pilih New Document
    - Lalu buat nama file misal (belajar)
    - Lalu buat jenis warnanya misal (CMYK)
    - Lalu atur ukuran panjang dan tinggi
    - Lalu pilih satuannya misal (milimeter)
    - Lalu atur resulusinya misal (300 : dpi)
        - <img src="img/10.png" style="width:40%">
    - Selesai 
        - <img src="img/11.png" style="width:40%">

<br>
<br>

**3. Visual Stodio Code**

<img src="img/12.png" style="width:40%">

- Cara membuat folder dan file baru di Visual Stodio Code
    - Buka aplikasi Visual Stodio Code
        - <img src="img/13.png" style="width:40%">
    - Untuk membuat file misal (markdown/md)
        - Pilih ikon kotak file
        - Lalu buat nama file misal (tugas1.md)
        - <img src="img/14.png" style="width:40%">
    - Untuk membuat folder misal (image/img)
        - Pilih ikon kotak folder
        - Lalu buat nama folder misal (img)
        - <img src="img/16.png" style="width:40%">
    - Selesai

<br>
<br>

> # Sistem Call

<p align=justify>Biasanya tersedia sebagai instruksi bahasa assembly. Beberapa sistem mengizinkan system calls dibuat langsung dari program bahasa tingkat tinggi. Beberapa bahasa pemrograman (contoh: C, C++) telah didefenisikan untuk menggantikan bahasa assembly untuk sistem pemrograman. 

Jenis System calls:
- System calls yang berhubungan dengan kontrol proses antara lain ketika penghentian pengeksekusian program. Baik secara normal (end) maupun tidak normal (abort). 
- Selama proses dieksekusi kadang kala diperlukan untuk me-load atau mengeksekusi program lain, disini diperlukan lagi suatu system calls. Juga ketika membuat suatu proses baru dan menghentikan sebuah proses. Ada juga system calls yang dipanggil ketika kita ingin meminta dan merubah atribut dari suatu proses. 
- MS-DOS adalah contoh dari sistem single-tasking. MS-DOS menggunakan metoda yang sederhana dalam menjalankan programan tidak menciptakan proses baru. Program di-load ke dalam memori, kemudian program dijalankan. Berkeley Unix adalah contoh dari sistem multi-tasking. Command Interpereter masih tetap bisa dijalankan ketika program lain dieksekusi.

<br>

**System calls manajemen proses:**

System Call untuk manajemen proses diperlukan untuk mengatur proses-proses yang sedang berjalan. Kita dapat melihat penggunaan system calls untuk manajemen proses pada Sistem Operasi Unix. Contoh yang paling baik untuk melihat bagaimana system call bekerja untuk manajemen proses adalah Fork. Fork adalah satu satunya cara untuk membuat sebuah proses baru pada sistem Unix. Fork membuat duplikasi yang mirip dengan proses aslinya, termasuk file descriptor, register, dan lainnya. 
Setelah perintah Fork, child akan mengeksekusi kode yang berbeda dengan parentnya. Bayangkan yang terjadi pada shell. Shell akan membaca command dari terminal, melakukan fork pada child, menunggu child untuk mengeksekusi command tersebut, dan membaca command lainnya ketika child terminate. 
Untuk menunggu child selesai, parent akan mengeksekusi system call waitpid, yang hanya akan menunggu sampai child selesai. Proses child harus mengeksekusi command yang dimasukkan oleh user(pada kasus shell). Proses child melakukannya dengan menggunakan system call exec. 
Dari ilustrasi tersebut kita dapat mengetahui bagaimana system call dipakai untuk manajemen proses. Kasus lainnya bukan hanya pada Fork, tetapi hampir setiap proses memerlukan system call untuk melakukan manajement proses. 

System calls manajemen berkas:
System calls yang berhubungan dengan berkas sangat diperlukan. Seperti ketika kita ingin membuat atau menghapus suatu berkas. Atau ketika ingin membuka atau menutup suatu berkas yang telah ada, membaca berkas tersebut, dan menulis berkas itu. System calls juga diperlukan ketika kita ingin mengetahui atribut dari suatu berkas atau ketika kita juga ingin merubah atribut tersebut. Yang termasuk atribut berkas adalah nama berkas, jenis berkas, dan lain-lain. 
Ada juga system calls yang menyediakan mekanisme lain yang berhubungan dengan direktori atau sistim berkas secara keseluruhan. Jadi bukan hanya berhubungan dengan satu spesifik berkas. Contohnya membuat atau menghapus suatu direktori, dan lain-lain. 

system calls manajemen piranti:
Program yang sedang dijalankan kadang kala memerlukan tambahan sumber daya. Jika banyak 
pengguna yang menggunakan sistem, maka jika memerlukan tambahan sumber daya maka harus meminta peranti terlebih dahulu. Dan setelah selesai penggunakannnya harus dilepaskan kembali. Ketika sebuah peranti telah diminta dan dialokasikan maka peranti tersebut bisa dibaca, ditulis, atau direposisi. 

## Contoh Sistem Calls yang ada pada laptop saya adalah:

**1. System Call di CMD**

<img src="img/17.png" style="width:40%">

- Cara membuat folder baru
    - ketik mkdir buat nama folder misal (DATA_KULIAH)
    - ketik dir untuk melihat folder baru
        - <img src="img/18.png" style="width:40%">

- Cara membuat folder dalam folder
    - ketik mkdir DATA_KULIAH\ nama folder misal (TUGAS)
    - ketik cd DA
    - lalu tab dan tekan enter
    - maka akan tampil seperti gambar  :
        - <img src="img/19.png" style="width:40%">
    - lalu ketik dir
    - disitu sudah ada folder tugas
        - <img src="img/20.png" style="width:40%">

- Cara membuat file txt
    - ketik copy con nama file misal (Tugas1.txt)
        - <img src="img/19.png" style="width:40%">
    - lalu ketik dir
    - disitu sudah ada file dengan nama Tugas1.txt
        - <img src="img/21.png" style="width:40%">