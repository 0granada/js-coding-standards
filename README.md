# Javascript coding standards
Estandares de codificación para el lenguaje javascript

## indice
// TODO: Hacer indice de contenidos

## 1. Declaración de variables
Declarar variables es una de las cosas más importantes a la hora de codificar, por eso es necesario tener en cuenta las siguientes premisas:

#### Nombres de variables
Los nombres de variables deben ser escritos con notación camellCase.

```javascript
var test;  // Nombre de variable correcto
var i_am_bad; //  Nombre de variable incorrecto
var iAmFine; //  Nombre de variable correcto
```

#### Valores de variables
Los espacios entre el nombre y el valor de una variable son muy importantes, puesto que mejoran la legibilidad del código.

```javascript
var test = 1;  // Nombre de variable correcto
var iAmFine = true; //  Nombre de variable correcto
```

#### Declaración de multiples variables
Cuando se declaran multiples variables deben declararse todas con la misma sentencia `var`, una variable por linea y con coma ( , ) al final a menos que sea la ultima variable, en cuyo caso se usará punto y coma ( ; ) al final de la linea. 
A partir de la segunda linea debe usarse 4 espacios antes del nombre de variable para mejorar la legibilidad del código fuente.

- Una declaración erronea es de la siguiente manera:
```javascript
// declaración erronea
var bad1 = 1;
var iAmFine = true;
var sampleVariable = true;

```

- Una declaración correcta es de la siguiente manera:
```javascript
// declaración correcta
var great = 1, // usa coma
	iAmFine = true, // usa coma
	sampleVariable = true; // usa punto y coma por que es la ultima variable

```

**Nota:** Es aconsejable que cada variable tenga un comentario acerca de su objetivo, de manera que aumente la comprensibilidad del código.
