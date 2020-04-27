<html>
<head>
	<title>Website Hanif fz</title>
</head>
<body>
 
	<style>
	h1,h2,p,a{
		font-family: sans-serif;
		font-weight: normal;
	}
 
	.jam-digital-malasngoding {
		overflow: hidden;
		width: 310px;
		margin: 20px auto;
		border: 5px solid #efefef;
	}
	.kotak{
		float: left;
		width: 90px;
		height: 80px;
		background-color: #189fff;
	}
	.jam-digital-malasngoding p {
		color: #fff;
		font-size: 38px;
		text-align: center;
		margin-top: 20px;
	}
 
 
</style>
 

<br><br><br>
<div class="jam-digital-malasngoding">
	<div class="kotak">
		<p id="jam"></p>
	</div>
	<div class="kotak">
		<p id="menit"></p>
	</div>
	<div class="kotak">
		<p id="detik"></p>
	</div>
</div>

<center>
    

    <br> <br> <br>
	<h1>Halo, Selamat Pagi :)</h1>
	 <a href="https://www.instagram.com/haniffz28/"><i> Hanif Fz
	<div class="navbar nav-center bg-transparent fixed-bottom">
        <div class="text-white">
           
                <audio src="sheila.mp3" autoplay="autoplay"></audio>
     
   

<script>
	window.setTimeout("waktu()", 1000);
 
	function waktu() {
		var waktu = new Date();
		setTimeout("waktu()", 1000);
		document.getElementById("jam").innerHTML = waktu.getHours();
		document.getElementById("menit").innerHTML = waktu.getMinutes();
		document.getElementById("detik").innerHTML = waktu.getSeconds();
	}

    
</script>

