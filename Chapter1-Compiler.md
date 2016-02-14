<h3>Apa itu Compiler?</h3>
<p>Compiler adalah sebuah penerjemah suatu bahasa pemograman kedalam bahasa lain yang lebih mudah dimengerti oleh mesin kebanyakan adalah
Assembly Code.</p>asdsadsadsadsadsad

<p>Proses Kompilasi itu Sendiri terbagi menjadi beberapa bagian :</p>
<ol>
<li>Lexical Analysis</li>
<li>Syntax Analysis</li>
<li>Intermediate Code Generation</li>
<li>Code Optimization</li>
<li>Code Generation</li>
</ol>

<h4>1. Lexical Analysis</h4>
<p>Sebuah Lexical Analyzer membaca source code untuk menghasilkan sebuah token. Token disebut juga atomic unit, yang direpresentasikan sebagai sebuah sequence (urutan) character. Identifiers, keywords, constants, operators, punctuation symbols adalah contoh token. Dibawah ini adalah sebuah statement dari c code :</p>
<p> return 5;</p>
<p>secara atomic unit pada statement code diatas terdapat 3 token, keyword return, constant 5 dan punctuation semicolon.</p>

<h4>2. Syntax Analysis</h4>
<p>Token yang berasal dari Lexical Analyzer akan menjadi sebuah input pada tahap ini. Sebuah set of rules atau disebut dengan production akan disediakan untuk menganalisa source code sebuah bahasa pemograman. Ini menjelaskan grammar dari bahasa pemograman itu sendiri. Sebuah Syntax Analyzer akan melakukan cek grammar pada setiap baris source code untuk menguji kelayakanya. Dibawah ini adalah contoh set of rules atau production.</p>

<p>Sentence -> Noun Verb</p>
<p>Noun -> Pria, Wanita, Burung</p>
<p>Verb -> Makan, Lari, Terbang</p>

<p>Sebuah parser akan menerima sebuah string sebagai sebuah input dan akan memproduksi parse tree sebagai sebuah output. Ada dua tipe parsing yaitu top-down parsing dan bottom-up parsing. Pada Grammar diatas jika kita memberikan string Burung Terbang sebagai sebuah input</p>
