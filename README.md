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

 # AERODINAMICA
 Rama de mecanica de fluidos que estudia las acciones que aparecen sobre los cuerpos solidos, (aviones, drones) el fluido es un gas (aire)  

 
  ## Propiedades de la Atmosfera
  * Capa gaseosa que rodea la tierra (mezcla diferentes gases)
  * Tiene propiedades de masa y peso
  * Fluido que ccambia en funciona la presion
  * Compuesta 78 Nitrgeno,21% oxigeno y 1 % otros gases
  * A mayor altura menor presion dificil respirar
  * Capas de la atmosfera  TROPOSFERA, ESTRATOSFERA, MESOSFERA, TERMOSFERA y EXOSFERA
    
   ### TROPOSFERA 
   * De 0 a 12 km y se encuentra
   *  20 Grados
   *   viacion comercial
   *   Nubes tipo nimbo o fenomenos de precipitacion o metereologicos
   *   Globos Tripulados

  #### ESTRATOSFERA
  * De 12 km a 50 km
  * de -60 a -5 grados
  * Aviones supersonicos o  militares
  * Capa ozono
  * Globos metereologicos
  * Estrellas fugaces
  * Nubes generadas por explosiones atomicas

  #### MESOSFERA
  * De 50km a 80km
  * De -5 a -95 grados
  * Ondas de radio
  * Rayos cosmicos

  #### TERMOSFERA
  * Nave espacial internacional ISS
  * Auroras boreales (Porque la capa de la atmosfera es mas gruesa)
  
  #### EXOSFERA
  * Satelites

## Presion atmosferica
* Fuerza que ejerce el aire sobre la tierra
* A mayor altura menor presion
* A nivel del del mar la presion atmosferica es de 1013 mbar o 760 mm Hg.
* 45 mil km hasta 10 seg antes de perder conciencia (Conciencia util)
* Los pilotos usan mascaras full face para que no se escape el oxigeno durante cierto teimpo
    
  ## Perfiles Aerodinamicos (Alas, en drones helices)
  * Peril area fija o ala rotatoria
  * Superficie disenada para producir sutentacion cuando el aire pasa por el mismo
  * Cuerpo que tiene un diseno determinado para aprovechar al maximo las fuerzas que se originan por la variacion de velocidad
  * Teorema de bernouilt y tercera ley de newton
  * Se denomina perfil alar, al perfil aerodinamico a la forma del area transversal de un elemento
  * Disenos de perfiles: Antiguo, avanzado,clark Y,Flujo Laminar, Arco de circuito, Doble prisma (4 ultimos supersonicos)

#### Partes Perfil aerodinamico
* Borde ataque Porcion redondeada que se proyecta dentro del flujo frl viento relativo
* Borde Salida  Parte trasera del perfil
* Linea curvatura media Linea equidistante matiene la misma distancia entre el extrado e intrados y va desde borde ataque y borde de salida, horizontal a lo largo del area
* Extrados Arriba del ala
* Intrado borde abajo del ala
* Espesor Distancia maxima entre intrados y extrados. se mide de foma vertical

#### La Sustentacion
* Lo explican 2 terorias Teorema de Bernnoully y tercera ley de newton (Ejemplo manguera de agua)
* Un avion vuela por la diferencia de presion en las alas y en drone en las helices
* La presion del aire disminuye en un tubo ventury

#### Efecto Ventury
* Giovanny Batista Ventury
* Comprobo experimentalmente que al pasar por un estrechamiento las particulas del fluido aumentan su velocidad y su presion disminuye

## FUERZAS AERODIANMICAS
* Sustentacion (Fuerza desarrollada por un perfil aerodinamico helice)
* Peso (hacia abajo es relativo al peso) en el centro de gravedad CG, 3 Posiciones abajo, centrado y arriba
* Empuje o Traccion(Producido por los motores) Trust
* Resistencia (Aire o viento) paralela al viento relativo
   * Resistencia inducida al levantar area de ataque o subir el morro, producida por el operador
   * Resistenci Parasita: Generada por partes que sobresalen del avion, por ejemplo tren aterrizaje

# Indice K

# METEREOLOGIA

## INDICE KP


## METAR
### Nubosidad
* FEW (nubes escasas)  1/8 a 2/8
* SCT (Nubes parcial)  3/8 a 4/8
* BKN (Nublado)        5/8 a 7/8
* OBK (Cielo cubierto) 8/8

