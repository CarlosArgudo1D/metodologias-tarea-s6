# metodologias-tarea-s6
'use strict';

let cashierKey = 1214
let counter = 0
let num;

do
{
    num = (Number(prompt('Ingrese su pin')));
    counter++;
}
while (num != cashierKey && counter < 3);
if (counter == 3 && num != counter)
    {
        alert ('Su clave es incorrecta')
        alert ('Tarjeta Bloqueada')
    }
else 
{
    alert ("Su clave es correcta");
    alert ('Operacion exitosa');
}
