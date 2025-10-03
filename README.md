1. Deskripsi Program
Program ini merupakan aplikasi sederhana untuk Manajemen Hewan Peliharaan. User dapat menambahkan hewan peliharaan dan menjalankan aksi seperti makan, minum, tidur, dan bersuara. Konsep OOP yang digunakan meliputi Class & Object, Inheritance, Polymorphism, Encapsulation, dan Interface.
2. Struktur Class
Struktur class pada program ini adalah sebagai berikut:
• Interface Aktivitas: mendefinisikan method makan() dan tidur().
• Class abstrak Hewan: memiliki atribut nama, jenis, dan method abstrak bersuara(). Juga mengimplementasikan interface Aktivitas.
• Subclass Kucing, Anjing, dan Burung: masing-masing meng-override method bersuara().
