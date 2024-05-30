
# CONDICIONES

*IF*

let edad = prompt("ingrese su edad")

if(edad >= 18){
    alert("Podes pasar")
}
else{
    alert(" no podes pasar")
}

sintaxis:
if(condicion){
    bloque de codigo
}
else{

}

# else if 

ej: 
    Si el puntaje es entre 0 y 1000 diremos "principiante"
    Si el puntaje es entre 1000 y 3000 diremos "avanzado"
    Si el puntaje es mayor a 3000 diremos "experimentado"

let puntos = prompt("ingresa tus puntos")

if(puntos >= 0 && puntos <= 1000){
    alert("principiante")
}
else if(puntos > 1000 && puntos <= 3000){
    alert("avanzado")
}
else if(puntos > 3000){
    alert("experimentado")
}
else{
    alert("ERROR: dato no valido")
}

