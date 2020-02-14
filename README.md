## vaquitas.py

Vamos a simular que hay vacas yendo por un camino, todas para el mismo lado, y se topan con un puente.
Las vacas caminan a diferentes velocidades, y el puente no soporta el paso de más de una vaca a la vez.

Mirá la implementación que esta ahora, correla algunas veces, y asegurate de entender a grandes rasgos el código.

1_
* Ahora agregale semáforos para asegurar que haya solamente una vaca cruzando el puente a la vez. La ejecución debería verse así:

![vaquitas cruzando el puente](assets/vaquitas.gif) HECHO

### Variantes de vaquitas.py

Ahora podés probar algunas variantes. En principio implementalas todas por separado y siempre tomando como punto de partida la versión que hiciste en el punto anterior.

 2_ 
 * Como máximo haya 2 vacas cruzando el puente a la vez. HECHO
 3_ 
 * Lo mismo que antes, pero para una cantidad _N_ de vacas que se configura antes de ejecutar el programa. HECHO
 4_ 
 * Que haya dos puentes.
 5_
  * Lo mismo que antes, pero para una lista de puentes que se configura antes de ejecutar el programa. (Acá sería buena idea tener una clase `Puente` que indique dónde empieza y qué tan largo es).
 6_ 
 * Que haya vacas caminando en ambos sentidos.
 7_ 
 * Que además de vacas, hayan liebres (muy muy rápidas) y *una* tortuga (muy muy lenta).
