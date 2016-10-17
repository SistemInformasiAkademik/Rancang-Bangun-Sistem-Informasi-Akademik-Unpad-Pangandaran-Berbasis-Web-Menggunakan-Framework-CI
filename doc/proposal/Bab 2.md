<h3 align="center">BAB II 
LANDASAN TEORI</h3>
<br>
<b>2.1	Pengertian Sistem Perancangan</b>
<p align="justify">
Perancangan sistem adalah penentuan proses dan data yang iperlukan oleh sistem baru, sistem itu berbasis computer, perancangn apat inyatakan spesifikasi peralatan yang digunakan</p>
<b>2.2	Pengertian Sistem Informasi</b>
<p align="justify">
Sistem informasi adalah suatu sistem didalam suatu organisasi yang mempertemukan kebutuhan pengelolaan transaksi, mendukung operasi, bersifat manajerial dan kegiatan strategi dari suatu organisasi dan menyediakan pihak luar tertentu dengan laporan-laporan yang dibutuhkan.
</p>
<b>2.3	Pengertian Akademik</b>
<p align="justify">
Sistem informasi Akademik adalah Sistem yang menberikan layanan informasi yang berupa data dalam hal yang berhubungan dengan akademi. Dimana dalam hal ini pelayanan yang diberikan yaitu seperti : penyimpanan data untuk baru, penetuan kelas, penentuan jadwal pelajaran, pembuatan jadwal mengajar, pembagian wali kelas, proses penilaian.</p>
<b>
2.4	Pengertian Codeigniter</b>
<p align="justify">
Codeigniter adalah suatu framework yang telah dilengkapi dengan fasilitas yang memudahkan penggunanya untuk membuat aplikasi website. Misalnya saja dengan adanya fasilitas error reporting. Tetapi, fasilitas error reporting. Tetapi fasilitas ini juga dapat digunakan hacker untuk mengetahui kelemaham website kita pula, sehingga dengan berbekal kelemahan tersebut, system website kita dapat ditembus.
CodeIigniter dibangun berbasis MVC yaitu (Models, View, Controller) yang memisahkan antara tampilan dan logic aplikasi. Models ¬adalah bagian yang betanggungjawab terhadap operasi database baik itu create, read, upadate dan delete berupa fungsi-fungsi operasional database yang dipanggil oleh controller. View adalah bagian menangani tampilan, bagian  inilah yang bertugas unutk mempresentasikan data kepada user berbentuk struktur HTML yang berisikan variable data yang dikirim oleh controller. Controller adalah bagian yang mengatur hubungan anatar model dan view. Terdiri dari fungsi-fungsi yang bersifat operasional logikal.
<img src="https://github.com/SistemInformasiAkademik/Rancang-Bangun-Sistem-Informasi-Akademik-Unpad-Pangandaran-Berbasis-Web-Menggunakan-Framework-CI/blob/master/img/CI.PNG" width="500" height="300">
</p>
<b>
2.5	Pengertian Bootstrap<br>
<p align="justify">
CCS Bootstrap merupakan framework front-end yang menggunakan HTML, CSS dan JavaScript yang dapat membuat aplikasi web yang responsive dan dapat digunakan pada lingkup perangkat mobile dapat membuat layout halaman website, table, tombol, form, naviasi dan komponen lainnya dalam sebuah website.
</p>
<b>2.6 Pengertian MySQL</b>
<p align="justify">
MySql merupakan software yang tergolong database server dan bersifat opensource. Open Source menyatakan bahwa software ini dilengkapi dengan source code (kode yang dipakai untuk membuat MySQL) yang dapat dijalankan secara langsung dalam system operasi. MySQL bersifat multiplatform yaitu dapat dijalankan pada berbagai system operasi. Pengaksesan database dapat dilakukan dengan mudah melalui SQL (Structured Query Language). Data dalam database dapat diakses melalui aplikasi non web maupun aplikasi web misalnya PHP.
</p>
<b>2.7	Pengertian UML</b>
<p align="justify">
<img src="https://github.com/SistemInformasiAkademik/Rancang-Bangun-Sistem-Informasi-Akademik-Unpad-Pangandaran-Berbasis-Web-Menggunakan-Framework-CI/blob/master/img/STAR%20UML.PNG" width="500" height="300">
Secara umum UML merupaka ‘bahasa’ untuk visualisasi, spesifikasi, konstruksi, serta dokumentasi. Dalam kerangka visualisasi, para pengembang menggunakan UML sebagai suatu cara untuk mengkomunikasikan idenya kepada para pemrogram serta calon pengguna sistem/ perangkat lunak.
Dalam keangka spesifikasi, UML menyediakan model- model yang tepat, tidak mendua-arti (ambigu), serta lengkap. Secara khusus, UML menspesifikasi langkah- langkah penting dalam pengambilan keputusan analisis, perancangan, serta implementasi dalam sistem yang sangat bernuansa perangkat lunak. Dalam hal ini UML bukanlah merupakan bahasa pemrograman tetapi model- model yang tercipta berhubungan langsung dengan berbagai macam bahasa pemrograman berorientasi objek, seperti Java, Delphi, C++, Visual Basic, dan lain- lain. UML mendefinisikan diagram-diagram sebagai berikut :
<b> 2.7.1	Use Case Diagram </b>
Use case diagram menggambarkan fungsionalitas yang diharapkan dari sebuah sistem. Yang ditekankan adalah “apa” yang diperbuat sistem, dan bukan “bagaimana”. Sebuah use case merepresentasikan sebuah interaksi antara aktor dengan system.
<b> 2.7.2	Class Diagram </b> 
Class adalah sebuah spesifikasi yang jika diinstansiasi akan menghasilkan sebuah objek dan merupakan inti dari pengembangan dan desain berorientasi objek. Class menggambarkan keadaan (atribut/properti) suatu sistem, sekaligus menawarkan layanan untuk memanipulasi keadaan tersebut (metoda/fungsi).
<b> 2.7.3	Sequence Diagram </b>
Menggambarkan  kolaborasi dinamis antara sejumlah  object. Kegunaanya untuk menunjukkan rangkaian pesan yang dikirim antara  object juga interaksi antara  object, sesuatu yang terjadi pada titik tertentu dalam eksekusi sistem.
<b> 2.7.4	Statechart Diagram </b>
Statechart diagram menggambarkan transisi dan perubahan keadaan (dari satu state ke state lainnya) suatu objek pada sistem sebagai akibat dari stimuli yang diterima. Pada umumnya statechart diagram menggambarkan class tertentu (satu class dapat memiliki lebih dari satu statechart diagram). 
<b> 2.7.5	Collaboration Diagram </b>
Collaboration diagram juga menggambarkan interaksi antar objek seperti sequence diagram, tetapi lebih menekankan pada peran masing-masing objek dan bukan pada waktu penyampaian message.  Setiap message memiliki sequence number, di mana message dari level tertinggi memiliki nomor 1. Messages dari level yang sama memiliki prefiks yang sama.
<b> 2.7.6	Activity Diagram </b> 
Activity diagram merupakan state diagram khusus, di mana sebagian besar state adalah action dan sebagian besar transisi di-trigger oleh selesainya state sebelumnya (internal processing). Oleh karena itu activity diagram tidak menggambarkan behaviour internal sebuah sistem (dan interaksi antar subsistem) secara eksak, tetapi lebih menggambarkan proses-proses dan jalur-jalur aktivitas dari level atas secara umum.
<b> 2.7.7	Component Diagram </b>
Component diagram menggambarkan struktur dan hubungan antar komponen piranti lunak, termasuk ketergantungan (dependency) di antaranya.  
<b> 2.7.8	Deployment diagram. </b>
Deployment/physical diagram menggambarkan detail bagaimana komponen di-deploy dalam infrastruktur sistem, di mana komponen akan terletak (pada mesin, server atau piranti keras apa), bagaimana kemampuan jaringan pada lokasi tersebut, spesifikasi server, dan hal-hal lain yang bersifat fisikal.
</p>
<b>
2.8	Sublime Texs 3</b>
<br>
<img src="https://github.com/SistemInformasiAkademik/Rancang-Bangun-Sistem-Informasi-Akademik-Unpad-Pangandaran-Berbasis-Web-Menggunakan-Framework-CI/blob/master/img/sublime.PNG" width="500" height="300">
<p align="justify">
Sublime Text adalah teks editor berbasis Python, sebuah teks editor yang elegan, kaya akan fitur, cross-platform, mudah dan simpel yang cukup terkenal di kalangan pengembang, penulis, dan desainer. Para programmer biasanya menggunakan sublime Text untuk menyunting source code yang sedang ia kerjakan. Sampai saat ini Sublime Text sudah mencapai pada versi 3 Beta. [ Yusti, 2015]
Berikut ini adalah beberapa kelebihan yang di milki Sublime Text:
1.	Multi Platform
Kelebihan pertama dari Sublime Text adalah software ini tersedia dalam berbagai platform sistem operasi, antara lain Windows, Linux dan MacOs. 
2.	Membuka File Besar
Sublime Text mampu membuka dan mengedit sebuah file teks yang sangat besar tanpa masalah.
3.	Drag & Drop
Menyeret dan melepas file teks ke dalam editor akan membuka tab baru secara otomatis. Anda juga bisa menentukan lokasi tab pada saat menyeret file teks tersebut. 
4.	Editor Sublime Text yang terpisah bisa di jadikan sebagai tab 
Editor Sublime Text pada jendela terpisah bisa jadikan sebagai tab baru dengan cara di seret. Tampilan jendela dapat dibagi baik secara vertikal maupun horizontal.
</p>
<b>
2.9	Software yang digunakan<br>
<p align="justify">
Sublime Text adalah teks editor berbasis Python, sebuah teks editor yang elegan, kaya akan fitur, cross-platform, mudah dan simpel yang cukup terkenal di kalangan pengembang, penulis, dan desainer. Para programmer biasanya menggunakan sublime Text untuk menyunting source code yang sedang ia kerjakan. Sampai saat ini Sublime Text sudah mencapai pada versi 3 Beta. [ Yusti, 2015]
<br>
Berikut ini adalah beberapa kelebihan yang di milki Sublime Text:<br>
1.	Multi Platform<br>
Kelebihan pertama dari Sublime Text adalah software ini tersedia dalam berbagai platform sistem operasi, antara lain Windows, Linux dan MacOs. <br>
2.	Membuka File Besar<br>
Sublime Text mampu membuka dan mengedit sebuah file teks yang sangat besar tanpa masalah.<br>
3.	Drag & Drop<br>
Menyeret dan melepas file teks ke dalam editor akan membuka tab baru secara otomatis. Anda juga bisa menentukan lokasi tab pada saat menyeret file teks tersebut. <br>
4.	Editor Sublime Text yang terpisah bisa di jadikan sebagai tab <br>
Editor Sublime Text pada jendela terpisah bisa jadikan sebagai tab baru dengan cara di seret. Tampilan jendela dapat dibagi baik secara vertikal maupun horizontal. 
</p>