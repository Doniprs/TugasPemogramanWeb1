# Tugas Pemograman web 1


* Nama : Doni Perdana Siringoringo
* NIM  : 312210687
* Kelas: TI.22.B1


### TUGAS

Membuat web portofolio sederhana menggunkan bahasa pemograman *HTML* *CSS*
Berikut Source Code nya

--<!DOCTYPE html>
<html lang="en">

<head>
	<meta charset="UTF-8" />
	<meta http-equiv="X-UA-Compatible" content="IE=edge" />
	<meta name="viewport" content="width=device-width, initial-scale=1.0" />
	<link type="icon" rel="icon" href="img/icon/favicon.ico" />
	<title>Curriculum Vitae</title>
	<!-- 
            Tugas 1 Pemrograman Web 1
            Nama    : Doni Perdana Siringoringo
            Kelas   : TI.22.B1
            NIM     : 312210687
            Prodi   : Teknik Informatika
            Matkul  : Pemrograman Web 1
            Dosen   : Sanudin S.Kom., M.Kom
        -->
	<!-- ambil CSS lokal -->
	<link rel="stylesheet" href="style.css" />
</head>

<body>
	<!-- header dan menu -->
	<header>
		<a class="brand">Doni Perdana Siringoringo
		<div></div>
		<div class="navigasi" style="font-weight: bold">
			<strong>
				<a href="#home">Home</a>
				<a href="#biodata">Biodata</a>
				<!-- <a href="#project">Project</a> -->
				<a href="#kontak">Kontak</a>
			</strong>
		</div>
	</header>
	<!-- akhir header -->
	<!-- home -->
	<section id="home" class="home" style="background-image: url(img/baground.jpeg)">
		<div class="content1">
			<h2>Halo kawan, ini adalah web pertama saya <br /></h2>
			<div class="animasi-text">
				<h3>Belajar network enginering</h3>
				<h3>Belajar Web Desainer</h3>
				<h3>Belajar Web Developer</h3>
			</div>
			<div style="padding-top: 50px">
				<a class="btns" href="#target">target Saya dapat mempelajari</a>
			</div>
		</div>
		<div class="content2"><img src="img/baground.jpeg" class="img" /></div>
	</section>
	<!-- akhir  home -->

	<!-- awal about -->
	<section class="Biodata" id="biodata">
		<div class="title">
			<h2 class="section-title">Biodata</h2>
			<hr style="width: 500px; height: 5px; border-radius: 10px" />
		</div>
		<div class="content">
			<div class="col-left">
				<div class="img-card">
					<img src="img/baground.jpeg" alt="" />
				</div>
			</div>
			<div class="col-right">
				<!-- paragraf 1 -->
				<p style="text-align: justify">
					Halo Kawan, perkenalkan saya Doni perdana siringoringo. Saat ini saya masih menempuh pendidikan S-1 Teknik Informatika
					di <a href="https://www.unsia.ac.id" target="blank" style="text-decoration: none">Universitas Pelita Bangsa
				</a>. Domisili saya di Kabupaten Bekasi
				</p><br>
				<!-- paragraft 2 -->
				<p style="text-align: justify;">
					Kesibukan selain kuliah, saya bekerja di <strong></strong> (PT.Sumber Alfaria Trijaya Tbk)
					Kabupaten Bekasi staff operation. Kadang di waktu luang saya
					menyempatkan diri untuk<em> Belajar menjadi web developer</em>.
				</p>
				<br>
				<!-- tabel 1 untuk data pendidikan -->
				<table border="1">
					<tr>
						<td colspan="2" align="center">
							<h4>Riwayat Pendidikan</h4>
						</td>
					</tr>
					<tr>
						<th>Tahun</th>
						<th>Instansi</th>
					</tr>
					<tr>
						<td width="20%">
							<!-- list 1: pendidikan -->
							<ul>
								<li><strong>2013</strong></li>
								<li><strong>2016</strong></li>
								<li><strong>2019</strong></li>
							</ul>
						</td>
						<td>
							<!-- list 1: pendidikan -->
							<ul>
								<li>SDN  4 Nainggolan</li>
								<li>SMPN 2 Nainggolan</li>
								<li>SMKN 1 Palipi (Otomotif)</li>
							</ul>
						</td>
					</tr>
				</table>
				<br>
				<!-- tabel 2 untuk data perkerjaan -->
				<table border="1">
					<tr>
						<td colspan="2" align="center">
							<h4>Riwayat Pekerjaan</h4>
						</td>
					</tr>
					<tr>
						<th>Tahun </th>
						<th>Instansi</th>
					</tr>
					<tr>
						<td>
							<!-- list 2: pekerjaan -->
							<ul>
								<li>2019 - 2023</li>
							</ul>
						</td>
						<td>
							<!-- list 2: pekerjaan -->
							<ul>
								<li><strong> PT Sumber Alfaria Trijaya</strong>, <em>Staff operation</em></li>
							</ul>
						</td>
					</tr>
				</table>
			</div>
		</div>
	</section>
	<!-- akhir about -->

	<!-- awal project -->
	<section id="project" class="project" style="background-image: url(img/bgmain.png)">
		<div class="title">
			<h2 class="section-title">target</h2>
			<hr style="width: 500px; height: 5px; border-radius: 10px; color: aliceblue" />
		</div>
		<div class="content">
			<div class="card">
				<div class="img-card">
					<a href="https://g.co/kgs/3b9RCj" target="blank" /><img src="icon/html.png" /></a>
				</div>
			</div>
			<div class="card">
				<div class="img-card"><a href="https://g.co/kgs/BYbk5d" target="blank" /><img
						src="icon/css.png" /></a></div>
			</div>
			<div class="card">
				<div class="img-card"><a href="https://g.co/kgs/pYxWq9" target="blank" /><img
						src="icon/js.svg" /></a></div>
			</div>

		</div>
	</section>

	<!-- awal kontak -->
	<section id="kontak" class="kontak"  style="background-image: url(img/bgmain.png)">
		<div class="title">
			<h2 class="section-title">Hubungi Saya</h2>
			<hr style="width: 500px; height: 5px; border-radius: 10px" />
		</div>
		<p style="padding: 50px;color:white;">Untuk kritik, saran dan atau konsultasi project bisa menghubungi saya melalui : <br>
		</p>
		<div class="content">

			<div class="card">
				<div class="img-card"><a href="https://instagram.com/donipsrg?igshid=YnFmN3dsYXJ5MThy" target="blank" />
					<img src="img/Instagram.png" /></a></div>
			</div>
			<div class="card">
				<div class="img-card"><a href="https://instagram.com/donipsrg?igshid=YnFmN3dsYXJ5MThy" target="blank" />
					<img src="img/Whatsapp_37229.png" /></a></div>
			</div>
			<div class="card">
				<div class="img-card"><a href="perdanasiringoringo123@gmail.com" target="blank" />
					<img src="img/g.mail.png" /></a></div>
			</div>
		</div>
	</section>

	<!-- footer -->
	<footer class="footer">Copyright &copy; 2022 |
		<a href="https://facebook.com/underfighter">Perdana Siringoringo</a>
	</footer>
	<!-- akhir footer -->
</body>

</html>--

Dan ini desain nya menggunakan CSS
/* import font google */
@import url("https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap");

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Poppins", sans-serif;
  scroll-behavior: smooth;
}

section {
  padding: 100px 200px;
}

/* untuk header */
header {
  z-index: 999;
  position: fixed;
  background-color: black;
  top: 0;
  left: 0;
  width: 100%;
  padding: 15px 200px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  transition: 0.5s ease;
}

header .brand {
  color: goldenrod;
  font-size: 1.8em;
  font-weight: 700;
  text-transform: uppercase;
  text-decoration: none;
}

header .navigasi {
  position: relative;
}

header .navigasi a {
  color: goldenrod;
  font-size: 1em;
  text-transform: uppercase;
  font-weight: 700;
  text-decoration: none;
  margin-left: 40px;
}

header .navigasi a:hover {
  color: #3a6cf4;
}

body {
  min-height: 110vh;
}

/* h4 secara umum */
h4 {
  color: goldenrod;
}

/* home */
.home {
  position: relative;
  width: 100%;
  min-height: 100vh;
  display: flex;
  background-position: center;
  background-size: cover;
  background-attachment: fixed;
  align-items: center;
}

/* konten kiri */
.home .content1 {
  width: 500px;
}

.home .content1 h2 {
  color: white;
  font-size: 2em;
  font-weight: 500;
}

.home .content1 h2 span {
  font-size: 2em;
  font-weight: 600;
}

.animasi-text {
  position: relative;
  height: 70px;
  overflow: hidden;
}

.animasi-text h3 {
  color: #4e9eff;
  font-size: 3em;
  font-weight: 700;
  line-height: 70px;
  letter-spacing: 1px;
}

.animasi-text h3:nth-child(1) {
  animation: text-move 10s infinite;
}

@keyframes text-move {
  0% {
    margin-top: 0;
  }

  25% {
    margin-top: -70px;
  }

  50% {
    margin-top: -140px;
  }

  75% {
    margin-top: -70px;
  }

  100% {
    margin-top: 0;
  }
}

.btns {
  background-color: #3a6cf4;
  color: gold;
  text-decoration: none;
  margin: 10px;
  padding: 10px;
  border-radius: 10px;
  text-transform: uppercase;
}

.btns:hover {
  background: white;
  color: #3a6cf4;
}

/* konten kanan */
.home .content2 {
  width: 300px;
}

/* foto di halaman home */
.home .img {
  border-radius: 50%;
  width: 65vh;
  position: relative;
  display: flex;
}

/* about */
.about {
  min-height: 150vh;
}

.about .content {
  position: relative;
  width: 100%;
  display: flex;
  justify-content: space-between;
  margin-top: 20px;
}

.about .content .col-left {
  position: relative;
  width: 30%;
}

.about .content .col-right {
  position: relative;
  width: 65%;
}

.about .content .col-left .img-card {
  position: relative;
  width: 100%;
  min-height: 300px;
}

.about .content .col-left .img-card img {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  object-fit: cover;
  border-radius: 10px;
}

table {
  width: 100%;
  align-items: center;
}

ul {
  padding-left: 25px;
}

.title {
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}

.section-title {
  position: relative;
  color: #3a6cf4;
  font-size: 2em;
  font-weight: 500;
}

/* project */
.project {
  min-height: 100vh;
}

.project .content {
  display: flex;
  justify-content: center;
  flex-direction: row;
  flex-wrap: wrap;
  margin-top: 20px;
}

.project .content .card {
  width: 250px;
  margin: 15px;
}

.project .content .img-card {
  position: relative;
  width: 100%;
  height: 250px;
  overflow: hidden;
  border-radius: 10px;
}

.project .content .img-card img {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  object-fit: cover;
  border-radius: 10px;
  transition: 0.5s ease;
}

.project .content .img-card img:hover {
  transform: scale(1.2);
}

/* kontak */
.kontak {
  min-height: 100vh;
  text-align: center;
}

.kontak .content {
  display: flex;
  justify-content: center;
  flex-direction: row;
  flex-wrap: wrap;
  margin-top: 20px;
}

.kontak .content .card {
  width: 100px;
  margin: 15px;
}

.kontak .content .img-card {
  position: relative;
  width: 100%;
  height: 100px;
  overflow: hidden;
  border-radius: 10px;
}

.kontak .content .img-card img {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  object-fit: cover;
  border-radius: 10px;
  transition: 0.5s ease;
}

.kontak .content .img-card img:hover {
  transform: scale(1.2);
}

/* footer */
.footer {
  position: fixed;
  bottom: 0;
  width: 100vw;
  background: black;
  color: #fff;
  text-align: center;
  padding: 1em;
}

.footer a {
  color: #3a6cf4;
  font-weight: 600;
  text-decoration: none;
}
