# curso_asincronismo_javascript

Callbacks --> Ventajas: Simple(una función que recibe otra función). Son universales, corren en cualquier navegador.
Desventajas: Composición tediosa, anidando cada vez más elementos. Caer en Callback Hell.

Promesas --> Ventajas: Facilmente enlazables .Then( return… ).Then - Fácil e intuitivo de leer.
Desventajas: Posible error si no se retorna el siguiente llamado. No corre en todos los navegadores.

Async-Await --> Ventajas: Se puede usar try-catch . Código más ordenado e intuitivo.
Desventajas: No corre en todos los navegadores (se requiere un transpilador).


CALL BACK
peticiones anidadas, call back hell
difincil de leer y entender
corre facilmente en cualquier navegador

PROMESAS
facilmente enlazables
es poderoso
gran capacidad de trabjar con asincronismo

no majea excepcion, solo tiene un catch al final
propenso a error si no se retorna el siguiente llamado
es necesario transpilar para que funcine en todos los navegadores

ASYNC AWAY
se maneja el try catch
son mas facil de leer
es mas facil de entender
es necesario esperar que halgo suceda para ver
es necesario transpilar para que funcine en todos los navegadores