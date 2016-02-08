# Learning-Compiler

<h2>Design Compiler for New Language.</h2>

<img src="https://scontent-sin1-1.xx.fbcdn.net/hphotos-xpt1/v/t1.0-9/12670259_1715544988659359_5643998370465263483_n.jpg?oh=b092da6311daf6b471dc15df965af92d&oe=5734B4F5"></img>

<p>Sebuah software dengan skala yang besar dan kompleks akan mudah difahami dan diimplementasikan jika kita cermat dalam membangun fondasi untuk setiap 'Abstraction' dan 'Interface' didalamnya. Begitu juga dengan desain sebuah compiler kita perlu membaginya menjadi sebuah tahapan, setiap tahapan mempunyai module tersendiri.</p>

<p>Membagi-bagi tahapan menjadi beberapa bagian membuat kita bisa menggunakan setiap komponen dalam tahapanya untuk digunakan kembali. Sebagai contoh jika compiler yang kita buat ingin memproduksi bahasa mesin untuk target mesin yang berbeda-beda (arsitektur processor i386, AVR, ARM) kita tinggal mengubah Frame Layout.</p>

<p>Jika kita ingin mengubah bahasa pemograman yang kita buat maka kita tinggal mengubah module pada tahap Translate. Jika ingin mengubah paradigma pemograman yang akan kita buat cukup mengubah module Abstract Syntax Interface.</p>

<p>3 Tahap fundamental agar generalisasi desain kompiler baik itu secara fitur dan karakteristiknya bisa disesuaikan sesuai dengan kebutuhan, ditengah perkembangan teknologi processor yang sangat cepat.</p>

2016 The Edensor.
