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
		width: 330px;
		margin: 20px auto;
		border: 5px solid #efefef;
	}
	.kotak{
		float: left;
		width: 110px;
		height: 100px;
		background-color: #189fff;
	}
	.jam-digital-malasngoding p {
		color: #fff;
		font-size: 36px;
		text-align: center;
		margin-top: 30px;
	}
 
 
</style>
 

<br><br><br><br><br><br></b>
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

</center>
<center>
    

    <br> <br> <br>
	<h1>Halo, Selamat Malam :)</h1>
	<div class="navbar nav-center bg-transparent fixed-bottom">
        <div class="text-white">
        <h5>	© <?php echo date('Y'); ?> Copyright :
            <a href="https://www.instagram.com/haniffz28/"><i> Hanif Fz</a></h5>
                <audio src="sheila.mp3" autoplay="autoplay"></audio>
        </div>
    </div>
   
</center>
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
</body>
</html>
