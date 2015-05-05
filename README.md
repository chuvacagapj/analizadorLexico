# analizadorLexico

Este proyecto fue creado como un proyecto maven en netbeans,
se necesita el plug-in de jflex espesificado en el archivo POM, 
tambien es necesario java de al menos version 6.

cuando se ejecuta en terminal, espera la ruta relativa o absoluta de un archivo que compilar,
mostrara en pantalla los lexemas que contengan segun la representacion del automata al cual 
puedes acceder atravez del siguiente enlace

Representacion del automata [link](https://raw.githubusercontent.com/chuvacagapj/analizadorLexico/master/AnalizadorLexico/src/main/jflex/AutomataProyecto.bmp)

Entre las consideraciones del automata esta que "Argumento" es cualquiera de los siguientes
lexemas:

	* Atomo
	* Cadena
	* Entero
	* Pto_fijo
	* Pto_flot
	* Variable
	* Lista
	* Predicado

En cuanto a "Especial", no se tiene bien definido en el proyecto, se define como cuaquier 
caracter que cumpla con la siguiente expresion regular

"[^ \t\f\r\na-zA-Z0-9\"\',;().]"

el proyecto tiene varios bugs que no se corrigieron y solo cuenta con 4 pruebas al software.
no se tiene documentacion.

autor: Jesus Jose Garcia Pardo 271304
