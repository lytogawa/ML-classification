# ML-classification

# LAPORAN PROYEK MACHINE LEARNING - classification

## Domain Proyek

Anggrek merupakan salah satu jenis tanaman hias yang memiliki nilai ekonomi tinggi dan keanekaragaman hayati yang kaya. Indonesia, sebagai negara megadiversitas, memiliki kekayaan spesies anggrek yang melimpah. Namun, eksploitasi berlebihan dan kerusakan habitat alami telah mengancam kelestarian banyak spesies anggrek. Kultur jaringan menjadi salah satu metode penting dalam upaya konservasi dan perbanyakan massal anggrek langka[Gantait et al, 2021].
Metode kultur jaringan konvensional, meskipun efektif, seringkali menghadapi beberapa kendala. Kontaminasi oleh mikroorganisme seperti bakteri dan jamur merupakan masalah umum yang dapat menghambat pertumbuhan dan perkembangan tanaman anggrek[Loyola-Gonzalez et al, 2019]. Selain itu, pertumbuhan tanaman dalam kultur jaringan konvensional relatif lambat,sehingga membutuhkan waktu yang lama untuk menghasilkan bibit yang siap tanam. Biaya produksi yang tinggi juga menjadi kendala dalam penerapan kultur jaringan secara luas, terutama bagi petani kecil.
Sistem perendaman sementara (Temporary Immersion System/TIS) bioreaktor menawarkan solusi inovatif untuk mengatasi kendala-kendala tersebut. TIS bioreaktor adalah sistem kultur jaringan di mana tanaman secara berkala terendam dalam larutan nutrisi dan kemudian dikeringkan. Perendaman sementara merangsang pertumbuhan akar dan tunas yang lebih cepat dan sehat, sementara sistem tertutup mengurangi risiko kontaminasi. Selain itu, penggunaan TIS bioreaktor dapat menghemat penggunaan air dan nutrisi, sehingga lebih efisien dan ramah lingkungan.
Machine learning (ML) juga memiliki potensi besar untuk meningkatkan efisiensi dan efektivitas kultur jaringan anggrek dengan TIS bioreaktor. ML dapat digunakan untuk menganalisis data dari sensor yang memantau kondisi lingkungan dan pertumbuhan tanaman. Dengan menganalisis data ini, algoritma ML dapat memprediksi pertumbuhan tanaman,mendeteksi dini kontaminasi, dan mengoptimalkan parameter kultur seperti suhu, pH, dan konsentrasi nutrisi. Selain itu,ML dapat digunakan untuk mengontrol proses bioreaktor secara otomatis, sehingga mengurangi kebutuhan tenaga kerja dan meningkatkan konsistensi hasil.
Dengan menggunakan ML yang diintegrasikan dengan metode TIS dapat dilakukan klasifikasi adanya kebocoran lingkungan TIS sebagai langkah awal pemberitahuan untuk melakukan tindak lanjut agar tidak ada kontaminan yang masuk ke dalam lingkungan TIS. Karena kontaminan adalah variabel yang wajib tidak boleh ada di dalam lingkungan TIS.

## Business Understanding

Petani anggrek menghadapi tantangan untuk pengembangbiakan anggrek dengan metode yang efektif dan efisien. Menggunakan metode media semi solid sudah banyak dilakukan secara massal tapi masih terkendala dengan biaya yang masih tinggi, rendahnya tingkat multiplikasi, serta masalah fisiologis seperti hyperhydricity dan asphyxia. Dengan metode TIS, masalah tersebut dapat teratasi namun juga masih perlu banyak perbaikan seperti peningkatan automasi. Dan juga masalah investasi pada infrastruktur TIS itu sendiri.

### Problem Statements
- Petani anggrek tidak memiliki pengetahuan teknis tentang integrasi IoT yang menggunakan beberapa sensor untuk pengambilan data agar dapat diolah dan mampu meningkatkan efektifitas dan efisiensi pengambangan anggrek dengan menggunakan machine learning.
- Bagaimana cara mengklasifikasikan adanya kebocoran sebagai salah satu indikasi kegagalan metode TIS dalam pengembangan anggrek berdasarkan dari data yang dikumpulkan dari beberapa sensor, sehingga dapat melakukan tindak lanjut untuk mengurangi waktu dan biaya pada awal pengembangan bibit anggrek.

### Goals

Tujuan utama dari proyek ini adalah membantu para petani anggrek untuk mengembangkan sistem yang dapat mengklasifikasikan adanya kebocoran lingkungan pada TIS agar dapat melakukan beberapa tindakan.
- Membuat keputusan untuk segera melakukan perbaikan atau penggantian wadah lingkungan TIS untuk anggrek berkembang.
- Dapat membangun dataset yang dapat digunkan untuk berbagai kebutuhan terkait pengembangan anggrek secara TIS, khususnya dalam kasus ini untuk klasifikasi adanya kebocoran pada lingkungan TIS.

## Data Understanding

Dalam tahapan Data Understanding, pengumpulan dataset yang diambil dengan crawling data secara mandiri dengan menggunakan sensor yang terintegraasi dengan IoT dan mengolahnya yang kemudian dapat digunakan untuk klasifikasi adanya kebocoran lingkungan TIS. Tahap pertama adalah memuat data train dan test ke dalam lingkungan pemrograman untuk dianalisis lebih lanjut. 
