<!DOCTYPE html>
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Travel Agency</title>
	<link rel="stylesheet" type="text/css" href="style.css">
	<link rel="stlesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.main.css"integrity="sha512-z3glpd7yknf1YoNbCzqRK4qyor8gaKU1qmn+CShxbuBussANI9QpRohGBreCFkKxLhei6S9CQXFEbkuqlg0DA==" crossorigin="anonymouse" referrerpolicy="no-referrer"/>
</head>
<body>

	<header>
		<h1>Travel Agency</h1>
	</header>
	<nav>
		<div class="navbar">
			<div class="logo">
				<a href="#">Travel Agency</a>
			</div>
			<ul class="menu">
				<li><a href="#">Beranda</a></li>
				<li><a href="#">Destinasi</a></li>
				<li><a href="#">Video Wisata</a></li>
				<li><a href="#">Audio</a></li>
			</ul>
		</div>
	</nav>
	<main>
		<section class="destinasi">
			<h2>Destinasi Populer</h2>
			<div class="destinasi-item">
				<img src="15.png" alt="Destinasi 1">
				<h3>Destinasi 1</h3>
				<p>lorem ipsum dolor sit amet, consectetur adipisicing elit</p>
				<button>Detail</button>
			</div>
			<div class="destinasi-item">
				<img src="02.png" alt="Destinasi 2">
				<h3>Destinasi 2</h3>
				<p>lorem ipsum dolor sit amet, consectetur adipisicing elit</p>
				<button>Detail</button>
			</div>
			<div class="destinasi-item">
				<img src="17.png" alt="Destinasi 3">
				<h3>Destinasi 3</h3>
				<p>lorem ipsum dolor sit amet, consectetur adipisicing elit</p>
				<button>Detail</button>
			</div>
		</section>
		<selection class="video-wisata">
			<h2>Video Wisata</h2>
			<div class="video-wisata-container">
				<div class="video-wisata-item">
					<h2>video</h2>
					<video width="600" height="400" controls>
						<source src="0330.mp4" type="video/mp4">
					</video>
					<h3>Video</h3>
					<p>Harga: $500</p>
					<p>Durasi: 5 Hari</p>
					<p>Destinasi: Destinasi 1, Destinasi 3</p>
					<button>Beli Sekarang</button>
				</div>
			</div>
		</selection>
		<selection class="kontak">
			<h2>audio</h2>
			<audio controls>
				<source src="audio.mp4" type="audio/mpeg">
				</audio>
		</selection>
	</main>

</body>
</html>
