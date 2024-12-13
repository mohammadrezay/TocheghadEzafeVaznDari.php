# TocheghadEzafeVaznDari.php
https://quera.org/problemset/3404?tab=description
<?php
$n = (int)readline("Enter weight: ");
$m = (float)readline("Enter a hight: ");
$BMI1 = $n / ($m * $m);
$BMI = number_format($BMI1, 2);
if($BMI < 18.5){
	echo $BMI. PHP_EOL . "Underweight";
}elseif($BMI >= 18.5 and $BMI < 25){
	echo $BMI. PHP_EOL . "Normal";
}elseif($BMI >= 25 and $BMI < 30){
	echo $BMI. PHP_EOL . "Overweight";
}elseif($BMI >= 30){
	echo $BMI. PHP_EOL . "Obese";
}
