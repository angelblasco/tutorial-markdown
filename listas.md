# Listas

Hay dos tipos de listas:

## Listas desordenadas

Para crear listas desordenadas se debe utilizar asteriscos `*`, guiones `-`, o simbolos de suma `+`. Hay que dejar un espacio en blanco entre el simbolo y la primera palabra.
Si escribimos:

    - Elemento de lista
	- Elemento de lista
	* Elemento de lista
	* Elemento de lista
	+ Elemento de lista
	+ Elemento de lista
	
Obtenemos en todos los modos:

- Elemento de lista
- Elemento de lista
* Elemento de lista
* Elemento de lista
+ Elemento de lista
+ Elemento de lista

Para generar listas anidadas hay que dar 4 espacios en blanco entes del siguiente `*`, `-`, o `+`

    - Elemento de lista
	- Elemento de lista
	    * Elemento de lista
	    * Elemento de lista
	        + Elemento de lista
	        + Elemento de lista
			
Se mostrara como:

- Elemento de lista
- Elemento de lista
	* Elemento de lista
	* Elemento de lista
	    + Elemento de lista
	    + Elemento de lista
		
## Listas ordenadas

Para crear listas ordenadas debes utilizar la sintaxis de tipo: “número.” 1.. Al igual que ocurre con las listas desordenadas, también podrás anidarlas o combinarlas.

    1. Elemento de lista
	2. Elemento de lista
	    * Elemento de lista
	    * Elemento de lista
	        1. Elemento de lista
	        2. Elemento de lista
			
Mostrara:

1. Elemento de lista
2. Elemento de lista
	* Elemento de lista
	* Elemento de lista
	    1. Elemento de lista
	    2. Elemento de lista
