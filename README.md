NotesApp adalah Pada  aplikasi Notes untuk mencatat agenda yang sederhana. Untuk media penyimpanan, kita gunakan SQLite. aplikasi ini mencakup beberapa hal yaitu:

Kelas helper apa saja yang perlu dipersiapkan untuk menggunakan SQLite?


	Bagaimana proses CRUD (Create Read Update Delete) di dalam SQLite
	Mengembangkan Aplikasi Catatan Sederhana dengan menggunakan SQLite


#informasi


Android menyediakan salah satu mekanisme penyimpanan data berulang yang dapat tersimpan secara terstruktur dan berelasi dengan menggunakan SQLite.

SQLite merupakan database yang bersifat open source yang mendukung operasi relasi standar yang umum terdapat pada engine database seperti sintaks SQL dan operasi transaksi. Meskipun berjalan seperti database, pada umumnya sqlite berukuran kecil dan mampu berjalan pada peranti dengan memori terbatas seperti smartphone.

SQLite ini dipakai oleh aplikasi-aplikasi native dengan penyimpanan data yang tidak bersifat kompleks seperti Google Chrome dan Firefox. Contohnya adalah untuk menyimpan data bookmark website yang dilakukan oleh pengguna dan juga aplikasi mobile seperti aplikasi contact bawaan OS Android yang menggunakannya sebagai penyimpanan data lokal yang mendukung proses sinkronisasi ke server.

SQLite hanya mendukung beberapa tipe data seperti text untuk penyimpanan data dalam bentuk string, int untuk menyimpan data dalam bentuk bilang bulat, real untuk penyimpan data dalam bentuk bilangan pecahan/bilangan presisi. Jadi apabila ingin menyimpan data yang tidak didukung oleh SQLite maka diharuskan dilakukan proses konversi tipe data yang sesuai dengan tipe data yang didukung sebelum melakukan penyimpanan data.
