# CodeMaster
Bitácora de codificación personal de Tomás Achával 

# JS

tipos de datos especiales:
-Undefined: la variable existe pero no tiene valor  (valor declarada pero no inicializada)
-Null: variable está vacia (a propósito), su valor es vacio o null 
-Nan: el resultado de la operación no es un número 

forma de declarar variable:
-var: alcance global
-let: limita el alcance de la variable al bloque en el que se declara
-const: no cambia es permanente (se inicializa al declararla)

prompt: para ingresar datos como alerta (Ej. prompt("mensaje que aparece como alerta"))

document.white("lo que quiera que aparezca en la pagina")

variable.concat(otraVariable) : si la primera variable es un string le agrega el valor de la segunda como si fuera un string 

concatenar con ${}:
variable1 = "texto 2";
variable2 = `texto 1 ${variable1} texto 3`;

operadores de comparación:
- Igualdad : == (no considera el tipo de dato)
- Inigualdad : !=
- Identidad : === (estrictamente iguales, mismo tipo de dato)
- No estrictamente igual : !== 
- >, >=, <, <=

Operadores lógicos:
- AND: exp1 && exp2
- OR: exp1 || exp2
- NOT: !exp1

parseInt() : convierte en entero //falta//

condicionales:
if (condicion) {
  bloque codigo
}

else if (nueva condicion){} //podemos poner muchos de estos//

else {} //la condición es que el anterior if sea falso

Array: varArray = ["string", 23, "sodaEstereo"]; 
Llamar Array : varArray[0]; //si llamo un valor fuera de lo inicializado me da undefined
//si llamo al array sin indice, me devuelve todo el array Ej. "varArray"

array asociativo: son objetos (parecido a formato json) Ej.
let programador = {
  nombre: "Tomás",
  apellido: "Achával",
  edad: 20
};
llamado array: programador["nombre"] //esto devuelve Tomás pero si pongo "programador" sin indicar el indice, me devuelve [object Object] 

//En una variable puedo poner código html//

while (condicion) {} //se puede usar el break;

do {} while (condicion) 

for(let i = 0; i<n; i++){} //la sentencia "continue;" se usa para saltear una iteración y continuar con el resto del bucle

for(nombreVariable in nombreArray) {} // devuelve la posición en la que se encuentra un elemento (también muestra el nombre de las propiedades que tenga el array)

for(nombreVariable of nombreArray) {} // muestra los elementos 

sentencia label:asocia un bucle (menos foreach) a un nombre para terminarlo cuando queramos -> nombreParaElBucle: *estructura de bucle*  (con esto podemos actuar sobre este bucle aunque nos encontremos dentro de un bucle o secuencia hijo)
