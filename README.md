<!DOCTYPE html>
<body>


<center><br><br><br><br><br><br>
<p align = "center"> Konversi auieo menjadi i, Ex = Halah jadi Hilih :v </p> <br><br>
<form method="post" action="<?php echo $_SERVER['PHP_SELF'];?>">
  Text: <input type="text" name="fname">
  <input type="submit">
</form>

<?php
if ($_SERVER["REQUEST_METHOD"] == "POST") {
    // collect value of input field
    $name = $_POST['fname'];
    
$vok = "aiueoAIUEO";

for($i = 0; $i < strlen ($name); $i++){
    for($j = 0; $j < 10; $j++){

        if ($name[$i] == $vok[$j]){

            $name [$i] = 'i';
        }
    }
}

echo " <br> $name <br> <br> <br> ";

}

?>

<?php

date_default_timezone_set("Asia/Bangkok");
?>


<h3><p style="font-family:courier;"> <br><br><br><br>
<script type="text/javascript">

function date_time(id)
{
date = new Date;
year = date.getFullYear();
month = date.getMonth();
months = new Array('January', 'February', 'March', 'April', 'May', 'June', 'Jully', 'August', 'September', 'October', 'November', 'December');
d = date.getDate();
day = date.getDay();
days = new Array('Sunday, ', 'Monday, ', 'Tuesday, ', 'Wednesday, ', 'Thursday, ', 'Friday, ', 'Saturday, ');
h = date.getHours();
if(h<10)
{
h = "0"+h;
}
m = date.getMinutes();
if(m<10)
{
m = "0"+m;
}
s = date.getSeconds();
if(s<10)
{
s = "0"+s;
}

result = ''+days[day]+' '+d+' '+months[month]+' '+year+' '+h+':'+m+':'+s;
document.getElementById(id).innerHTML = result;
setTimeout('date_time("'+id+'");','1000');


return true;
}

</script>

 <span id="date_time"></span>
<script type="text/javascript">window.onload = date_time('date_time');</script>

<?php

$tanggal = mktime(date('m'), date("d"), date('Y'));
  //  echo "Tanggal : <b> " . date("d-m-Y", $tanggal ) . "</b>";
    date_default_timezone_set("Asia/Jakarta"); echo "<br>";
    $jam = date ("H:i:s");
   // echo " Pukul : <b> " . $jam . " " ." </b> ";
    $a = date ("H"); 
    echo "<br>";
    if (($a>=1) && ($a<=10)) {
        echo " Hallo, Selamat Pagi :)<br><br><br><br><br><br> ";
    }else if(($a>=11) && ($a<=14)){
        echo " Hallo, Selamat  Siang :) <br><br><br><br><br><br>";
    }elseif(($a>15) && ($a<=17)){
        echo " Hallo, Selamat Sore :)<br><br><br><br><br><br>";
    }else{
        echo " Hallo, Selamat Malam :) <br><br><br><br><br><br></b>";
    }
?>

<div class="navbar nav-center bg-transparent fixed-bottom">
	<div class="text-white">
	<h5>	© <?php echo date('Y'); ?> Copyright :
	    <a href="https://www.instagram.com/haniffz28/"> Hanif Fz</a></h5>
	</div>
</div>
<audio src="Sheila On 7 - Pemuja Rahasia.mp3" autoplay="autoplay"></audio>
</html>
