# Examen 1
Instituto Tecnológico de Costa Rica. 
Escuela de Ingeniería en Computación. 
Redes - IC-7602.
Grupo 2. 
Profesor: Gerardo Nereo Campos Araya
Estudiante: Daniel Araya Sambucci - 2020207809
Fecha de entrega: 11/11/23

## Pregunta 1

Cuando se de la colonización de Namiapí, esta tiene distintos factores vitales a tomar en cuenta para poder establecer toda la estructura de comunicaciones, que a su vez permita comunicarse con la Tierra. Al estar en las etapas iniciales de la colonización, una propuesta viable que permita cumplir esto, realizando un uso eficiente de los recursos y pueda ser establecida en menos de dos años, tiene que ser una propuesta inalámbrica, ya que un medio cableado tomaría mucho más tiempo de ser montado todo. Aprovechando el enjambre de satélites que serán desplegados en la órbita geoestracionaria sobre el ecuador de Solaria, se puede optar por el sistema ALOHA ranurado. 

ALOHA ranurado tiene una taza de 37% de ranuras vacías, 37% de éxitos y 26% de colisiones al realizar transmisiones. Al no ser de importancia la velocidad y se priorice la existencia de la comunicación, el garantizar esta taza de éxitos permitirá que las personas de Namiapí puedan comunicarse. Como se están tomando en cuenta que serán las primeras etapas de colonización, entonces habrá una baja densidad de tráfico, lo que permite ver el ALOHA ranurado como una opción viable y eficiente, ya que la probabilidad de que haya colisiones será más baja. 

Conforme Namiapí se vaya desarrollando, podrán realizar una transición a tecnologías de comunicación más avanzadas y establecer medios de transmisión cableados en la zona, pero esto tomará más tiempo, por lo que ALOHA ranurado cubrirá de forma correcta las necesidades de comunicación de la colonia en estos primeros años de forma flexible y simple. 

## Pregunta 2

* Desde un punto de vista técnico, ¿Por qué razón se presentó este incidente?

Este incidente se presentó debido a que, los niños sin haberse dado cuenta, estaban transmitiendo las canciones por medio del Radio Walkie Takie a la misma frecuencia que la radio del operador del aeropuerto transmitía. Entonces ocurrió que la frecuencia los niños interfería. Ellos empezaron a escuchar la frecuencia del operador debido a que, conforme se iban alejando, las señales chocaron. Como la señal del operador tenía más potencia, entonces esta destruyó la señal de los niños y siguió hasta sus Walkie Talkie. Es por esto que lograron escuchar la voz del operador. 

* ¿Por qué es necesaria la regulación de uso de frecuencias?

La regulación del uso de frecuencias se realiza para que no se den casos como este donde se da una interferencia perjudicial. Las frecuencias tienen múltiples usos en las comunicaciones, donde entran servicios críticos como pueden ser los operadores de un aereopuerto, donde si las comunicaciones son interrumpidas, puede ocurrir un accidente que atente contra la vida de las personas. Entonces, cuando se regula el uso de las frecuencias, se asegura que cada banda en el espectro electromagnético tenga su propio espacio, minimizando las interferencias y garantizando tanto la fiabilidad como la seguridad de las comunicaciones. Ejemplos de donde esto aplica pueden ser las Radio Bands (ITU), donde hay distintos tipos de banda que operan sobre ciertos intervalos de frecuencias, que a su vez tienen determinadas longitudes y usos específicos. Por ejemplo, el uso en AM corresponde a una banda Medium Frequency (MF).

* ¿Por qué se debe certificar los dispositivos y limitar su frecuencia de transmisión?

Al certificar los dispositivos y limitar su frecuencia de transmisión, esto es una medida para poder garantizar que trabajen sobre los intervalos de frecuencia que estos deben de trabajar, y de esta forma no interfieran con otros tipos de servicios. Entonces, al limitarlos, se puede certificar estos dispositivos para que se mantengan dentro de estos límites y garanticen estándares de calidad y seguridad y, de esta forma, se pueda prevenir problemas de comunicación y posibles riesgos de seguridad.

* ¿Por qué la privacidad va de la mano con las redes? En especial en medios inalámbricos.

La privacidad se considera un factor clave en las redes, ya que de las principales características que se busca cuidar en este área es la integridad, privacidad y seguridad de los datos que se transmiten. Cuando hablamos de medios inalámbricos, la información se transmite por medio de señales en el aire. Esta información ppuede ser interceptada con mayor facilidad que si hablamos de un medio cableado. Entonces, paquetes podrían ser atrapados por un atacante y abiertos, leyendo de esta forma los bytes que contienen. La información entonces podría ser interpretada y por ende robada. Este es el motivo por el cual se implementan protocoolos de seguridad en redes que buscan proteger la privacidad de los usuarios.

* Suponiendo que se encuentran en el año 1993, ¿Qué solución darían para evitar este problema?

En 1993, las tecnologías de comunicación no se encontraban tan avanzadas como en la actualidad, por lo que una solución viable, asumiendo que no existieran leyes que regularan de forma correcta el uso de gran parte del espectro electromagnético, sería el designar un rango de frecuencias restrigido para el uso civil que pudiera contener frecuencias para el uso de Walkie Talkies. De esta forma, se previene que se invandan los rangos de frecuencias de los operadores del aeropuerto y se evita un posible accidente. 

## Pregunta 3

* ¿Por qué razón overprovisioning de hardware no es una herramienta efectiva para lidiar con la
congestión? (10 pts)

El overprovisioning de hardware si bien, puede ser una solución a corto plazo, esta no es la ideal ya que la congestión de la red puede variar muchísimo. Esta no es efectiva a largo plazo ya que el tráfico tiene a crecer y la capacidad actual para mantener la red puede verse superada rápidamente. El estar constantemente brindando mayor capacidad de hardware puede resultar muy costoso, ya que se usa hardware muy potente para las situaciones donde la red tiene un tráfico normal y no elevado. Lo ideal es que la capacidad de la red fuera dinámica en base al nivel de tráfico que se esté dando en el momento. Al ser un hardware fijo, este es poco flexible y no permite adaptarse a los patrnes de tráfico que están constantemente cambiando, lo que resulta en un desperdicio de recursos.

* ¿Como el uso de Inteligencia Artificial (IA) y el análisis de tráfico de capa de red, puede ayudar a
tomar decisiones más adecuadas para asegurar un QoS en la red, será posible implementar
prioridad de tráfico basado en IA? (5 pts)

El analizar el tráfico en las capas de red es vital para poder realizar un manejo correcto de la congestión. En el caso de que haya una ruta en la que el tiempo de llegada de los paquetes sea mayor ya sea por distancia o bien por que un router tiene una alta demanda, lo que aumenta el tiempo con el que procesa los paquetes, es un problema que se puede solucionar mediante el uso de métricas. Entonces, analizando los distintos caminos en base a estas métricas, se puede optar por tomar una ruta u otra. No obstante, estas métricas no son fijas y pueden variar con los distintos flujos de tráfico que se den en la red. Es por esto que, para mejorar el QoS en la red, se puede implementar prioridad de tráfico basado en IA. Se aprovechan las virtudes de las inteligencias artificiales para poder reconocer patrones de tráfico en la red y actualizar las métricas en base a esto. Entonces las IA se encargarían de setear un valor u otro a las métricas, permitiendo que los paquetes siempre viajen por el camino más óptimo, hasta llegar a su destino.

## Pregunta 4

* Explique en detalle, ¿Cómo afectan los saltos entre routers el round-trip time de un paquete entre 
dos puntos de Internet?, ¿Cómo afecta el MTU este tiempo y como nos beneficia conocer el 
mínimo MTU? Discuta las implicaciones de clientes, servidores y dispositivos de red intermedios 
(routers) que participan en la comunicación. (10 pts)

Cada salto que se da en la red entre distintos routers agrega una pequeña demora, ya que se tiene que procesar la información en el router y determinar a donde se debe enviar el paquete. Mientras más saltos se acumulen esto significa que el round-trip time será mayor. Mientras más alto es un round-trip time, esto afectara a la calidad del servicio que se le puede ofrecer a un cliente. Es por esto que se define una cantidad máxima de saltos y si el paquete las supera, este se descarta. Esto evita que se queden dando vueltas indefinidamente por la red. También se puede interpretar esto como que no hay un camino óptimo para que los paquetes viajen entre los dos puntos. Por ejemplo si se define que la cantidad de saltos sea de 30 ya que este es el estándar de calidad de servicio definido, entonces cuando supere esto ya el paquete no seguirá viajando más. 

El MTU (Maximum Transfer Units) es el tamaño máximo que puede tener un paquete al ser enviado por la red. Este se define tomando en cuenta el paquete más grande que puede manejar un router. Esto permite averiguar la velocidad a la que se puede conectar a esos routers. Conocer el mínimo MTU permite poder evitar la fragmentación de paquetes, ya que se envían paquetes del tamaño que pueden manejar los routers y de esta forma ellos no tienen que perder tiempo de procesamiento fragmentando los paquetes. Esto reduce el round-trip time. Entonces, los paquetes se definen de cierto tamaño en el punto de salida y son procesados por cada router. Si el router puede procesar un paquete de mayor tamaño, esto no importa ya que se toma en cuenta el menor tamaño que pueda procesar alguno de los routers en el camino designado. Para averiguar esto, antes de empezar la conexión, se envía un paquete satélite lo más pequeño posible. Al ser tan pequeño ningún router lo despedazará. Entonces llega a cada router, guarda el tiempo que duró y el tamaño. Va acumulando el tiempo y el tamaño más pequeño. Esto permite configurar los timeouts y asegura que nadie en la red parta los paquetes.

* ¿Cómo el uso de caches regionales (cerca del usuario) pueden ayudar a reducir la cantidad de
saltos, reducir el round-trip time y hacer un uso eficiente del ancho de banda? Discuta las
implicaciones para clientes, servidores y dispositivos de red intermedios. (5 pts)

El uso de caches regionales puede permitir que, al leer esta cache, se pueda saber cuales son los caminos óptimos que han sido usados de forma frecuente para llegar a cierto punto. Esto permite que no se tenga que realizar un análisis de las rutas en la red y se pueda optar por tomar este camino directamente, al ser el que mejor tiempo da para llegar al destino, dando un mayor equilibrio para el tráfico entre routers. Esto implica una menor cantidad de saltos lo que reduce el round-trip time. Además, al estar leyendo contenido de ubicaciones que se encuentran de forma cercana, deben viajar menos datos en la red para poder averiguar la información necesaria para enviar los paquetes, lo que reduce la cantidad de datos en tráfico y permite un uso eficiente del ancho de banda. Esto permite a los servidores tener una menor carga de trabajo. Así mismo, esto implica un beneficio para los clientes, ya que pueden tener tiempos de carga más rápidos y una mejor calidad de su servicio.