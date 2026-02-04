# Curso UAS RAC 100

* Gustavo Henao (Gerente)
* Gustavo Andres Perez Briceno (Capitan)

* Examenes 3 intentos

#### RPAS 
#### DRONE
#### UAS

# Introduccion

# GENERALIDADES

## Motores

### Motor Drone Brushless (Sin escobillas)

[Como Funciona](https://www.youtube.com/watch?v=3lVW9HoLZv0)

* No genera ruido
* No produce chispas
* Campo magnetico giratorio
* Bobinas de cobre (Giran al ser energizadas)
* Controlado por un Electronic Speed Control


#### ESC  (Electronic Speed Controller)
[Video](https://youtu.be/CN9m2lGGVh4?si=4ktrO1a5CJS2ZGL2)
 Dispositivo electronico que permite controlar la velocidad de un motor
 * Transforma la corriente 
 * Envia pulsos electricos a gran velocidad
 * Manejan grandes corrientes, debe estar disenados para disipar calor
 * Permite que los motores brushles sean compatos y eficientes

 #### Gimbal
 Sistema electronico y mecanico que manitiene la camara centrada y estabilizada
 
 * Existen de 1, 2 y 3 ejes, a mayor cacntidad de jejes mucho mejor
 * Los de 3 ejes ayudan a estabilizar al momento girar, porque giran en sentido contrario al giro

 #### Sistemas Seguridad
 * Anticolision
 * Evitar Obstaculos
 * Tiempo Vuelo
 * Ultra Sonido (Sonar)
 * Lidar (Sistema que calcula con laser distancias y proximidades)
 * Infrarojos
 * Vision Monocular
 * Tecnologia SLAM trabaja primero contruyendo un mapa prexeeistente de su entorno. El drone se entrena con mapas preexistentes, el drone se va entrenando de acuerdo al vuelo por el mapa

 #### Sistemas de Transmision
 * Ocusync (Transmicion entre drone y control creado por DJI) Resolucion  1080 Max, Distancia Hasta 7km  Modo transmision 2.4 y 5.8 GHz
 * Wifi SIstema de conexion inalambrica para comunicar y conectar equipos microinformaticos entre si, dentro de una red Local LAN (Bandas de frecuencia de uso libre de 2.4 y 5 GHz)
 

# Drone Phanthom
* Receptor GPS , Ubicado en la parte inferior de concha (Tapa superior), indica la posicion y altura del Quadcopter
* Para avanzar, retroceder o moverce hacia los laterales, reduce velocidad de las helices del lado opuesto, para giros en el mismo eje reduce velocidad en diagonal
* Pa Ascender acelera los 4 motores
# Despegue
* Tiempo de despegue es relativo al tiempo que se conecte a los satelites (depende de la topografia)
 * Minimo 12 satelites para volar seguro, a excepcion si el dron esta configurado indoor
 * RTH (Return to Home)
 * Las antenas de los controles deben estar paradas donde toda la antena tenga cobertura al drone (NO SOLO LA PUNTA APUNTANDO AL DRONE)
 * Conexion entre Drone y control de forma electromagnetica a 2.4 Ghz

 # 2.AERODINAMICA (3 Clases)
 Rama de mecanica de fluidos que estudia las acciones que aparecen sobre los cuerpos solidos, (aviones, drones) el fluido es un gas (aire)
 
  ## Propiedades de la Atmosfera
  * Capa gaseosa que rodea la tierra (mezcla diferentes gases)
  * Tiene propiedades de masa y peso
  * Fluido que cambia en funciona la presion
  * Compuesta 78% Nitrgeno,21% oxigeno y 1 % otros gases
  * A mayor altura menor presion dificil respirar
  * Gases vitales para la vida Oxigeno y CO2
  * Capas de la atmosfera  TROPOSFERA, ESTRATOSFERA, MESOSFERA, TERMOSFERA y EXOSFERA

La ISA (International Standard Atmosphere o Atmósfera Estándar Internacional) es un modelo de atmósfera utilizado en aviación para estandarizar las condiciones atmosféricas y calcular el rendimiento de las aeronaves.
    
   #### TROPOSFERA 
   *   De 0 a 12 km
   *   20 °C a -60°C
   *   Mayor proporcion o densidad del aires lo que permite el vuelo de Animales o aviones 
   *   Aviacion comercial
   *   Nubes tipo nimbo o fenomenos de precipitacion o metereologicos
   *   Globos Tripulados

  #### ESTRATOSFERA
  * De 12 km  a 50 km
  * de -60 °C a -5 °C
  * Aviones supersonicos y militares (Ejemplo avion concorde)
  * Se separa en 2 capas por densidad del aire, una inferior aire frio y otra superior con aire caliente
  * Capa ozono (Ozonosfera) filtra la radiacion para evitar mutaciones que producen cancer
  * Globos metereologicos MTAR TAF
  * Estrellas fugaces
  * Nubes generadas por explosiones atomicas

  #### MESOSFERA (MESO = Medio)
  * De 50km a 80km
  * De -5 °C a -95 °C
  * Ondas de radio
  * Rayos cosmicos
  * Donde arden los meteoritos para no llegar a la tierra, esto crea estrellas fugaces
  * Ondas de radio y comunicaciones, ondas televisivas
  * Ultima capa con gas para producir friccion y generar calor y transmitirolo

  #### TERMOSFERA (Termo = calor)
  * 80km a 500km
  * No transmite el calor porque no existen suficientes moleculas de gas, tampoco transmite sonido
  * -95 °C a 1000 °C
  * Nave espacial internacional ISS
  * Satelites Orbita baja
  * Auroras boreales (Porque la capa de la atmosfera es mas gruesa)
  * IONOSFERA Permite la comunicacion de ondas de radio haciendo uso de un transmisor y un receptor
  
  #### EXOSFERA (Exo = Afuera)
  * 500km y 10000 km
  * +1000 °C
  * Satelites Orbita alta (Hubble, Sputnik 1)
  * Ultima capa de la atmosfera terrestre
  * Gases ligeros Hidrogeno y helio , moleculas separada (Zona fria)

## Presion atmosferica
* Fuerza que ejerce el aire sobre la tierra
* A mayor altura menor presion (falta oxigeno porque las moleculas estan separadas difil respirar)
* A mayor temperatura menor presion
* A nivel del del mar la presion atmosferica es de 1013mbar(milibares) o 760 mmHg (pulgadas de mercurio).
* Presion (QNH) estandar a nivel del mar 29.92 Hg (Pulgadas de mercurio) o 1013 mb (milibares) referencia altimetro aviacion
* 43000ft 9-12seg,40000ft 15seg,35000ft 30seg, 3000ft 1min-2min, 28000ft 2.5min-3min, 18000ft 20-30min antes de perder conciencia (Conciencia util (TUC) tomar desiciones)
* Los pilotos usan mascaras full face para que no se escape el oxigeno durante cierto tiempo
* Max 12000 ft pies (4,26 km) de altura podemos respirar

## Perfiles Aerodinamicos (Alas, en drones helices)
  * Peril area fija o ala rotatoria
  * Superficie disenada para producir sutentacion cuando el aire pasa por el mismo
  * Cuerpo que tiene un diseno determinado para aprovechar al maximo las fuerzas que se originan por la variacion de velocidad y presion en una cooriente de aire
  * Teorema de bernouilt y tercera ley de newton
  * Se denomina perfil alar, al perfil aerodinamico a la forma del area transversal de un elemento
  * Disenos de perfiles: Antiguo, avanzado,clark Y,Flujo Laminar, Arco de circuito, Doble prisma (4 ultimos supersonicos)
  * Angulo de ataque:  Angulo agudo formado por la cuerda del ala y la direccion recta del viento al subir el morro

#### Partes Perfil aerodinamico
* Borde ataque Porcion redondeada que se proyecta dentro del flujo frl viento relativo
* Borde Salida  Parte trasera del perfil
* Cuerda Linea curvatura media Linea equidistante matiene la misma distancia entre el extrado e intrados y va desde borde ataque y borde de salida, horizontal a lo largo del area
* Extrados Arriba del ala
* Intrado borde abajo del ala
* Espesor Distancia maxima entre intrados y extrados. se mide de foma vertical

#### La Sustentacion
* Lo explican 2 terorias Teorema de Bernnoully y tercera ley de newton (Ejemplo manguera de agua)
* Un avion vuela por la diferencia de presion en las alas y en drone en las helices
* La presion del aire disminuye en un tubo ventury y la velocidad aumenta

#### Efecto Ventury
* Giovanny Batista Ventury
* Comprobo experimentalmente que al pasar por un estrechamiento las particulas del fluido aumentan su velocidad y su presion disminuye

 #### III Ley Newton
 * Toda accion tiene una reaccion (ejem salida o empuje motores)

#### FUERZAS AERODIANMICAS
* Sustentacion (Fuerza desarrollada por un perfil aerodinamico helice o ala)
* Peso (hacia abajo es relativo al peso y la gravedad) en el centro de gravedad CG, 3 Posiciones abajo, centrado y arriba
* Traccion o Empuje hacia adelante sacando el aire hacia atras (Producido por los motores) Trust
* Resistencia al avance (Generada por el fuselaje contra el Aire o viento) paralela al viento relativo
   * Resistencia inducida al levantar area de ataque o subir el morro, producida por el operador
   * Resistencia Parasita: Generada por partes que sobresalen del avion, por ejemplo tren aterrizaje
  
 #### Controles de vuelo primario
   * **Elevador - Timon profundidad**  (Cabeceo o pitch - Eje transversal o lateral) Sube o baje el morro (ubicado en la cola del avion de forma horizontal)
  *  **Rudder - Timon de direccion** (Guinada o yaw - Eje vertical) giro sobre el mismo eje (ubicado en la cola de forma vertical)
  *  **Alerones** (alabeo o roll izq o Derecha - Eje longitudinal cabeza a cola) sube un ala y baja la otra genera un viraje
  *  Flaps agrandan perfil alar, para generar mayor sustentacion a bajas velocidades

 #### Superficies control RPAS
Defecto Modo 2

   * Joistick Izqdo ↑ Despegue
   * Joistick Izqdo ↓ Aterriza
   * Joistick Izqdo ← Guinada izquierda mismo eje
   * Joistick Izqdo → Guinada derecha mismo eje
---------------------------------------------
  
   * Joistick Derecho ↑ Avance
   * Joistick Derecho ↓ Retroceso
   * Joistick Derecho ← Desplazamiento lateral izquierdo
   * Joistick Derecho → Desplazamiento lateral derecho

> [!NOTE]  
> El ESC (Electronic speed control) controla los motores para generar los movimientos mencionados anteriormente


# Indice K

# 3. METEREOLOGIA
Ciencia que estudia los fenomenos que se producen en la atmosfera a lo largo del tiempo, de forma que pueden preveer su evoluci'on

> [!NOTE] 
> El clima de una region, no es lo mismo que la metereologia

**Meteoros :** Fenomeno natural que se produce en la otmosfera, consiste en una precipitacion, una suspwncion o un deposito de pariculas liquidas o solidas, asi como una manifestacion optica o electrica
* Aurora boreal
* Arcoiris
* Niebla
* Nieve
* Granizo

**Tipos Meteoros**
* Hidrometeoros Fenomenos formados por particulas de agua en estado liquido, solido o vapor (Nieve,Lluvia,Granizo) pueden estar en el aire, precipitar ser arrastradas por el viento o depositarse sobre objetos
* Litometeroros Relacionados con particulas solidas no acuosas en la atmosfera, levantada del suelo por el viento (Bruma o calima,Smog, Tormentas de arena)
* Fotometeoros Fenomenos opticos por la reflexion, refraccion, distraccion o interferencia de la luz del sol o la luna (Arco iris, Auroras boreales)
* Electrometeoros Fenomenos visibles o audibles de la electricidad de la atmosfera (relampagos,trueno y aurora boreal)

### Caracteristicas de la atmosfera
  * Capa gaseosa que rodea la tierra
  * Compuesta 78% Nitrgeno,21% oxigeno y 1 % otros gases
  * Segun la composicion quimica de aire la atmosfera se divide en HOMOSFERA y HETEROSFERA
  * Capas de la atmosfera  TROPOSFERA, ESTRATOSFERA, MESOSFERA, TERMOSFERA y EXOSFERA

### Propiedades de la Atmosfera
* Presion (QNH) estandar a nivel del mar 29.92 Hg (Pulgadas de mercurio) o 1013 mb (milibares)
* Temperatura Atmosferica grado de calor en el aire en un lugar y momento determinado
* (International Standard Atmosphere - ISA) Atmosfera estandar internacional permite obtener valores aprox de presion y  temperatura de acuerdo a la altura en pies ft, cuando no se tiene torre de control o METAR que suminstre la informacion


> [!NOTE] 
> La Temperatura disminuye 2°C por cada 1000ft de ascenso  hasta 3600 ft (pies). Porncime se considera constante hasta 80.000 ft
> La presion disminuye 1 pulgadas de mercurio (1013 milibares) por cada 1000ft de ascenso

> [!TIP] 
> Temperatura para volar drone es maximo a 40°C porque se afecta la bateria y a los 0°C

### Intrumentos (20 Enero 2026)
* **Anemometro** Mide la velocidad del viento en km/h o m/s de acuerdo a las revoluciones del giro x minuto
* **Veleta o Manga Veleta** Sirve para medir la direccion del viento Norte,Sur,Este u Oeste, normalmente acoplada al anemometro 
* **Pluviometro** Mide volumen de agua caida (gotas) medida en L/m2 (litros x metro cuadrado) *la lluvia fina genera mas agua
* **Barometro** Mide la presion atmosferica tomando la presion atmosferica normal como referencia, si el barometro sube es senal de buen clima, ya que presiones altas son senales de tiempo seco buen clima
* **Ceilometro** Usa un laser de forma vertical hacia las nubes para determinar la altura de la base de las nubes, de acuerdo al tiempo que tarde en retornar el reflejo de la luz al ceilometro. Tambien se conoce como NEFOBASIMETRO
* **Higrometro**  Mide la humedad relativa del aire, los resultados se expresan en valores entre 0 y 100%. 0 a 30% (Clima seco) 30 % y 70 (Comfortable) , Mayor a 70 (Humedad relativa alta, mayor probabilidad de lluvia)
* **Termometro** Los de maxima registran la temperatura mas alta del dias des -31,5°C hasta 51,5°C y los de minima miden la mas baja desde -44,5°C a 40,5°C

### El clima
Efecto de la radicon solar sobre la superficie de la tierra en rotacion, es decir caracteristicas de la zona
* Polos                           => Polar
* Ariba/abajo de la linea ecuador => Templado
* Linea Ecaudor                   => Tropical

> [!NOTE]
> Clima no es lo mismo que el tiempo

### Radicion SOlar
Energia lectromagnetica emitida por el solo y se propaga a traves del del espacio, es fundamental para la vida en la tierra ya que proporciona la energia para los procesos biologico. Ademas es responsable de los patrones metereologicos de la tierra y el clima

Compuesta por luz visible que es parte del espectro Electromagnetico. Tambien incluye la radiacion UV y rayos infrarrojos IR

#### Indice KP  [Web Consulta Indice KP](https://www.spaceweatherlive.com/es/actividad-auroral/indice-kp.html) 
* Radiacion solar intensa G3 o superior satura la conexion entre drone y control, tambien recalienta bateria y descarga

### Sistemas de alta y baja presion
Los sistemas de presion tienen lineas isobaricas y determinan que tienen la misma presion en un instante dato

Las lineas isobaricas son las lineas que unen puntos de igual presion

**Formas Isobaricas Principales**
* Areas aereas de bajas presiones (B) Bajas,Depresion,Borrasca,Ciclon
Los vientos circulan en contra de las agujas del reloj (circulacion cinclonica) en el emisferio norte (HN) y al emisferio sur (HS) en el sentido del reloj (circulacion anticinclonica)
La presion disminuye desde el exterior hacia el centro, donde es minima

* Areas aereas de altas presiones (A) Anticcion (clima seco)
Los vientos circulan en sentido de las agujas del reloj  (circulacion anticinclonica) en el emisferio norte y al emisferio  sur al contrario (circulacion cinclonica)
Adoptan una configuracion bastante irregular, la presion aumenta aumenta desde el exterior hacia el centro

### Punto de Rocio y Congelacion
* **Rocio** Temperatura a la que se enfria o satura el aire para convertirse en agua
* **Congelacion** Temperatura a la que se enfria el aire para que alcance el punto de saturacion referido al hielo

### Fenomenos Atmosfericos
##### Viento
> [!NOTE]
> Viento no es lo mismo que aire

Se denomina veinto a un vector que tiene magnitud,direccion y sentido. Generalmente se define viento al aire en movimiento. 
* Se considera viento toda translacion de masas de aire en sentido horizontal.
* La translacion vertical se conoce como el termino de corriente vertical o convectiva
* El origen del viento se debe a las variaciones de temperatura y de presion que experimentan las diferentes masas de aire
* Direccion Es el punto del horizonte de donde sopla el viento. A ese punto se denomina barlovento(de donde viene) y al opuesto sotavento (a donde va)
* Intensidad Es la segunda magnitud que caracteriza el viento, pudiendose definir como la presion  (velocidad o fuerza) que ejerce sobre los objetos
* Fuerza de Coriolis (Fc) Aparece siempre que un cuerpo se mueve sobre otro que esta girando, esta fuerza hace que el veinto se desvie hacia la derecha se su trayectoria en el emisferio Norte y la izqda en el hemisferio sur
* Escala de Befaurt, Es la tabla de velocidad del viento o carta de vientos

  ###### Clases de viento
  * Laminar Es constante en direccion y velocidad
  * Turbulento Posee variaciones continuas en su instensidad y direccion, afectando todos los planos del espacio. (sube ,baj ,izqda, dcha)
  * Racheado Aparece bruscamente, aun despues de haber existido periodo de calma
  * Variable Cambia constantemente su direccion sobre un plano horizontal
  * Estable Cuando sopla con cierto caracter de constancia y se mantiene su direccion

Clases de viento respecto a su localizacion, se divide en
   * Generales Reinan en un amplio sector geografico
   * Locales soplan en una zona reducida (canon)
   * Periodicos Soplan en epocas determinadas (ejemplo agosto colombia)
   * Ocasionales No tienen caracter fijo, ni en cuanto a su duracion, pueden ser:
     Orograficos Influenciados principalmente por la orografia (topografia) del terreno. Se pueden dividir a su vez en:
       * Ascendendentes (Dia) : Que suben por la ladera de la montana (pegado al borde de la moontana) tip para bajar el drone alejar de la montana
       * Descendente (Noche): Que bajan por la ladera de la montana (pegado al borde de la moontana) tip para bajar el drone acercar a la montana
       * Brisas de Valle y montana:  Que sopla del a la montana y viceversa
       * Brisas de Mar y Tierra: Se generan del mar a la tierra y viceversa

### Composicion atmosferica, capas , ISA y condiciones

### Metereologia Basica y fenomenos atmosfericos

### Reportes Metereologia


### METAR
### Nubosidad
* FEW (nubes escasas)  1/8 a 2/8
* SCT (Nubes parcial)  3/8 a 4/8
* BKN (Nublado)        5/8 a 7/8
* OBK (Cielo cubierto) 8/8

# 4. Navegacion para RPA UAS (Inicio 29 Enero)
### Definicion
Tecnicas y procedimientos para pilotear una aeronave eficiente a su lugar de destino, asegurando la integridad de los tripulantes, pasajeros y de los que estan en tierra.

### Tipos Navegacion Aerea
#### Observada
Navegacion de contacto visual o pilotaje, se determina la posicion de la aeronave valiendose de la observacion de puntos de referencia sobre el terreno, los cuales pueden ser topograficos o culturales, para esta navegacion el cielo debe estar totalmente despejado. distancia/velocidad=tiempo

#### Estima
Deduccion o calculo se determina por la posicion de la aeronave por medio de direccion y la distancia desde una posicion anterior conocida y el tiempo segun la velocidad que se haya determinado.

#### Automatica 
* Se determina por la posicion de la aeronave por medio de computadores a bordo
* Se define un punto A y un punto B y el sistema calcula los puntos intermedios, altura etc.

#### Astronomica
Basado en los astros con respecto a la tierra

#### Intrumentos
Se determina la posicion de la aeronave por medio de la transmision de radiofaros situados en la superficie de la tierra, cuya senal es recibida a bordo de la aeronave por equipos e instrumentos especializados
* Radionavegacion

#### Satelital
Sistemas GNSS (Global Navegation Satellite Systems) es una constelacion de satelites que transmiten los rangos de senales utilizados para el posicionamiento y localizacion en cuerquier parte del globo terrestre, ya sea en tierra, mar o aire.
* Ruso (Glonass)
* USA (GPS)
* Union Europera (Galileo)
* China BeiDou (BDS)

### Coordenadas Geograficas
Punto 0  Ecuador
Latitud paralelo (Horizontal) 0 y  divide en 2 emisferios norte y sur
Longitud mediridiano de grenwich (0) de forma vertical de 0 a 180 grados (este y oeste)

### Medidas de distancia
* Milla nautica (NM) es equivalente a 1852 m (1.852km) en cartas de navegacion de aviacion se usa este tipo
* Km
* Metro m
* Milla Terrestre Milla estatutaria - Statuute Mille - sM SM = 1,609km =1609 m  (200 m mas corta que la nautica)

### Medidas de Tiempo
La tierra gira de occidentre a oriente y tarda 24H y hace un arco de 360 grados, significa que la tierra en 1h gira 15 grados
* UTC, Siempre se utiliza independiente si es vuelo nacional
* Hora Llegada se notifica en hora local a los pasajeros

### Elementos de coordenadas geograficas
### Plan Navegacion

