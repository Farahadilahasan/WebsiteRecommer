<b>Spesifikasi Kebutuhan Sistem</b>
Untuk
Website Recommer
Version 1.0 

Disusun Oleh :

FARAH ADILAH HASAN 		     22091397092 MIC

M. ADHIEL VINCO AUKY	        22091397089 MIC

D4 Manajemen Informatika
Fakultas Vokasi
Universitas Negeri Surabaya
2023

<b>A. Deskripsi Produk</b>

Website Recommer merupakan sebuah website yang memberikan pelayanan kepada pengguna dalam bentuk rekomendasi kebutuhan wisata yang sangat lengkap. mulai dari rekomendasi objek wisata yang ingin wisatawan kunjungi, hotel, restoran bahkan travel atau transportasi yang akan di gunakan saat berwisata. selain memberikan beberapa rekomendasi, website ini juga membantu pelayanan booking/reservasi sesuai jadwal yang dinginkan oleh wisatawan. disisi lain juga wisatawan bisa memberikan ulasan dalam bentuk komentar ataupun rating terkait apa yang telah direkomendasikan oleh Website Recommer ini sendiri. website Recommer ini nantinya akan di design dengan tampilan semenarik mungkin dan yang terpenting user friendly. karna sebelum kita memberikan pengalaman layanan kebutuhan wisata kepada pengguna, sebaiknya kita memberikan pengalaman penggunaan website yang mudah dan gampang untuk dimengerti terlebih dahulu kepada pengguna.

<b>B. Tujuan</b>
   
Pembuatan website Recommer ini memiliki beberapa tujuan. Tujuan biasanya muncul dari proses visi, atau rencana yang akan membantu dalam meraih sesuatu yang diinginkan, diantaranya :

1. Memudahkan pengguna untuk mencari reservasi wisata, pencarian reservasi kamar hotel, dan restoran. <br>
2. Memudahkan pengguna untuk memesan akomodasi hotel, wisata, dan restoran di berbagai wilayah. <br>
3. Memberikan tawaran harga dan paket liburan yang menarik untuk para pengguna/traveler/wisatawan. Yang mana dalam paket liburan tersebut mencangkup wisata, hotel, dan makan di restoran.
    
<b>C. Audiensi yang Dituju</b>

Dokumen ini ditujukan untuk pengembang web, pengguna, penguji dan penulis dokumentasi hingga staf pemasaran dan lain sebagainya. SRS ini dibagi menjadi beberapa bagian, antara lain yaitu:
1. Pengembang web yang ingin mencari referensi mengenai web rekomendasi. <br>
2. Membantu menambah literatur dalam bidang web development. <br>
3. Menambah wawasan, informasi, serta petunjuk mengenai sistem web reservasi. <br>
4. Memberi petunjuk mengenai target pasar. <br>
5. Dokumen pengajuan. <br>


<b>E. Penjelasan Codingan HTML Dan CSS yang digunakan</b> 

<b>PENJELASAN CODINGAN PROJECT.HTML</b> 

![1 html](https://github.com/Farahadilahasan/WebsiteRecommer/assets/124495764/c0295936-97f6-4b9b-82fe-2f28241733d8)

Diawal kodingan terdapat keterangan DOCTYPE yang mengindikasikan bahwa halaman ini adalah dokumen HTML. Selanjutnya terdapat tag <head> yang berguna untuk menampung informasi tentang halaman web tersebut, seperti metadata dan referensi ke berkas-berkas eksternal seperti CSS. Semua elemen yang berada dalam head tidak akan ditampilkan pada halaman itu sendiri tetapi digunakan untuk mengkonfigurasi penyediaan informasi kepada browser. Agar tampilan halaman website ini bisa terkontrol pada perangkat yang digunakan maka kita perlu menggunakan meta tag viewport. selanjutnya kita membuat tag link yang digunakan untuk menghubungkan halaman HTML dengan file CSS eksternal yang berfungsi untuk mengatur tampilan dan gaya halaman web. Terakhir yang terdapat pada head terdapat title yang berguna untuk menentukan judul halaman web yang akan di tampilkan di tab browser  

<b>NAVIGASI BAR</b>

![2](https://github.com/Farahadilahasan/WebsiteRecommer/assets/124495764/e5f49cc4-9d9b-4d01-9223-0e7562a1a0c5)

Dibagian ini  kita akan fokus kepada pembuatan navigasi bar pada website. Kita awali dengan elemen nav sebagai tanda navigasi dari halaman website. Selanjutnya kita perlu membuat div class=”wrapper” yang menjadi wadah/container dengan kelas CSS “wrapper” yang berguna untuk mengelompokkkan elemen – elemen yang terdapat dalam navigasi. Dalam navigasi ini nantinya kita iingin mencantumkan logo/judul dari website yang kita buat dengan menggunakan div class=”logo karna desain yang kita inginkan dari logo tersebut berbeda dengan desain menu yang kita buat sehingga kita perlu membuat div class yang berbeda. Menu yang akan kita buat akan di kelompokkan melalui div class=”menu” yang berisi daftar menu navigasi. Didalam div class menu terdapat elemen ul sebagai daftar tak terurut yang berisi tautan menu yang akan membawa user kepada halaman yang dituju melalui daftar menu tersebut. Dalam elemen ul terdapat elemen li yang menandakan satu item menu. Dalam setiap li terdapat a href=”#Item menu” Item Menu /a yang berfungsi sebgai tautan menu yang mengarahkan pengguna ke berbagai bagian halaman web yang menggunakan tanda “#” dan diikuti oleh Id dari masing – masing bagian yang bersangkutan. 

<b>MENU HOME</b>
![3](https://github.com/Farahadilahasan/WebsiteRecommer/assets/124495764/904db385-75b0-4e93-a1e8-b643d1f00841)

Pada bagian ini kita akan memulai untuk membangun isi konten menu HOME. Pada bagian ini kita menggunakan div class=”wrapper” untuk mengelompokkkan elemen-elemen dalam menu HOME pada halaman web. Selanjutnya terdapat elemen section yang memiliki atribut id “home” yang berguna untuk mengelompokkan dan mengidentifikasi bagian “HOME” dari halaman website. Di bagian home ini kita memberi sebuah gambar menggunakan elemen img srs=”” yang mana gambar tersebut merujuk pada file image yang telah di simpan ke dalam folder asset yang menyimpan semua gambar yang digunakan untuk project website ini sendiri. Pada bagian konten tulisan kita membuat div class=”kolom” sebagai wadah kelas CSS yang berisikan teks. Berikut ini konten tulisan yang terdapat pada bagian home 

•	Konten tulisan ini akan kita bentuk menjadi sebuah peragraf sehingga kita perlu membuat kelas CSS untuk paragraf tersebut yang kita beri nama “deskripsi”.   <br>
•	Dibaris kedua kita membuat elemen h2 sebagai judul dibagian HOME  <br>
•	Dibaris ketiga kita kembali menggunakan elemen p yang berguna sebagai teks deskripsi tambahan <br>
•	Dibagian terakhir pada isi konten home terdapat paragraf yang berisi tautan yang tersembunyi dalam teks “cari tahu lebih lanjut” yang mana ketika user mengklik tautan tersebut maka website akan mengalihkan ke halaman yang dituju dari tautan itu sendiri. Dalam pargraf ini juga terdapat kelas CSS “tbl-biru” yang memberikan bentuk tabel berwarna biru pada teks tersebut 

<b>MENU ABOUT ME</b>
![4](https://github.com/Farahadilahasan/WebsiteRecommer/assets/124495764/f524b3fc-bcea-4831-91c5-a6a5a4466f39)

Seperti penjelasan sebelumnya, pada bagian section, div class=”kolom dan juga p class=”deskripsi” memiliki fungsi yang sama seperti sebelumnya, hanya saja dibagian atribut id pada section kita perlu menyesuaikan dengan konten menu selanjutnya yang akan kita buat. Terkait kebutuhan elemen untuk isi konten dalam menu ABOUT ME ini juga tidak berbeda dengan menu sebelumnya (HOME).

<b>MENU RECOMMENDATION</b>
![5](https://github.com/Farahadilahasan/WebsiteRecommer/assets/124495764/b78fc9db-8ea8-44a8-931f-8368ed27b545)

Di bagian ini kita akan membuat isi konten dari menu recommendation. Di awal bagian masih terdapat beberapa elemen yang sama seperti  menu menu sebelumnya seperti elemen section,  dan div class lainnya. Tetapi terdapat 1 div class tambahan yang tidak terdapat pada pada menu sebelumnya yakni div class=”tengah” yang  berguna untuk  mengatur elemen – elemen yang terdapat di bagian menuini supaya tampilannya bisa ke tengah halaman.

![6](https://github.com/Farahadilahasan/WebsiteRecommer/assets/124495764/005e04fb-cca8-4794-92ba-4eafdfd796be)

Bagian ini menjadi isi konten utama dalam halaman RECOMMENDATION. Dibawah judul dan teks yang sudah dibuat sebelumnya, disini kita membuat div class=”Recommendation-list yang berisi daftar kategori rekomendasi. Setiap rekomendasi ini nantinya akan ditempatkan dalam divclass=”kartu-Recommendation” yang berisi gambar. Di bawah setiap gambar terdapat sebuah teks dengan kelas CSS yang akan mendefinisikan rekomendasi tersebut (Penginapan, Wisata, Transportasi, Kuliner)

<b>MENU FIND US</b>
![7](https://github.com/Farahadilahasan/WebsiteRecommer/assets/124495764/14e812fd-60ff-415a-ab29-12bc4b7394cf)

![8](https://github.com/Farahadilahasan/WebsiteRecommer/assets/124495764/3b07ddc4-a2e3-4f16-8774-51e2bf8caec4)

Di bagian ini kita akan membuat isi konten dari menu FindUS. Semua kebutuhan elemen yang terdapat pada menu ini sama persis dengan elemen-elemen yang digunakan pada menu RECOMMENDATION. Hanya saja pada bagian menu ini gambar yang kita cantumkan berformat URL beberapa gambar yang kita salin dari situs website lain. Pada bagian div class “kartu-FidnUs” juga terdapat 1 perbedaan dari menu sebelumnya yang mana kita tidak memberikan elemen p sebagai penjelasan berupa teks. Karna dibagian ini berisi media sosial yang tentunya semua orang tau aplikasi – aplikasi yang biasa digunakan sebagai sarana publikasi jadi kami rasa tidak perlu lagi di berikan sebuah keterangan/teks yang mendefiniskan gambar tersebut

<b> MENU CONTACT</b> 
![9](https://github.com/Farahadilahasan/WebsiteRecommer/assets/124495764/aa3f275e-28b0-48b0-b9f3-ed01bc404105)

Pada bagian kita akan membuat isi konten dari menu CONTACT. Di awal kita menggunakan div id=”contact” untuk mengelompokkan dan menampilkan indormasi kontak dan media sosial di bagian bawah/footer. Selanjutnya di setiap kelompok informasi seputar kontak akan di wadahi oleh div class “footer-section” yang akan mengatur tatanan tampilan melalui CSS. Pada setiap kelompok informasi kontak terdapat beberapa elemen seperti h3 yang berguna sebagai judul dari sebuah kelompok informasi, kemudian elemen p yang berguna untuk memberikan deskripsi singkat dari judul yang tertera

![10](https://github.com/Farahadilahasan/WebsiteRecommer/assets/124495764/0366bdf7-85fa-44fa-ad19-3358809bbf77)

Di bagian paling bawah dari halaman utama terdapat elemen div id=”copyright” yang bergun auntuk menampilkan hak cipta. Dalam elemen div tersebut terdapat elemen b yang berguna untuk menge – boald tulisan yang dinginkan 

 <b>PENJELASAN CSS DARI PROJECT.HTML</b>

![1CSS](https://github.com/Farahadilahasan/WebsiteRecommer/assets/124495764/2a200e62-7973-4ec4-96c6-bf2499941d7d)

Tanda bintang pada bagian awal dokumen CSS ini terdapat tanda bintang. Aturan ini berguna untuk mengatur beberapa hal dasar pada tampilan elemen di halaman web 

•	Text-decoration:none kita gunakan untuk menghapus atau menghilangkan dekorasi pada semua tautan di halaman web (seperti underline) <br>
•	Margin kita buat 0 px untuk menghapus margin bawaan yang ada disekitar elemen-elemen  <br>
•	padding: 0px berguna untuk menghapus padding bawaan yang ada disekitar elemen-elemen  <br>

![2CSS](https://github.com/Farahadilahasan/WebsiteRecommer/assets/124495764/e82ef973-c1f2-4bf7-be23-4cb5f8c62862)
Bagian ini berlaku untuk elemen <body> dalam dokumen HTML 

•	Margin 0 px berguna untuk menghapus margin bawaan pada elemen body <br>
•	Padding 0 px berguna untuk menghapus padding bawaan pada elemen body <br>
•	Font-family berguna untuk mengatur jeni font text dalam elemen body  <br>

![3CSS](https://github.com/Farahadilahasan/WebsiteRecommer/assets/124495764/945023bf-2cb9-4609-b8c2-79a21e2c70db)

Css pada bagian ini menaggambarkan aturan gaya yang akan di terapkan pada elemen dalam kelas “wrapper”  <br>
•	Wdht : berguna untuk mengatur lebar elemen kelas wrapper sesuai dengan besar nya pixel yang ditentukan (1100) <br>
•	Margin : pada bagian margin ini kita setting menjadi auto, yang mana bagian atas dan bawah serta margin samping dari elemen tersebut akan berada di tengah horizontal dari parent elemennya (body)

![4CSS](https://github.com/Farahadilahasan/WebsiteRecommer/assets/124495764/1f454121-8629-4a7f-89d6-71fabc71728b)

Pada bagian ini merupakan css yang mengatur styling pada kelas “logo” yang juga merupakan tautan (a) yang berisi sebuah text sebagai logo <br>
•	Font size : untuk mengatur besar kecilnya ukuran font yang digunakan  <br>
•	Font weight : untuk mengatur ketebalan font text (bold) <br>
•	“Float : left” : berguna untuk mengatur elemen pada class tersebut menjadi berada di kiri <br>
•	Font-family: courier” : untuk mengatur jenis font teks  <br>
•	Color : mengatur warna teks sesuai dengan apa yang diinginkan, pada bagian desain yang mengatur tampilan logo ini kami memberikan warna putih dengan kode #FFFFFF <br>

![5CSS](https://github.com/Farahadilahasan/WebsiteRecommer/assets/124495764/d73608cc-51aa-41f2-8317-c13d0b7ca7a4)

Pada aturan menu di bagain css ini hanya terdapat “float: right” yang akan mengatur tampilan class menu untuk berada di kanan  

![6CSS](https://github.com/Farahadilahasan/WebsiteRecommer/assets/124495764/d016e977-7acd-40db-a713-4ef05432a2eb)

Aturan css yang digunakan untuk nav <br>
•	Wdth : mengatur lebar elemen nav menjadi 100% dari lebar parent-nya<br>
•	Margin auto : mengatur agar margin di bagian atas bawah dan samping elemen menjadi di sisi tengah halaman secara horizontal<br> 
•	Display flex : berguna untuk mengatur elemen nav menggunakan tata letak flexbox yang memungkinkan untuk penataan elemen-elemen dalam kontainer dengan tata letak yang fleksibel dan mudah dikontrol <br>
•	Line height : berguna untuk mengatur tinggi baris teks dalam elemen nav. Hal ini akan mempengaruhi jarak antara barisan teks dalam elemen tersebut.<br>
•	Position sticky : berguna untuk mengatur posisi elemen nav menjadi “sticky” yang berarti elemen nav ini nantinya akan tetap terlihat di layar kita saat menggulir halaman website <br>
•	Top 0 : untuk mengatur elemen nav agar tetap berada di atas halaman, ini hanya berlaku jika elemen tersebut juga menjadi “sticky” <br>
•	Background colour : mengatur warna latar belakang elemen nav menjadi biru tua dengan kode warna (#364f6b) <br>
•	Z-index 1 : berguna untuk mengatur indeks tumpukan elemen (z-index) untuk elemen nav. Ini berguna ketika ada elemen lain yang tumpang tindih dengan elemen nav <br>
•	Border bottom : mengatur garis bawah dengan ketebalan 5 pixel  dan warna biru terang pada bagian tepi bawah elemen nav, hal ini juga berguna sebagai garis pemisah antara elemen nav dengan konten dibawahnya <br>

![7CSS](https://github.com/Farahadilahasan/WebsiteRecommer/assets/124495764/5e166a40-82a2-4932-99a1-815c75bcc565)

Dalam bagian ini terdaapat beberapa aturan untuk nav yang semakin ke bawah semakin terspesifikkan 

Aturan css untuk nav ul : <br>
•	List style type none : berguna untuk menghilangkan tanda bullet atau angka yang biasanya muncul setiap kali sebelum item undored list. Dengan settingan ini item pada unordered list dalam elemen <nav> tidak akan memiliki tanda atau angka sebelumnya

Aturan css untuk nav ul li :<br>
•	Float left : berguna untuk mengatur elemen-elemen unordered list dalam elemen <nav> berada di tampilan sebelah kiri halaman 

Aturan css untuk nav ul li a :<br>
•	Color : mengatur warna teks dalam tautan (link href) yang ada dalam elemen unordered list. <br>
•	Font weight bold : mengatur ketebalan font <br>
•	Text align center : mengatur teks dalam tautan untuk di align (alirkan) secara horizontal ke tengah. <br>
•	Padding : berguna untuk mengatur ruang di sekitar teks dalam tautan, dalam hal ini padding di atur untuk menyisipkan 16 pixel ruang di atas dan bawah, dan 16 pixel ruang dikiri dan kanan setiap tautan <br>
•	Text decoration none : menghilangkan dekorasi tautan default, seperti garis bawah (underline)

Aturan untuk CSS nav ul li a:hover <br>
Ini adalah aturan yang berlaku ketika user mengarahkan kursor ke tautan (link) dalam menu navigasi maka elemen berikut akan di terapkan :<br>
Text decoration : underline : elemen ini akan menambahkan garis bawah pada tautan saat di klik

![8CSS](https://github.com/Farahadilahasan/WebsiteRecommer/assets/124495764/4ff3cc60-ff80-4e80-9185-f3d418574528)

Bagian ini akan mengatur tampilan elemen – elemen yang terdapat pada section <br>
•	Margin auto : mengatur elemen agar berada di tengah secara horizontal <br>
•	Display flex : kit amenggunakan model tata letak flexbox untuk elemen yang berada pada section yang memungkinkan penataan elemen secara flexible <br>
•	Margin bottom : menambahkan margin bawah sebesar 50 px pada elemen section 

![9CSS](https://github.com/Farahadilahasan/WebsiteRecommer/assets/124495764/7df16ac8-d67d-42a0-b66f-a2abbfb92fff)

Aturan css yang berlaku untuk elemen dengan class “kolom” <br>
•	Margin top : berguna untuk menambahkan margin sebesar 50px yang memberikan ruang atas antara elemen kolom dengan elemen lainnya <br>
•	Margin bottom : berguna untuk memberikan margin bawah sebesar 50 piksel untuk memberikan ruang bawah antara elemen kolom dengan elemen lainnya 

![10CSS](https://github.com/Farahadilahasan/WebsiteRecommer/assets/124495764/839b92ac-e248-480e-992f-2dc8e6e79080)

Bagian ini merupakan aturan css yang berlaku untuk elemen dengan class “deskripsi” yang berada dalam elemen dengan class “kolom”<br>
•	Font-size : mengatur ukuran font text untuk elemen deskripsi <br>
•	Font-weight: bold : mengatur ketebalan font text menjadi tebal <br>
•	Font-family : Mengatur jenis font teks <br>
•	Color : mengatur warna teks yang berada di class deskripsi menjadi warna biru tua dengan kode warna tersebut 

![11CSS](https://github.com/Farahadilahasan/WebsiteRecommer/assets/124495764/15caddc3-9bcc-4324-8a77-bcc642cabf8f)

bagian ini adalah aturan css yang berlaku untuk elemen h2 <br>
•	font-family : mengatur jenis font teks untuk elemen h2 menggunakan ‘comic sans ms’<br>
•	font-size : mengatur ukuran teks menjadi 45 pixel <br>
•	color : mengatur warna teks menjadi biru tua dengan kode tersebut <br>

![12CSS](https://github.com/Farahadilahasan/WebsiteRecommer/assets/124495764/414b5da7-b5d7-4479-afda-e70a13645046)

Pada bagian ini akan mengatur tampilan tabel yang responsive <br>
a.	Tbl-biru <br>
•	Background : mengatur warna latar belakang tautan menjadi biru tua dengan kode tersebut <br>
•	Border radus : memberikan sudut bulat pada tautan dengan jari jari sudut sebesar 20 pixel <br>
•	Margin top : menambahkan margin atas sebesar 20 pixel pada tautan <br>
•	Padding 15px 20px 15px 20px : mengatur padding tautan yakni dengan ruang sekitar teks dalam tautan dengan 15 pixel untuk bagian atas dan bawah, 20 pixel untuk sisi kiri dan kanan<br>
•	Color : mengatur warna teks dalam tautan menjadi putih dengan kode warna tersebut <br>
•	Font weight bold : mengatur ketebalan font teks dalam tautan menjadi tebal 

a.	Tbl-biru hover <br>
•	Background : mengubah warna latar belakang tautan menjadi warna merah muda dengan kode warna tersebut saat pengguna mengarahkan kursor ke tautan tersebut <br>
•	Text decoration none : berguna untk menghilangkan dekorasi tautan seperti garis bawah saat pengguna mengarahkan kursor ke tautan <br>

![13CSS](https://github.com/Farahadilahasan/WebsiteRecommer/assets/124495764/ec586f7e-9d45-4357-b195-093c528f02cf)

Aturan css yang berlaku untuk elemen – elemen p <br>
•	Margin : mengatur margin elemen p dengan 10 pixel diatas dan bawah, serta 0 pixel dikiri dan kanan<br>
•	Padding : mengatur padding elemen p dengan 10 pixel diatas dan bawah serta 0 pixel di sisi kiri dan kanan<br>

".tengah" Merupakan aturan css yang berlaku untuk elemen dengan class “tengah” <br>
•	Text=align : mengatur teks menjadi terpusat barada di tengah secara horizontal<br>
•	Width : mengatur lebar elemen menjadi 100% dari lebar halaman nya. Aturan ini memastikan bahwa elemen – elemen tersebut akan mengisi seluruh lebar halaman 

![14CSS](https://github.com/Farahadilahasan/WebsiteRecommer/assets/124495764/a7640d5a-0c30-4cfc-83e5-ce715bead33c)

Aturan untuk recommendation-list 

•	Display flex : menggunakan model tata letak flex box untuk elemen yang terdapat pada class ini. Karna flexbox memungkinkan penataan elemen – elemen dengan tata letak yang fleksibel<br>
•	Flex-wrap :wrap: mengatur elemen untuk dikemas secara fleksibel saat ruang tersedia terbatas. Dengan kata lain elemen yang akan di tambahkan nanti akan turun ke baris selanjutnya jika tidak cukup ruang 

Aturan css untuk kartu-recommendation 

•	Widht : mengatur lebar elemen menjadi 20% dari lebar parent nya, dengan aturan ini maka elemen ini nantinya akan menempati 20% dari  lebar elemen class tersebut <br>
•	Margin 0 auto : mengatur magin atas bawah menjadi 0 pixel dan marhgin samping menjadi auto. Aturan ini digunakan untuk mengatur elemen ini menjadi terletak di tengah secara horizontal 

Aturan css untuk kartu-recommendation img 

•	Widht : mengatur lebar gambar dalam elemen menjadi 80%, sehingga ini akan membuat gambar menjadi lebih kecil daripada lebar elemen 

Aturan css untu recommendation p 

•	Font-family : mengatur jenis font teks dalam elemen paragraf <br>
•	Font weight : mengatur ketebalan font menjadi 800px <br>
•	Font size : mengatur ukuran font menjadi 20 pixel <br>
•	Text align center : mengatur teks dalam paragraf untuk di pusatkan ke tengah secara horizontal <br>
•	Color : mengatur warna teks dalam paragraf menjadi biru tua dengan kode warna tersebut 

![15CSS](https://github.com/Farahadilahasan/WebsiteRecommer/assets/124495764/30e69960-88c7-47d3-88ca-feb915c009b0)

Pada bagian ini adalah aturan css untuk class FindUS-list. 3 class ini terkait isi pengaturan design nya tidak berbeda dengan class sebelumnya (recommendation-list) hanya saja ada beberapa perbedaan dari besar kecilnya skala widht yang digunakan dan juga border radius yang digunakan agar gambar pada class ini berbentuk lingkaran.

![16CSS](https://github.com/Farahadilahasan/WebsiteRecommer/assets/124495764/ba17b547-baf8-4ce7-b030-4cf01ed17112)

Aturan css untuk class “contact”

•	Background : mengatur warna latar belakang elemen dengan id contact menjadi abu abu dengan kode warna tersebut <br>
•	Padding :  mengatur padding elemen id contact dengan 50 pixel bagian atas dan bawah, 0 pixel dibagian  kanan dan kiri 

Aturan css untuk footer 

•	Display flex : menggunakan model tata letak flex box untuk elemen yang terdapat pada class ini. Karna flexbox memungkinkan penataan elemen – elemen dengan tata letak yang fleksibel<br>
•	Flex-wrap :wrap: mengatur elemen untuk dikemas secara fleksibel saat ruang tersedia terbatas. Dengan kata lain elemen yang akan di tambahkan nanti akan turun ke baris selanjutnya jika tidak cukup ruang <br>
•	Margin auto : mengatur margin elemen ‘footer” menjadi “auto” yang akan membantu elemen “footer” berada di tengah secara horizontal 

Aturan css untuk class footer section, pada bagian ini merujuk pada bagian bagian tertentu dalam footer 

•	Width : mengatur lebar elemen dengan class tersebut menjadi 20%, sehingga elemen ini akan menempati 20% dari lebar elemen “footer”<br>
•	Margin 0 auto : mengatur margin atas bawah menjadi 0 pixel dan marhgin samping menjadi auto. Aturan ini digunakan untuk mengatur elemen ini menjadi terletak di tengah secara horizontal 

Aturan untuk css pada class h3

•	Font-family : mengatur jenis font teks untuk elemen h3 menjadi ‘comic sans MS’<br>
•	Font-size : mengatur ukuran font teks untuk elemen h3 menjadi 30 pixel <br>
•	Color : mengatur warna teks untuk elemen h3 menjadi warna biru tua dengan kode warna tersebut <br>

![17CSS](https://github.com/Farahadilahasan/WebsiteRecommer/assets/124495764/20be74bd-0951-4a03-a6e5-384b0f0078cf)

Aturan css untuk elemen dengan id ‘copyright’ yang akan merujuk pada bagian hak cipta di footer

•	Text align center : mengatur teks menjadi terpusat secara horizontal <br>
•	Padding :  mengatur padding elemen id copyright dengan 50 pixel bagian atas dan bawah, 0 pixel dibagian  kanan dan kiri <br>
•	Margin top : berguna untuk menambahkan margin atas sebesar 50 pixel pada elemen dengan id ‘copyright’<br>

<b>PENJELASAN CODING RECOMMEND </b>

dibagian awal halaman semua elemen head dan navbar tidak ada perubahan dari penjelasan sebelumnya, namun yang berubah hanya saja terletak pada link rel/href yang menjadi tautan tujuan 

<b>CLASS CONTAINER</b>

![image](https://github.com/Farahadilahasan/WebsiteRecommer/assets/124495764/a70ad03d-1ab6-4de6-897f-86bc90928111)


Div class “container” merupakan elemen HTML yang digunakan untuk mengelompokkan dan mengatur konten dalam sebuah wadah atau container. Elemen inijuga mambantu untuk memisahkan elemen-elemen pada website agar mudah untuk memanipulasi dan memformatnya. Pada class “container” juga terdapat 3 class lagi diantaranya : <br>
•	Div class “table city”<br>
Elemen ini digunakan untuk mengelompokkan konten yang terkait satu sama lain. Dalam hal ini, ini digunakan untuk mengelompokkan elemen-elemen terkait dengan pilihan kota. Pada class table city ini kita menggunakan elemen input type=”radio berikut penjelasan nya:<br>
o	input type radio dgunakan untuk membuat tombol pilihan yang memungkinkan pengguna memilih satu opsi dari beberapa yang tersedia, pada kasus ini, radio button digunakan untuk membuat daftar kota-kota yang dapat dipilih pengguna  

<b>TABEL KATEGORI</b>

![5 recc](https://github.com/Farahadilahasan/WebsiteRecommer/assets/124495764/933e6bf0-9c87-44a2-8bb9-0b6dbd6abe36)

•	Div class selanjutnya adalah “table category” yang mana elemen untuk isi konten nya tidak jauh berbeda dengan class sebelumya (table city), hanya saja di bagian class ini terdapat tampilan gambar yang terletak di bagian atas kolom setiap konten yang ada pada table categpry. Gambar tersebut kita panggil menggunakan img src yang akan merujuk kepada file gambar yang telah kita simpan di folder asset

<b>TABLE REKOMENDASI</b>

<b>REKOMENDASI PENGINAPAN</b>

![6 recc](https://github.com/Farahadilahasan/WebsiteRecommer/assets/124495764/50abaf5e-69c6-4d93-a1eb-103904b5e4e8)

•	Div class selanjutnya terdapat div class “recommendation” yang berguna untuk mengelompokkan konten rekomendasi dari suatu kategori atau tabel tertentu. Di dalam class recommendation ini akan terdapat beberapa class lagi yang akan berperan sebagai wadah yang fokus terhadap pengelompokkan beberapa rekomendasi yang sesuai dengan kategori, sedangkan Div class “hotel”, merupakan class berguna untuk mengelompokkan isi konten rekomendasi seputar penginapan (kategori), pada class ini terdapat beberapa elemen didalamnya, yakni : <br>
      o	ul class “accordion” yang berguna untuk membuat daftar rekomendasi yang mungkin dapat di perluas atau dipersempit oleh pengguna  <br>
      o	li merupakan elemen list item yang berisi rekomendasi penginapan, setiap elemen ‘li’ yang mewakili satu rekomendasi <br>
      o	input type="radio" name="accordion" id="satu" checked adalah elemen radio button. Ini digunakan untuk membuat pilihan eksklusif di antara rekomendasi penginapan. Atribut name dengan nilai            "accordion" mengelompokkan radio button ini, sehingga hanya satu yang dapat dipilih sekaligus. Radio button dengan id="satu" diberi atribut checked, sehingga ini adalah rekomendasi yang                terpilih secara otomatis saat halaman dimuat. Bersamaan dengan label yang terhubung dengan radio button (id=”tiga”) yang memugkinkan pengguna untuk memilih rekomendasi dengan menklik label            ini <br>
      o	Div class “konten” berguna untuk mengelompokkan konten rekomendasi yang sesuai dengan kategori, termasuk gambar dan deskripsi  <br>
      o	Selanjutnya terdapat elemen img src yang berguna untuk menampilkan gambar dan elemen p yang berguna sebagai deskripsi yang menjelaskan seputar isi konten rekomendasi tersebut   <br>
         Untuk bagian rekomendasi seperti kuliner, wisata, pusat perbelanjaan dan lain sebagainya. Semua elemen di dalamnya sama persis dengan semua elemen yang terdapat pada bagian rekomendasi                sebelumnya (Penginapan). Tidak terdapat banyak perbedaan karna semua rekomendasi yang dikemas dalam setiap kategori nya di tabel rekomendasi memiliki konsep dan tata letak yang sama, hanya            saja pada bagian gambar dan dekskripsi seputar produk nya saja yang membedakan. Berikut kodingan masing-masing rekomendasi per kategorinya  

<b> REKOMENDASI WISATA </b>
![image](https://github.com/Farahadilahasan/WebsiteRecommer/assets/124495764/00fca34b-4657-4c01-baf1-d84ae3d8de62)

<b>REKOMENDASI KULINER</b>
![image](https://github.com/Farahadilahasan/WebsiteRecommer/assets/124495764/15255437-3ab1-422d-ac4a-25247e51a56c)

<b>JAVASCRIPT </b>

![1SR](https://github.com/Farahadilahasan/WebsiteRecommer/assets/124495764/eeb36eb5-4f4d-4b0d-82dd-3ba11637fb74)

<b>hideAllRecommendations()</b> <br>
Fungsi ini digunakan untuk menyembunyikan semua rekomendasi. Ini dicapai dengan mengambil semua elemen rekomendasi (dengan kelas .table.recommendations div) dan mengatur gaya display mereka menjadi 'none' sehingga mereka tidak terlihat di halaman.

<b>showRecommendationsByCategory(category)</b> <br>
Fungsi ini digunakan untuk menampilkan rekomendasi sesuai dengan kategori yang dipilih. Fungsi tersebut mengambil argumen category yang merupakan ID kategori yang dipilih oleh pengguna.

![2SR](https://github.com/Farahadilahasan/WebsiteRecommer/assets/124495764/efcd1c73-dbe3-4a8e-84c8-902b3ce9c5d0)

<b>Fungsi handleCategoryChange()</b><br>

Fungsi ini mengatur event listener untuk mengidentifikasi perubahan pemilihan kategori oleh pengguna

Dengan cara ini, ketika pengguna mengklik salah satu radio button kategori, fungsi ini akan merespons dengan cara menyembunyikan semua rekomendasi terlebih dahulu, kemudian menampilkan rekomendasi yang sesuai dengan kategori yang dipilih oleh pengguna. Ini memberikan pengalaman yang lebih interaktif dan sesuai dengan pilihan pengguna.















































