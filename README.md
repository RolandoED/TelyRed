Primera Clase Redes

http://ccna-v5.net/cisco-packet-tracer-7-0-32bit-64bit-windows-free-download.html

Las organizaciones que entran en el examen:

-	ISO
-	IEEE
-	IETF
-	ITU

**Primera red ARPANET creada por ARPA en US**


Pregunta de Examen quien inicio el ARPANET y con que proposito **agregar proposito**, empezo en la costa oeste 
Stanford UCLA

Modelos de Referencia vienen a dar solucion a la falta de comunicacion entre computadoras
Diseñar el hardware por modulos y el software por Capas

Se programa por modulos para facilitar la depuracion de software

1978 creado por la ISO el modelo OSI

Descomponer la cadena de transmision de diversos modulos cuya interfaz con los adyacentes esté estandarizada


Modelos Basico de referencia y uno de estados concretos

###De Examen
consta de 7 capas Modelo OSI
de abajo hacia arriva 


L7 Capa de Aplicación
L6 Capa de Presentación
L5 Capa de sesión
L4 Capa de transporte
L3 Capa de Red
L2 Capa Enlace de Datos
L1 Capa fìsica


##L1 Capa fìsica
Conversion (transfiere y recibe) de los datos en 1's y 0's se realiza en la capa fisica 
Impulsos Electricos, Electromagneticos o Fibra Optica


##L2 Capa Enlace de Datos
Switches se encarga de recibir el flujo de bits que recibe la capa física y lo convierte en tramas ,
proporciona control de errores para evitar tramas perdidas o dañadas.
Control de Flujos.

Tiene 2 Subcapas

	Control logico de enlace LLC: define como se transfieresn los datos sobre el medio fisico
	Control de accecso al medio MAC: actua como controladora del hardware subyacente (el adaptador de red)

##L3 Capa de Red
Direccionamiento logico, enrutamiento por medio de algoritmos de enrutamiento.
Asigna IP busca la mejor ruta.
Se divide en 2:
	Transporte : encapsula.
	Conmutacion : enruta.

##L4 Capa de Transporte:
Garantiza Fiabilidad del Servicio.
Describe la calidad y naturaleza del envio de datos

##L5 Capa de sesión
Control del dialogo: a quien le toca hablar por sesión.
Administración del Token: indica cual es el que puede hablar.
Sincronización: saber cuanta info se ha transmitido y cuanta falta 
en caso de que se  haya caido la conexion

##L6 Capa de Presentación

Cuando se forman archivos textuales con los datos recibidos.
Prepara lo que la capa L7 va a presentar al usuario

##L7 Capa de Aplicación
Terminales Remotas.
Se la presenta al usuario.
Navegadores. Presenta algo lógico.

---


Proceso de Compsosición de los Datos

###PDU-> Physical Data Unit

Cada capa Posee un PDU específico

L7 - |
L6 - | - Datos
L5 - |
L4 - Segmento
L3 - Paquete
L2 - Trama
L1 - Bit

Modelo OSI Granula los datos, descomponiendolos de arriba a abajo 
o conformandolos de abajo hasta arriba.

#corregir con presentacion.

L7 - |
L6 - | 		D
L5 - |
L4 - Segmento	D H headeer de capa 4
L3 - Paquete	D H H IP receptor emitor
L2 - Trama	D H1 H2 H3 T Agrega un checksum si no es igual se restransmite Mac que envia y recibe
L1 - Bit	Bits 1001010101010011


#Dibuje el modelo de referencia OSI describa cada una de sus capas y liste los PDU para cada capa 
trama datos bits paquete

#ver imagen de que traer el OSI

###L7	TELNET, FTP , SSH, HTTP/S, SMTP
L6	JPEG, MOV, TXT
L5	NFS, SQL
###L4	TCP UDP
L3	IP
L2	PPP
L1	Ninguno

En H3 los que pueden salir en el examen , el resto tamb

#Examen
Beneficios:

Facilidad de comprension.

Dividir en partes pequeñas reduce complejidad.

Facilidad en cambios en red ya que modula.

Interoperabilidad.

Facilita diseño modular.

---

Interaccion entre las capas:

Uso de Headers entre capas.



















