# continuamos-segunda-parte-HTML-ELEMENTOS-COMPUESTOS
<body>

<h1>CLASE 2 - ELEMENTOS COMPUESTOS</h1>

<!--input de ingreso de datos tipo TEXTO -->
<label for="coment_1">ingresa un comentario</label><br>
<input type="text" id="coment_1" name="coment_1" ><br>

<!--input de ingreso de datos tipo MAIL -->
<label for="mail_1">ingresa tu correo</label><br>
<input type="email" id="mail_1" name="mail_1" ><br>

<!--input de ingreso de datos tipo NUMERO -->
<label for="number_1">ingrese su numero favorito</label><br>
<input type="number" id="number_1" name="number_1" ><br>

<!--input de ingreso de datos tipo CONTRASENA -->
<label for="pass_1">ingresa su password</label><br>
<input type="password" id="pass_1" name="pass_1" ><br>

<!--input de ingreso de datos tipo NUMERO TELEFONICO -->
<label for="phone_1">ingresa un telefono de contacto</label><br>
<input type="tel" id="phone_1" name="phone_1" ><br>

<!--input de ingreso de datos tipo URL o LINK -->
<label for="UrL_1">ingresa un link</label><br>
<input type="url" id="UrL_1" name="UrL_1" ><br>

<hr>

<h2>INPUT DE SELECCION MULTIPLE</h2>

<!--input de marcado de CASILLAS DE SELECCION -->
<input type="checkbox" id="ChecK_1" name="ChecK_1" value="Remeras">
<label for="ChecK_1">Remeras</label><br>


<input type="checkbox" id="ChecK_2" name="ChecK_2" value="Pantalones" >
<label for="ChecK_2">Pantalones</label><br>


<input type="checkbox" id="ChecK_3" name="ChecK_3" value="Camperas">
<label for="ChecK_3">Camperas</label><br>


<h2>INPUT DE SELECCION UNICA</h2>

<h3>Color de su prneda seleccionada: </h3>
<!--input de marcado de CASILLAS DE SELECCION UNICA-->
<input type="radio" id="ChecKuniK_1" name="ChecKuniC" value="Rojo" >
<label for="ChecKuniK_1">Rojo</label><br>


<input type="radio" id="ChecKuniK_2" name="ChecKuniC" value="Azul">
<label for="ChecKuniK_2">Azul</label><br>


<input type="radio" id="ChecKuniK_3" name="ChecKuniC" value="Negro" >
<label for="ChecKuniK_3">Negro</label><br>


<h2>Selector de opciones</h2>

<!--Selector de opciones varias que se abre al hacer click-->
<label for="remeras"></label>
<select name="remeras" id="remeras">
    <option value="mangascortas">mangas cortas</option>
    <option value="mangaslargas">mangas largas</option>
    <option value="muscolosas">musculosas</option>
    <option value="mediamanga">media manga</option>
</select>

<h2>SELECT CON INPUT</h2>
<!--Selector de opciones varias que se abre al hacer click-->
<label for="materialTelas">elige el material de tu prenda</label><br>
<input list="materialTelas">
<datalist id="materialTelas"> 
    <option value="modal">modal</option>
    <option value="algodon">algodon</option>
    <option value="nilon">nilon</option>
    <option value="seda">seda</option>
</datalist>



<h2>INPUT DE FECHAS</h2><br>

<input type="date" id="fecha-1" name="fecha-1"><br>
<input type="datetime-local" id="fecha-2" name="fecha-2"><br>
<input type="week" id="fecha-3" name="fecha-3"><br>
<input type="time" id="fecha-4" name="fecha-4"><br>
<input type="month" id="fecha-5" name="fecha-5"><br>


<h2>INPUT DE ARCHIVO</h2>

<input type="file" id="folder_1" name="folder_1" multiple><br><br>


<h2>INPUT DE COLOR</h2>

<input type="color" id="color_1" name="color_1"><br><br>


<h2>INPUT DE RANGO</h2>

<label for="range1">selecciona el rango de talle</label>
<input type="range" id="range1" name="range1" min="0" max="100"><br><br>


<hr>

<h2>INPUT DE BOTON</h2>

<input type="reset"><br>
<input type="submit"><br>
<input type="button" id="button1" name="button1" value="button1" onclick="alert('bienvenidos a la tienda');">

<hr>
<h2>FORMULARIOS</h2><br>


<form action="/action.js" id="FormularioCompra" method="post">
    <label for="nombre">Nombre:</label>
    <input type="text" id="nombre" name="nombre"><br><br>
    <input type="submit" value="enviar">
    <input type="reset">
</form>

<!--ejemplo de coomo poemos incluir un elemento que esta fuera del formulario y ponerlo dentro con la etiqueta FORM y el ID que le pusimos al FORM al que queremos incluirlo-->
<label for=""></label>
<input type="text" id="apellido" name="apellido" form="FormularioCompra">





</body>
