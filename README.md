# PR1_Zyablyh_lab_rab_1
<!DOCTYPE HTML>
<html>
<head>
<title>Задача 1_1</title>
</head>
<body>
<script>
var a;var b; var c; 
var a=prompt("a?","");
var b=prompt("b?","");
var c=prompt("c?","");
   if (a >= b && a < c) {
alert ('неравенство a<b<c не выполняется' );
} 
   else if (a < b && a <= c && b >= c) {
alert( 'неравенство a<b<c не выполняется' );
}
   else if (a >= b && a >= c && b < c) {
alert( 'неравенство a<b<c не выполняется'); 
}
   else if (a >= b && a >= c && b >= c) {
alert('неравенство a<b<c не выполняется');
}
   else if (a < b && a >= c && b > c){
alert( 'неравенство a<b<c не выполняется ');
}
   else{
alert('неравенство a<b<c  выполняется ');
}
</script>
</body>
</html>
