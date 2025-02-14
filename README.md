📌Laporan Praktikum 3 Jaringan Komputer

Nama : M. Rizky Taufik Nur Hidayat

NIM  : 09030582327076

Kelas: TK4B
<hr>

<h1>Tracker data Qos wifi dengan WireShark</h1>

<ol>
<li>Download wireshark dengan komen sudo apt install wireshark di terminal</li>
<img  src="1.png" alt=""  width="300px">

<li>buka wireshark dengan komen sudo wireshar</li>
<img  src="2.png" alt=""  width="300px">

<li>Pilih jaringan yang ingin di track lalu klik start di pojok kiri atas</li>
<img  src="3.png" alt=""  width="300px">

<li>maka tracking sudah di mulai</li>
<img  src="4.png" alt=""  width="300px">

<li>Buka browser dan pilih apa yang mau di track, misal youtube <br>
Lalu scroll atau apapun selama 10 menit</li>
<img  src="5.png" alt=""  width="300px">
<img  src="6.png" alt=""  width="300px">

<li>maka hasil tracking sudah tertangkap</li>
<img  src="7.png" alt=""  width="300px">

<li>filter hasil dari track untuk mencari http</li>
<img  src="7.png" alt=""  width="300px">

<li>filter hasil dari track untuk mencari tcp</li>
<img  src="8.png" alt=""  width="300px">
<img  src="10.png" alt=""  width="300px">

<li>Hasil dari filter tadi di save as ke format csv untuk di olah di excel</li>
<img  src="11.png" alt=""  width="300px">

<li>Pilih bagian menu statistic, lalu capture file properties </li>
<img  src="12.png" alt=""  width="300px">

<li>Disini terlihat data total capture, time span, packet loss, dan jumlah byte </li>
<img  src="13.png" alt=""  width="300px">

<li>Install libreoffice pengganti excel di linux ubuntu dengan komen sudo apt install libreoffice</li>
<img  src="14.png" alt=""  width="300px">

<li>Open app dengan komen di terminal</li>
<img  src="15.png" alt=""  width="300px">

<li>Olah data dengan membuat Time 1, Time 2, Delay 1, dan Delay 2 untuk menghitung <br>
Tiem 1 dan Time 2 untuk menghitung Delay, Sedangkan Delay 1 dan Delay 2 untuk menghitung jitter</li>
<img  src="16.png" alt=""  width="300px">

<li>maka hasil adalah sebagai berikut</li>
<img  src="17.png" alt=""  width="300px">

<li>Berikut total dan hasil perhitungan dari ThroughPut, Packet Loss, Delay, dan Jitter</li>
<img  src="18.png" alt=""  width="300px">
