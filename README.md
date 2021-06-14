# php-loop-break-continue
<?php
 //break and continue
 
 for($a=2; $a<=12; $a++ ){
	 echo $a;
	 echo "<br>";
	 if($a==8){
		 break;
	 }
 }
 echo "<br><br>";
 for($a=2; $a<=12; $a++){
	 echo $a;
	 echo "<br>";
	 if($a==8){
		 continue;
	 }
 }
?>
