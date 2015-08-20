# SOFTWARE
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=iso-8859-1" />
<title></title>


<link href="../../Downloads/css/estilo.html.css" rel="stylesheet" type="text/css" />

<link href="factura.css" rel="stylesheet" type="text/css" />
<style type="text/css">

</style>
<body>
<p>
<form = style= border-color: green;background-image: none> 

</div>

<div>

<link rel="stylesheet" type="text/css" href="../../facturacion.css" />
</head>

<form = style="border-style:groove;border-color: gree;border- width:10px;" >
<p  align="left">Nombre y Apellido<input type="text" id="nombrecliente" ><br /><br />
Direccion <input type="text" id="direccioncliente"> <br /><br />
Telefono <input type="text" id="telefonocliente"> <br /><br />
Fecha<input type="text" id="fecha"> <br /><br />
Factura <input type="text" id="numfact"> 

<center> <table border= 1>;

<tr>

<th rowspan="2"> Cantidad</th>
<th rowspan="2"> Precio Unitario</th>
<th rowspan="2"> Valor Total</th>

</tr>

  <th align="center" valign="middle"></th>

<tr>
<td> <input type="text" name "cant1" id= "cant1"></td>
<td> <input type="text" name "presu1" id= "presu1" ></td>
<td> <input type="text" name "valt1" id= "valt1" ></td>
</tr>

<tr>
<td> <input type="text" name "cant2" id= "cant2" ></td>
<td> <input type="text" name "presu2" id= "presu2" ></td>
<td> <input type="text" name "valt2" id= "valt2" ></td>
</tr>


<tr>
<td> <input type="text" id="cant3" ></td>
<td> <input type="text" id="presu3" ></td>
<td> <input type="text" id="valt3" ></td>
</tf>

<tr>
<td> <input type="text" id="cant4" ></td>
<td> <input type="text" id="presu4" ></td>
<td> <input type="text" id="valt4" ></td>
</tr>


<tr>
<td rowspan="4"></td>
<td rowspan="4"></td>
<td></td>
<td><input type="text" ></td>
</tr>


<tr>
<td> Valor Total</td>
<td><input type="text" id="valortotal"></td>
</tr>

</table>

<form>
<br />




<input type="button" onClick=" valor1()" name="Calcular" id="Calcular" value="Calcular 1" /> 
<input type="button" onClick=" valor2()" name="Calcular2" id="Calcular2" value="Calcular 2" /> 
<input type="button" onClick=" valor3()" name="Calcular3" id="Calcular3" value="Calcular 3" />
<input type="button" onClick=" valor4()" name="Calcular4" id="Calcular4" value="Calcular 4" />
<input type="button" onClick=" valortot()" name="Calculartot" id="Calculartot" value="Calcular Total" />


</p>

</form>


</body>
</html>





<div>

<script type="text/ecmascript">
function valor1(){
var n1 = document.getElementById("cant1").value;
var n2 = document.getElementById("presu1").value;
var n3 = (parseInt(n1) * parseInt(n2))
valt1.value = n3
}

function valor2(){
var n4 = document.getElementById("cant2").value;
var n5 = document.getElementById("presu2").value;
var n6 = (parseInt(n4) * parseInt(n5))
valt2.value = n6
}

function valor3(){
var n7 = document.getElementById("cant3").value;
var n8 = document.getElementById("presu3").value;
var n9 = (parseInt(n7) * parseInt(n8))
valt3.value = n9
}

function valor4(){
var n10 = document.getElementById("cant2").value;
var n11 = document.getElementById("presu2").value;
var n12 = (parseInt(n10) * parseInt(n11))
valt4.value = n12
}


function valortot(){
var n13 = document.getElementById("valt1").value;
var n14 = document.getElementById("valt2").value;
var n15 = document.getElementById("valt3").value;
var n16 = document.getElementById("valt4").value;
var n18 = ((parseInt(n13) + parseInt(n14) + parseInt(n15) + parseInt(n16)))
valortotal.value = n18
	
}

</script>

COMENTARIO FRANCISCO
