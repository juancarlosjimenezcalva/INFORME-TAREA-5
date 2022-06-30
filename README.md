# INFORME TAREA 5

## OBJETIVO GENERAL:

Comprender el análisis de ramas, lazos y nodos, al mismo tiempo los conceptos y el funcionamiento del magnetismo y el electromagnetismo, por medio de la investigación en fuentes confiables, resolución de ejercicios de los temas antes previstos y la elaboración de un informe explicando los temas, para así lograr aplicar los métodos de corrientes en ramas y trayectorias cerradas, método de voltaje en nodos, y conceptos del magnetismo y electromagnetismo.

## OBJETIVOS ESPECÍFICOS: 

-	Explicar como plantear y resolver un sistema de ecuaciones en el análisis de circuitos.
-	Demostrar los métodos de corrientes en ramas, corrientes en trayectorias cerradas y voltaje en nodos.
-	Definir los conceptos de campo magnético, electromagnetismo, dispositivos electromagnéticos, histéresis magnética, inducción electromagnética, y sus aplicaciones.

## MARCO TEÓRICO:

### SISTEMA DE ECUACIONES EN EL ANÁLISIS DE CIRCUITOS

Las ecuaciones simultáneas se componen de un conjunto de n ecuaciones que contiene n incógnitas, donde n es un número con un valor de 2 o más. El número de ecuaciones incluidas en el conjunto debe ser igual al número de incógnitas. Por ejemplo, para determinar dos variables desconocidas, se requieren dos ecuaciones; para tres incógnitas se requieren tres ecuaciones, y así sucesivamente.  

#### SOLUCIÓN DE SISTEMAS DE ECUACIONES

#### SOLUCIÓN POR SUSTITUCIÓN 

Se pueden resolver dos o tres ecuaciones simultáneas en la forma estándar mediante sustitución algebraica determinando primero una de las variables en función de las otras. Sin embargo, como el proceso puede llegar a ser bastante tedioso, este método se restringirá a ecuaciones de segundo grado.

Por ejemplo:

![image](https://user-images.githubusercontent.com/105565683/176758384-adb2dbce-a2ab-4eef-add0-1717ccc151a3.png)

#### SOLUCIÓN DE DETERMINANTES

El método de determinantes es una parte del álgebra de matrices y proporciona un método de “recetario de cocina” para resolver ecuaciones simultáneas con dos o tres variables. Una matriz es una tabla de números, y un determinante es efectivamente la solución de una matriz, y cuyo resultado es un valor específico. Se utilizan determinantes de segundo grado para dos variables y de tercer grado para tres variables. Las ecuaciones deben estar en la forma estándar para encontrar su solución.

Por ejemplo:

![image](https://user-images.githubusercontent.com/105565683/176758567-a7f16859-d96b-46a1-862c-b818e64fe72e.png)

![image](https://user-images.githubusercontent.com/105565683/176758583-7801c05c-ce52-4dcc-aa0f-721c79642450.png)
![image](https://user-images.githubusercontent.com/105565683/176758606-d73d4339-6f28-499a-b8ab-60e1051e75ea.png)

Para un sistema de ecuaciones de tres variables el proceso seria:

![image](https://user-images.githubusercontent.com/105565683/176758646-a0c3ed8f-9c6b-436f-a0f9-fe152b46a277.png)

![image](https://user-images.githubusercontent.com/105565683/176758661-d2fa9fe0-99e3-48db-968a-e8ab501a97c6.png)
![image](https://user-images.githubusercontent.com/105565683/176758701-b44f5ac8-b660-4ce2-82a9-0a829962b2ee.png)

Para sistemas de ecuaciones de un grado superior o mas complejas es recomendable utilizar una calculadora, por ejemplo:

![image](https://user-images.githubusercontent.com/105565683/176758750-4563597d-5c45-4189-b9d4-07897d60573b.png)

### MÉTODO DE LA CORRIENTE EN RAMAS

Primero hay que tener un par de definiciones previas:

-	Un lazo es una trayectoria completa para la corriente que circula en un circuito, y un conjunto de lazos no redundantes puede ser visto como un conjunto de “marcos de ventana”, donde cada marco representa un lazo no redundante.
-	Un nodo es un punto donde se conectan dos o más componentes.
-	Una rama es una trayectoria que conecta dos nodos.

Los pasos parar el método de corrientes de ramas es el siguiente:

#### Paso 1

Asignar una corriente a cada rama del circuito en una dirección arbitraria. 

#### Paso 2

Indicar las polaridades de los voltajes presentes en los resistores de acuerdo con las direcciones de las corrientes asignadas a las ramas. 

#### Paso 3

Aplicar la ley del voltaje de Kirchhoff alrededor de cada lazo (la suma algebraica de los voltajes es igual a cero). 

#### Paso 4

Aplicar la ley de la corriente de Kirchhoff en el número mínimo de nodos de modo que todas las corrientes de rama estén incluidas (la suma algebraica de las corrientes que entran o salen a un nodo es igual a cero). 

#### Paso 5

Resolver las ecuaciones resultantes de los pasos 3 y 4 para determinar los valores de las corrientes de rama

### MÉTODO DE LA CORRIENTE DE LAZO

Normalmente este proceso se aplica para circuitos con dos lazos:

![image](https://user-images.githubusercontent.com/105565683/176758955-455ed339-733a-42cc-bc46-21181a6bfe4f.png)

(La suma de los resistores dispuestos en un lazo) multiplicada por (la corriente de lazo) menos (cada resistor común a ambos lazos) multiplicado por (la corriente del lazo aso ciada adyacente) es igual (al voltaje de fuente presente en el lazo).

Los pasos para el método de la corriente de lazo:

#### Paso 1

Aunque la dirección asignada a una corriente de lazo es arbitraria, se asignará una corriente en el sentido de las manecillas del reloj (SMR) alrededor de cada lazo no redundante, por consistencia. Ésta puede no ser la dirección de la corriente real, pero no importa. El número de asignaciones de corrientes de lazo debe ser suficiente para incluir las corrientes que circulan a través de todos los componentes del circuito. 

#### Paso 2

Indicar las polaridades de las caídas de voltaje en cada lazo con base en las direcciones de corriente asignadas. 

#### Paso 3

Aplicar la ley del voltaje de Kirchhoff alrededor de cada lazo. Cuando más de una corriente de lazo pasa a través de un componente, se deberá incluir su caída de voltaje. Esto produce una ecuación para cada lazo. 

#### Paso 4

Resolver las ecuaciones resultantes para las corrientes de lazo utilizando sustitución o determinantes.

Para circuitos con mas lazos, los pasos son:

El método de la corriente en lazos puede ser sistemáticamente aplicado a circuitos que tengan cualquier cantidad de lazos. Desde luego, mientras más lazos haya, más difícil será encontrar la solución, pero las calculadoras han simplificado en gran medida la resolución de ecuaciones simultáneas. La mayor parte de los circuitos con que usted se encontrará no tendrá más de tres lazos. Recuerde que las corrientes de lazo no son corrientes físicas reales sino cantidades matemáticas asignadas para propósitos de análisis. 

Un circuito ampliamente utilizado con el que ya se topó usted es el puente Wheatstone. Éste originalmente se diseñó como un instrumento de medición autónomo, pero ha sido reemplazado en gran medida por otros instrumentos. No obstante, el circuito puente Wheatstone se encuentra incorporado en instrumentos de medición automáticos, y como previamente se explicó, se utiliza mucho en la industria de las básculas y en otras aplicaciones de medición. 
Un método para determinar los parámetros del puente, y que conduce directamente a encontrar la corriente en cada brazo del puente y la corriente de carga, es escribir ecuaciones de lazo para el puente.

![image](https://user-images.githubusercontent.com/105565683/176759110-190a8a01-466e-464c-89f3-c8dc19312014.png)

Otro circuito útil de tres lazos es el circuito puente T. Si bien este circuito se aplica principal mente en circuitos filtro de ca que utilizan componentes reactivos, se introduce aquí para ilustrar la solución de circuitos de tres lazos.

![image](https://user-images.githubusercontent.com/105565683/176759155-40530f5c-0d9b-4140-8407-9cfeda55233c.png)

### MÉTODO DE VOLTAJE EN NODOS

Se basa en la determinación de los voltajes presentes en cada nodo del circuito mediante la ley de la corriente de Kirchhoff.

Los pasos generales para aplicar el método del voltaje en nodos al análisis de circuitos son los siguientes: 

#### Paso 1

Determinar el número de nodos

#### Paso 2

Seleccionar un nodo como referencia. Todos los voltajes serán con respecto al nodo de re ferencia. Asignar designaciones de voltaje a cada nodo donde el voltaje es desconocido. 

#### Paso 3

Asignar corrientes en cada nodo donde se desconoce el voltaje, excepto en el nodo de referencia. Las direcciones son arbitrarias.

#### Paso 4

Aplicar la ley de la corriente de Kirchhoff a cada nodo donde se asignan las corrientes. 

#### Paso 5

Expresar las ecuaciones de corriente en función de voltajes, y resolver las ecuaciones para determinar los voltajes de nodo desconocidos mediante la ley de Ohm.

### MÉTODO DEL VOLTAJE EN NODOS PARA UN PUENTE WHEATSTONE

![image](https://user-images.githubusercontent.com/105565683/176759312-00ab3be4-7b87-4ef2-b84e-d52b7f18c17a.png)

El nodo D se elige casi siempre como el nodo de referencia, y el nodo A tiene el mismo potencial que el voltaje de fuente. Cuando se constituyen las ecuaciones para los dos voltajes de nodo desconocidos (B y C), es necesario especificar la dirección de la corriente como se describe en los pasos generales. La dirección de la corriente en RL depende de las resistencias del puente; si la dirección asignada es incorrecta, la corriente aparecerá como negativa en la solución.

La ley de la corriente de Kirchhoff se escribe entonces para cada uno de los nodos desconocidos. Así, cada corriente se expresa en función de voltajes de nodo utilizando la ley de Ohm como sigue:

![image](https://user-images.githubusercontent.com/105565683/176759382-efa37767-e1dd-49cc-a738-9065fb60bf6d.png)

### MÉTODO DEL VOLTAJE EN NODOS PARA EL CIRCUITO PUENTE T

![image](https://user-images.githubusercontent.com/105565683/176759423-bb62f747-36ac-4312-9e69-826195edc079.png)

El nodo D es la referencia y el A es el voltaje de fuente, de tal suerte que los dos voltajes desconocidos están en los nodos C y D. El efecto de un resistor de carga en el circuito es casi siempre la pregunta más importante, por lo que el voltaje en el nodo C es el objetivo principal. La solución de las ecuaciones simultáneas con una calculadora se simplifica para analizar el efecto de varias cargas porque solamente la ecuación para el nodo C se ve afectada cuando cambia la carga.

### EL CAMPO MAGNÉTICO

El campo magnético es el espacio que rodea una carga o corriente eléctrica en movimiento. En este espacio se produce una fuerza sobre cualquier otra carga o corriente en movimiento que se coloque en el campo.

![image](https://user-images.githubusercontent.com/105565683/176759500-2ba6d81f-6364-4781-b53a-ca0ded0fb1ca.png)

### FLUJO MAGNÉTICO (ɸ)

El grupo de líneas de fuerza que van del polo norte al polo sur de un imán se llama flujo magnético, simbolizado mediante ɸ (la letra griega fi). El número de líneas de fuerza presentes en un campo magnético determina el valor del flujo. Mientras más líneas de fuerza haya, más grande es el flujo y más intenso el campo magnético.

![image](https://user-images.githubusercontent.com/105565683/176759580-bbe97ec6-5135-4bbe-aa56-9d2c24fa7f38.png)

Cabe recalcar como funcionan los polos en un imán:

![image](https://user-images.githubusercontent.com/105565683/176759646-b04df35a-674c-4345-ad3f-48f484f50b3e.png)

### DENSIDAD DE FLUJO MAGNÉTICO (B)

La densidad de flujo magnético es la cantidad de flujo por unidad de área perpendicular al campo magnético. Se simboliza mediante B, y su unidad SI es el tesla (T). Un tesla es igual a un weber por metro cuadrado (Wb/m^2). La fórmula siguiente expresa la densidad de flujo:

![image](https://user-images.githubusercontent.com/105565683/176759729-d020e79a-7082-4853-9ab1-995616b682ad.png)

donde f es el flujo (Wb) y A es el área de sección transversal en metros cuadrados (m^2) del campo magnético.

El Gauss Aunque el Tesla (T) es la unidad en el SI de densidad de flujo, de vez en cuando se utiliza otra unidad llamada gauss del sistema CGS (centímetro-gramo-segundo), donde (104 gauss   1 T). De hecho, el instrumento utilizado para medir la densidad de flujo es el gaussímetro. El gauss es una unidad conveniente para emplear en campos magnéticos pequeños tales como el campo magnético terrestre, el cual oscila entre 0.3 y 0.6 gauss, según el lugar

### MAGNETIZACIÓN DE MATERIALES 

Los materiales ferromagnéticos tales como hierro, níquel y cobalto se magnetizan al colocarlos en el campo magnético de un imán. Todos hemos visto que un imán permanente atrae cosas como sujetapapeles, clavos y limaduras de hierro. En estos casos, el objeto se magnetiza (es decir, en realidad se convierte en un imán) debido a la influencia del campo magnético permanente y es atraído por el imán. Cuando se retira el campo magnético, el objeto tiende a perder su magnetismo. 

Los materiales ferromagnéticos provocan que se creen dominios magnéticos diminutos dentro de su estructura atómica. Estos dominios pueden ser considerados como pequeñísimas barras imantadas con polos norte y sur.

Los imanes permanentes se utilizan en interruptores, tales como el interruptor magnético normalmente cerrado (NC).

![image](https://user-images.githubusercontent.com/105565683/176759843-3c07b0bb-81b2-4fc9-8548-387c9f382264.png)

### ELECTROMAGNETISMO

El electromagnetismo es la producción de un campo magnético por una corriente en un conductor.

La corriente produce un campo magnético, llamado campo electromagnético, alrededor de un conductor. Las líneas de fuerza invisibles del campo magnético forman un patrón circular concéntrico alrededor del conductor y son continuas a todo lo largo de éste. A diferencia de la barra imantada, el campo magnético que rodea un conductor no tiene polo norte o sur. La dirección de las líneas de fuerza que rodean el conductor mostrado en la figura es para corriente convencional. Las líneas están en el mismo sentido que las manecillas del reloj. Cuando se invierte la corriente, las líneas del campo magnético van en dirección contraria a la de las manecillas del reloj.

![image](https://user-images.githubusercontent.com/105565683/176759910-6980acd0-ee52-4ada-b4f6-2fe4687747ee.png)

Aunque el campo magnético no es visible, tiene capacidad para producir efectos visibles. Por ejemplo, al insertar perpendicularmente en una hoja de papel un conductor que transporta corriente, limaduras de hierro colocadas en la superficie del papel se acomodan en líneas de fuerza magnéticas formando anillos concéntricos.

![image](https://user-images.githubusercontent.com/105565683/176759933-36457f9c-5c2d-4ed3-a1ab-ab0afba8e2b1.png)

Regla de la mano derecha: Una ayuda para recordar la dirección de las líneas de fuerza. Imagine que usted está sujetando el conductor con su mano derecha, con el pulgar apuntando en la dirección de la corriente; así, sus dedos apuntarán en la dirección de las líneas de fuerza magnéticas.

![image](https://user-images.githubusercontent.com/105565683/176759960-1c93fa56-8cfa-44de-aed5-d0306b4329bd.png)

### PROPIEDADES ELECTROMAGNÉTICAS

Permeabilidad (µ) La facilidad con que un campo magnético puede ser establecido en un material dado se mide mediante la permeabilidad de dicho material.

Reluctancia (ℛ) La oposición al establecimiento de un campo magnético en un material se llama reluctancia.

Fuerza magnetomotriz (fmm) Como ya se vio, la corriente que circula en un conductor pro duce un campo magnético. La causa de un campo magnético se llama fuerza magnetomotriz (fmm).

El electroimán: Un electroimán está basado en las propiedades que se acaban de aprender. Un electroimán básico es simplemente una bobina de hilo arrollado alrededor de un núcleo que es fácil de magnetizar.

### DISPOSITIVOS ELECTROMAGNÉTICOS

El solenoide: es un tipo de dispositivo electromagnético provisto de un núcleo de hierro móvil llamado émbolo. El movimiento de este núcleo de hierro depende tanto del campo electromagnético como de la fuerza mecánica de un resorte.

![image](https://user-images.githubusercontent.com/105565683/176760047-97e0306d-0162-4c28-8ccb-dacb78a29abc.png)

La válvula solenoide: En controles industriales, las válvulas solenoide son ampliamente utilizadas para controlar el flujo de aire, agua, vapor, aceites, refrigerantes, y otros fluidos. Se utilizan válvulas solenoide en sistemas tanto neumáticos (aire) como hidráulicos (aceite), que son comunes en controles de máquinas. Las válvulas solenoide también son comunes en los campos aeroespacial y médico. Estas válvulas pueden mover un émbolo, abrir o cerrar un orificio o hacer girar una cantidad fija una válvula de charnela.

![image](https://user-images.githubusercontent.com/105565683/176760161-745efc89-06b6-4d8c-88ad-3fe5680b92ea.png)

El relevador: difiere del solenoide en que la acción electromagnética se utiliza para abrir o cerrar contactos eléctricos y no para producir movimiento mecánico.

![image](https://user-images.githubusercontent.com/105565683/176760191-00137f52-6ca4-473b-9617-0fa09b774c12.png)

Un altavoz es un dispositivo electromagnético que convierte señales eléctricas en ondas sonoras. Comúnmente se utilizan altavoces de imán permanente en estéreos, radios y televisiones y su operación está basada en el principio de electromagnetismo.

![image](https://user-images.githubusercontent.com/105565683/176760246-edacef2e-35c8-4a8c-bdfc-1459ce569d85.png)

### HISTÉRESIS MAGNÉTICA

#### Intensidad de campo magnético (H)

La intensidad de campo magnético (llamada también fuerza magnetizante) en un material se define como la fuerza magnetomotriz (Fm) por unidad de longitud (l) del material, y se expresa mediante la fórmula siguiente. La unidad de intensidad de campo magnético (H) es el ampere vueltas por metro (ampere-turn/metro, At/m

![image](https://user-images.githubusercontent.com/105565683/176760343-ae51e194-70c2-4511-b729-4a5d4cfe9e98.png)

donde Fm = NI.

Observe que la intensidad de campo magnético depende del número de vueltas (N) de la bobina de alambre, de la corriente (I) que circule a través de la bobina, y de la longitud (l) del material. No depende del tipo de material.

Como f = Fm/ℛ, al incrementarse Fm, el flujo aumenta. Asimismo, la intensidad del campo magnético (H) se incrementa. Recuerde que la densidad de flujo (B) es el flujo por área de sección transversal unitaria (B = ɸ/A), por lo que B también es proporcional a H. La curva que muestra cómo están relacionadas estas cantidades (B y H) se llama curva B-H o curva de histéresis.

![image](https://user-images.githubusercontent.com/105565683/176760378-f57bba4f-69eb-4a3a-9e6f-f633b8838ac2.png)

#### La curva de histéresis y retentividad

La histéresis es una característica de un material magnético por la cual un cambio de magnetización retrasa la aplicación de la intensidad de campo magnético. La intensidad de campo magnético (H) puede ser incrementada o reducida con facilidad variando la corriente a través de la bobina de alambre, y puede ser invertida invirtiendo la polaridad del voltaje presente en la bobina.

![image](https://user-images.githubusercontent.com/105565683/176760465-18349b3f-f613-4c4e-97df-0be26ae65c31.png)

### INDUCCIÓN ELECTROMAGNÉTICA

#### Movimiento relativo

Cuando un conductor se mueve a través de un campo magnético, existe un movimiento relativo entre el conductor y el campo magnético. Asimismo, cuando un campo magnético se mueve más allá de un conductor estacionario, también existe movimiento relativo. En ambos casos, este movimiento relativo produce un voltaje inducido (vind) en el conductor.

La cantidad de voltaje inducido (vind) depende de la densidad de flujo, B, de la longitud del conductor, l, expuesta al campo magnético, y de la velocidad a la cual el conductor y el campo magnético se mueven uno con respecto al otro. Mientras más rápida es la velocidad relativa, más grande es el voltaje inducido. La ecuación para voltaje inducido en un conductor es:

![image](https://user-images.githubusercontent.com/105565683/176760539-2dd6be1f-d8b8-4373-a805-a497a1960757.png)

donde vind es el voltaje inducido, B es la densidad de flujo en teslas, l es la longitud del conductor expuesta al campo magnético expresada en metros, y v es la velocidad relativa en metros por segundo.

![image](https://user-images.githubusercontent.com/105565683/176760579-bf8eea83-56ee-4400-a978-edc53699192e.png)

#### Polaridad del voltaje inducido

![image](https://user-images.githubusercontent.com/105565683/176760610-28320408-d55e-4fdc-b5f3-7cd44fc753f2.png)

#### Corriente inducida

![image](https://user-images.githubusercontent.com/105565683/176760644-4dfe29f6-933a-48ed-ae1d-776a93f374c5.png)

#### Fuerzas que actúan sobre un conductor que transporta corriente en un campo magnético (Acción de motor)

![image](https://user-images.githubusercontent.com/105565683/176760677-88360289-6c13-46b1-a670-f63e7b9a4d47.png)

### LEY DE FARADAY

Michael Faraday descubrió el principio de inducción electromagnética en 1831. Encontró que al mover un imán a través de una bobina de alambre se inducía voltaje en la bobina, y que cuando se proporcionaba una trayectoria completa, el voltaje inducido provocaba una corriente inducida, como ya se vio. Dos observaciones de Faraday se enuncian como sigue: 

1.	La cantidad de voltaje inducido en una bobina es directamente proporcional a la rapidez de cambio del campo magnético con respecto a la bobina (df/dt). 

![image](https://user-images.githubusercontent.com/105565683/176760745-0f87b4ee-25d6-43d0-a2d7-448b7403570d.png)

2.	La cantidad de voltaje inducido en una bobina es directamente proporcional al número de vueltas de alambre que hay en la bobina (N).

![image](https://user-images.githubusercontent.com/105565683/176760770-df5ea83d-15cc-4ae6-9db2-93c9d76ba0d7.png)

La ley de Faraday se enuncia como sigue: El voltaje inducido a través de una bobina de alambre es igual al número de vueltas que haya en la bobina multiplicado por la velocidad de cambio del flujo magnético. 

![image](https://user-images.githubusercontent.com/105565683/176760830-edd7f271-5334-418a-8bd5-500435a2dd79.png)

### LEY DE LENZ

Cuando la corriente que pasa a través de una bobina cambia, se crea un voltaje inducido a consecuencia del campo electromagnético cambiante y la polaridad del voltaje inducido es tal que siempre se opone al cambio de corriente.

## EXPLICACIÓN Y RESOLUCIÓN DE EJERCICIOS O PROBLEMAS

Resolución de ejercicios pares de los capítulos 9 y 10 del libro Principios de Circuitos Eléctricos - Floyd.

### CAPITULO 9 ANALISIS DE RAMAS, LAZOS Y NODOS:

2. Evalúe cada determinante:

![image](https://user-images.githubusercontent.com/105565683/176253097-50d365fa-a86b-4465-84f9-69c01e8812ef.png)

4. Evalúe cada uno de los determinantes:

![image](https://user-images.githubusercontent.com/105565683/176253164-242e4151-6004-4d91-be26-5c056b9c8592.png)

6. Determine I3 en el ejemplo 9-4.

![image](https://user-images.githubusercontent.com/105565683/176253182-2d9a758f-969b-49b5-a434-2979328985d5.png)

![image](https://user-images.githubusercontent.com/105565683/176253219-08403b56-c8ec-4a6d-9d03-9530c1c5415f.png)

8. Determine V1, V2, V3 y V4 resolviendo el siguiente conjunto de ecuaciones con una calculadora:

![image](https://user-images.githubusercontent.com/105565683/176253247-5aad7afb-9f59-4b3b-8650-7b4c8d266ddd.png)

![image](https://user-images.githubusercontent.com/105565683/176253266-0f08c1ae-97e0-4295-a6b5-c9ceacb9458f.png)

![image](https://user-images.githubusercontent.com/105565683/176253303-4c7a231b-cbb0-4b9e-a718-32f2fafb6dfe.png)

10. Resuelva las tres ecuaciones simultáneas del problema 7 con su calculadora.

![image](https://user-images.githubusercontent.com/105565683/176253334-1a529f5f-9489-4fbb-aaec-aeccb4423214.png)

![image](https://user-images.githubusercontent.com/105565683/176253380-4b4c50e4-472a-4402-973c-34cf07143e9e.png)

![image](https://user-images.githubusercontent.com/105565683/176253448-ff32f8b0-5d77-4735-9847-2e269fc5dc0a.png)

12. Resuelva para cada una de las corrientes de rama ilustradas en la figura 9-26.

![image](https://user-images.githubusercontent.com/105565683/176253477-bf693f26-217b-4403-804e-50da9a1a1b08.png)

![image](https://user-images.githubusercontent.com/105565683/176253529-59da44e8-7102-4132-9787-7c01f4d84610.png)

14. Determine la corriente a través de cada resistor mostrado en la figura 9-27.

![image](https://user-images.githubusercontent.com/105565683/176256271-4d06ceee-bbce-440b-9758-764c1ba2967c.png)

![image](https://user-images.githubusercontent.com/105565683/176256312-874a2ce7-73c2-430f-a76d-785f39b73534.png)

16. Escriba el determinante característico para las ecuaciones:

![image](https://user-images.githubusercontent.com/105565683/176256353-83e06585-68a8-4a4d-ae55-f35faae1417e.png)

![image](https://user-images.githubusercontent.com/105565683/176256396-713eca44-06c4-461a-bff8-8d8a4b9414a8.png)

18. Determine las corrientes de rama en la figura 9-28.

![image](https://user-images.githubusercontent.com/105565683/176256432-8627aacd-06f7-4ba4-9863-83c587a91c1c.png)

![image](https://user-images.githubusercontent.com/105565683/176256461-4a49f356-f0d6-43e3-8703-3f369024bd74.png)

20. Escriba las ecuaciones de lazo para el circuito de la figura 9-29.

![image](https://user-images.githubusercontent.com/105565683/176256496-2bc1fee4-42b3-40ed-87e3-9d5045266ddf.png)

![image](https://user-images.githubusercontent.com/105565683/176256538-9db87dc8-050a-41aa-bbb0-da692ae3e8b6.png)

22. Determine la corriente a través de cada resistor en la figura 9-29

![image](https://user-images.githubusercontent.com/105565683/176256644-55d88168-1450-4018-808d-fd1cf5d16001.png)

![image](https://user-images.githubusercontent.com/105565683/176256676-1f02d287-bdcd-47cc-b394-abe93a4c3c70.png)

24. Cuando se conecta un resistor de 10 kΩ desde la terminal A hasta la terminal B en la figura 9-30, ¿cuál es la corriente que circula a través de él?

![image](https://user-images.githubusercontent.com/105565683/176256765-1290707d-de4d-4fcb-8f75-5c25487a4bb6.png)

![image](https://user-images.githubusercontent.com/105565683/176737917-ee6c3746-235b-4721-8b77-6484266d7f90.png)

26. En la figura 9-32, use el método del voltaje en nodos para determinar el voltaje presente en el punto A con respecto a tierra.

![image](https://user-images.githubusercontent.com/105565683/176256817-5808f093-e9ec-4369-a607-8c871e125226.png)

![image](https://user-images.githubusercontent.com/105565683/176737997-08129491-f108-4a32-a63e-2bda67583b7e.png)

28. Escriba las ecuaciones de voltaje de nodo para la figura 9-29. Use su calculadora para determinar los voltajes de nodo.

![image](https://user-images.githubusercontent.com/105565683/176256861-8324c09e-9c21-44b5-b302-eb583477fd40.png)

![image](https://user-images.githubusercontent.com/105565683/176739772-14d265fa-4f30-4c6a-89b2-cd9cd59afbe3.png)

30. Determine el voltaje en los puntos A, B y C en la figura 9-34

![image](https://user-images.githubusercontent.com/105565683/176256890-2290d056-2e7c-4196-b2b5-980a2c14af42.png)

![image](https://user-images.githubusercontent.com/105565683/176738795-ae4a9149-012b-4b87-86f4-048edf37310a.png)

### CAPITULO 10 MAGNETISMO Y ELECTROMAGNETISMO:

2. En cierto campo magnético, el área de sección transversal es de 0.5 m2 y el flujo es de 1500 µWb. ¿Cuál es la densidad de flujo?

![image](https://user-images.githubusercontent.com/105565683/176257131-b1c7ac69-cf22-4762-8f24-0284ef1e3a8d.png)

4. En un lugar dado, suponga que el campo magnético terrestre es de 0.6 gauss. Exprese esta densidad de flujo en teslas.

![image](https://user-images.githubusercontent.com/105565683/176257164-4d408e9c-1bb9-4070-ada3-6716e2cd87c3.png)

6. ¿Qué le sucede a la aguja de la brújula mostrada en la figura 10-9 cuando la corriente que circula a través del conductor se invierte?

![image](https://user-images.githubusercontent.com/105565683/176257196-aa24b22b-a0e4-4ebf-b013-1e7f72e7fa3c.png)

R: La aguja de la brújula gira 180°.

8. Determine la reluctancia de un material con longitud de 0.28 m y área de sección transversal de 0.08 m^2 si la permeabilidad absoluta es de 150×10^(-7) Wb/At⋅m

![image](https://user-images.githubusercontent.com/105565683/176257257-a217f59d-c3b4-4ff2-bd08-40217a31884b.png)

10. De manera característica, cuando se activa un solenoide, ¿se extiende o retrae el émbolo de imán?

R: Cuando se activa un solenoide, su émbolo se retrae.

12. Explique la secuencia de los eventos mostrados en el circuito de la figura 10-43 comenzando cuando el interruptor 1 (SW1) se cierra.

![image](https://user-images.githubusercontent.com/105565683/176257324-25e76460-225d-4d0e-a902-7457fd0870d9.png)

R: El relé conecta +9 V al pin 2 encendiendo la lámpara 2 y apagando la lámpara 1.

14. ¿Cuál es la fuerza magnetizante en el problema 9 si la longitud del núcleo es de 0.2 m? ¿Cuál es la fuerza magnetomotriz en una bobina de 50 vueltas de hilo cuando hay 3 A de corriente a través de él?

![image](https://user-images.githubusercontent.com/105565683/176257376-6637bdf3-cc02-4ec7-bac4-ab61a9b9b797.png)

16. En la figura 10-44, hay 500 vueltas. Determine

![image](https://user-images.githubusercontent.com/105565683/176257414-2e68aa59-3ea6-483f-b1b8-3f0aedfb45b9.png)

![image](https://user-images.githubusercontent.com/105565683/176257451-91295eb4-3b7e-49b8-89cc-a90d7197c0fc.png)

18. De acuerdo con la ley de Faraday, ¿qué le sucede al voltaje inducido en una bobina dada si la razón de cambio del flujo magnético se duplica?

R: El voltaje inducido se duplica cuando la tasa de cambio del flujo magnético se duplica.

20. Un campo magnético cambia a razón de 3500 x 10^-3 Wb/s. ¿Cuánto voltaje se induce en una bobina de 500 vueltas colocada en el campo magnético?

![image](https://user-images.githubusercontent.com/105565683/176739128-fe180b14-73e0-48b1-a5f9-a12b65297c14.png)

22. En la figura 10-33, ¿por qué no se induce voltaje cuando el disco no está girando?

![image](https://user-images.githubusercontent.com/105565683/176257571-37629460-9321-4c76-aa9d-de843b93b0e0.png)

El campo magnético no cambia; por lo tanto, no hay voltaje inducido.

24. Un generador de cd básico de una espira gira a 60 rev/s. ¿Cuántas veces cada segundo llega el voltaje de cd de salida a su pico (alcanza un máximo)?

![image](https://user-images.githubusercontent.com/105565683/176258917-4990658d-374e-4ced-be60-16382c560a97.png)

## VIDEO



## CONCLUSIONES

- 

## BIBLIOGRAFÍA 







