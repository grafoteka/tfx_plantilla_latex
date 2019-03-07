# tfx_plantilla_latex

/*******************************************************************************************
*
* Maintainer: Jorge De León Rivas
* jorge.deleon@upm.es
* May/05/2018
* Author: Raúl Cebolla
********************************************************************************************/

Este es el directorio de trabajo para escribir una memoria TFG/TFM.

El directorio está estructurado en subdirectorios dedicados cada uno a un capítulo. 
	- Si no son necesarios tantos, se eliminan los directorios o se comentan en  0_documento_final/documento_final.tex 

--- COMO USAR LA PLANTILLA ---

Si solo se quiere escribir un capítulo, compilarlo y ver como queda, se emplea el fichero capitulo.tex

Si ya se tiene el capítulo terminado y se quiere añadir al conjunto de la memoria, se copia todo el contenido del TFG/TFM al fichero capitulo_inc.tex

--- ERRORES AL COMPILAR ---

*Solución al error: Package babel Error: Unknown option `spanish'. Either you misspelled itd. \ProcessOptions*

	- $ sudo apt-get install texlive-lang-spanish

*Solución al error: File `todonotes.sty' not found. ^^M

	- $ sudo apt-get install texlive-full
