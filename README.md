<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<style type="text/css">
#recuadro1{
    width: 100%;
    height: 100%;

}
body {
    background: white;
    margin: 50 px;
}
#imagen
{
    height: 300px;
    width: 300px;
    object-fit: cover;
}
</style>
<body>
<div id="recuadro1">
     <img src="ashe.jfif" id="imagen"> <br><br>
     <button onclick="cambioImagen('ashe');">ashe</button>
     <button onclick="cambioImagen('lucian');">lucian</button>
     <button onclick="cambioImagen('jhin');">jhin</button>
     <button onclick="cambioImagen('draven');">draven</button>
     <button onclick="cambioImagen('kaisa');">kaisa</button>
</div>
<script type="text/javascript">
    function cambioImagen(ashe)
{
var elemento=document.getElementById("imagen");
if(ashe==="ashe"){
    elemento.src="ashe.jpg";
}
else if(ashe==="lucian"){
    elemento.src="lucian.jfif";
}
else if(ashe==="jhin"){
    elemento.src="jhin.jfif";
}
else if(ashe==="draven"){
    elemento.src="draven.jfif";
}
else if(ashe==="kaisa"){
    elemento.src="kaisa.png";
}
}
</script>
</body>
</html>
