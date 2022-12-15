# Bienvenido al Prode Tonic3

<div align="center">
<a href="https://tonic3.com/" style="margin-right: 30px" target="_blank">
    <img src="https://info.tonic3.com/hubfs/tonic3-logotype-color.png" width="100" height="100">
</a>
<a align="center" href="http://https://www.plataforma5.la/" target="_blank">
    <img src="https://www.plataforma5.la/static/media/P5Desktop.d1842dd2bff00677295cd7d28a29e60c.svg" width="200" height="100">
</a>
</div>

------------
Proyecto realizado como practica profesional del Coding Bootcamp de Plataforma 5 a mano de la empresa Tonic3.

## Descripcion
Crear una PWA, reutilizable y adaptable, llave en mano, para la realización de Prodes para eventos deportivos. 
La PWA deberá ser adaptable y autoadministrable, se deberá poder acceder desde Argentina, Brasil y Estados Unidos, localizando por IP para cada país. 
Deberá poder usarse como PWA y como Web App tanto en mobile, tablets y desktop. Redirigir países de habla hispana a Argentina, Brasil a la versión en portugués, y USA versión inglés. 

------------
# Instalacion Back

- Realizar un git clone:
	1. HTTPS: `git clone https://github.com/ElianRivoira/PRODE-Tonic3.git`

	2. SSH: `git clone git@github.com:ElianRivoira/PRODE-Tonic3.git`

- En la carpeta "back" realizar un `npm i`
- Generar un archivo .env con los datos del .temple.env en los mismos rellenar los campos de las variables de entorno
		
		PORT = (ingresar el puerto en el que se ejecutará)
		MONGODB_CNN = (ingresar ruta de Mongo)
		TOKEN_PASSPHRASE = (ingresar un string para cifrado de token)
		
- Una vez configurado ejecutar el proyecto con `npm start`


## Diagrama DB
- ### <a href="https://dbdiagram.io/d/6328db260911f91ba5e92378" target="_blank">dbDiagram<a/>


## Documentacion
- ### <a href="https://github.com/ElianRivoira/PRODE-Tonic3/tree/master/front" target="_blank">Front</a>
- ###  <a href="https://github.com/ElianRivoira/PRODE-Tonic3/tree/master/back" target="_blank">Back</a>
