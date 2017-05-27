# OWL API in Java

Aplikasi sederhana ini akan menunjukkan cara kerja OWL API di Bahasa Pemrograman Java dalam mengelola ontology berbasis OWL.

Fitur:
 1. Akses Ontology di File
 2. Menjalankan SPARQL-DL API
 3. Mengatur SWRL Rule
 4. Menambahkan Class baru, *Belum mendukung penambahan SubClass*
 5. Menambahkan Individu ke dalam suatu Class
 6. Menambahkan Object dan Data Property

Kebutuhan Sistem:
1. Eclipse IDE, *aplikasi ini dikerjakan dengan versi Neon.3 Release (4.6.3)*
2. Kemampuan untuk membuat Maven Project di Eclipse
3. Java SDK sesuai kebutuhan yang ditetapkan oleh Eclipse
4. Jumlah *storage space* dan *memory* yang terpakai menyesuaikan kebutuhan yang ditetapkan oleh Eclipse IDE

**Penggunaan**
1. Import project ke Eclipse
2. Deklarasikan OntologyProcessor di App.java, karena yang di-*run* adalah App.java
3. Eksplorasi ontology dapat dilakukan menggunakan OWL API atau (*cara yang mudah*) menggunakan Protege

>     //deklarasi OntologyProcessor sebagai OP
>     OntologyProcessor OP = new 
>     
>     //tambah class profession
>     OP.addClass("Profession");
>     
>     //menambah individu Fuad di class Person.
>     OP.addIndividuToClass("Person", "Fuad");

**Atribusi:**

> Terima kasih kepada Dr.Techn. Khabib MUSTOFA, S.Si., M.Kom.
> (khabib@ugm.ac.id) dan Mbak Kartika atas bimbingan, serta arahan,
> dalam mempelajari topik ini. Semoga kalian diberkahi atas ilmu dan
> usia yang bermanfaat di dunia dan akhirat.

Terkhusus untuk Mbak Kartika, semoga sukses dan lancar ujian tesisnya... Semangat!!!
