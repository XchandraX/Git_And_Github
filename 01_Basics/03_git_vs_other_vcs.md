# Git dengan sistem kontrol versi tradisional

- Arsitekur Terdistribusi (Git):
    Git adalah sistem yang terdistribusi, artinya setiap developer memiliki salinan lengkap dari seluruh riwayah proyek di komputernya sendiri, bukan sekadar versi yang paling baru.

- Arsitektur Terpusat (VCS Klasik):
    Sistem lama seperti Subversion (SVN) atau CVS bersifat terpusat. Sistem ini sangat bergantung pada satu server utama dan selalu memerlukan koneksi jaringan untuk menyimpan perubahan (commt).

- Kemampuan Bekerja Offline:
    Karena data tersimpan secara lokal, Git memungkinkan Anda untuk melakukan commit, membuat cabag (branching), dan melihat riwayat modifikasi tanpa koneksi internet sama sekali.

- Sinkronisasi Sesuai Kebutuhan:
    Koneksi internet pada Git hanya diperlukan saat Anda ingin menyinkronkan data di komputer lokal dengan server jarak jauh (remote server), yaitu ketika melakukan push (mengirim data) atau pull (mengambil data).