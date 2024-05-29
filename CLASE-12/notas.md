*OPERADORES LOGICOS*

# NOT o negacion:
Nos da el valor booleano opuesto al dato que estoy negando.

ej:
console.log( ! true ) = false
console.log( ! " " ) = true 

# OR o O
Seleccionar
Si el primer valor es un valor falsy, va a seleccionar el segundo valor.
Si el primer valor es un valor verdadero, va a seleccionar el primer valor.

ej:
console.log( "" || "pepe" ) = pepe
console.log( "" || 0 ) = 0
console.log( "pepe" || 0 ) = pepe

# &&: AND o  Y Logico
Evalua si el primer valor es un true o un falsy
Si es false, devuelve el primer valor.
Si es true, devuelve el segundo valor.

ej:
console.log( 0 && 7) = 0
console.log( true && 7) = 7

# Tablas de la verdad:
AND:
true && true = true
true && false = false
false && true = false
false && false = false

OR:
true || true = true
true || false = true
false || true = true
false || false = false

