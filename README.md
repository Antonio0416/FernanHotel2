# MANUAL DE USUARIO FERNANHOTEL
Practica Obligatoria Tema 2. Programa de un hotel en Martos realizada por Antonio y Manuel José.

## Índice
1. [Comenzando](#comenzando)
2. [Requisitos Mínimos](#requisitos)
3. [Instalación](#Instalación)
4. [Ejecucion](#ejecucion)
5. [Colaboradores](#colaboradores)

## 🔰​ Comenzando 🔰​

_Estas instrucciones te permitirán obtener una copia del proyecto en funcionamiento en tu máquina local para propósitos de desarrollo y pruebas._

## ✔ Requisitos Mínimos ✔

_Debes tener instalado Windows 10 o Windows 11 (x64) y la siguiente versión de java
**Java SE Development Kit 19.0.2**, para descargarla acceda al siguiente enlace_

```
https://download.oracle.com/java/19/archive/jdk-19.0.2_windows-x64_bin.exe
```

Para comprobar la version de java que tenemos instalada en nuestro equipo, escribimos "cmd" en el buscador de Windows. Después de ejecutarlo, escribimos "java-version" en la terminal.

_A continuación, debes tener el siguiente path en tus variables de entorno del sistema, si no sabes mirarlo en el buscador de Windows "Editar las variables del entorno" y por último añadir la siguiente línea al path si no la tienes:_

```
C:\Program Files\Java\jdk-19.0.2\bin
```

## 🔧 Instalación 🔧

_Una vez cumplas los requisitos, debes descargarte nuestro repositorio, pulsando en el siguiente botón:_

![image](https://github.com/Antonio0416/FernanHotel2/assets/113978105/19086323-b585-41a7-9b00-154258f6b5d8)

_Ahora con el proyecto en tu equipo situandolo en el disco C: solo tendrás que descomprimirlo con permisos de administrador para pasar al siguiente apartado_

## ⚙️ Ejecución ⚙️
_Con el programa descomprimido, se va a encontrar una carpeta **practicAtnonioManu** y un ejecutable llamado **FernanHotelApp**. Para acceder al programa primero debe cumplir los requisitos y después puede abrir la aplicación._

_Al abrir la aplicación se encontrará con la siguiente pantalla:_

![image](https://github.com/Antonio0416/FernanHotel2/assets/150932456/8f82b801-36c9-4ad4-8610-1352b46da4cd)
Encontrarás un menú con las siguientes opciones:
  1. Ver el estado de ocupación de las habitaciones.
  2. Reservar una habitación.
  3. Realizar checkout de una habitación.
  4. Menú de administrador

#### Ver el estado de ocupación de las habitaciones
En este apartado se muestra en distintos bloques el estado de las habitaciones del hotel. Nos muestra el nombre del cliente, número de confirmación, fecha y tipo de habitación.

![image](https://github.com/Antonio0416/FernanHotel2/assets/150932456/dcb8b09f-ec08-44cb-8a26-aa28191b0c0a)

![image](https://github.com/Antonio0416/FernanHotel2/assets/150932456/a9c3410c-9359-4239-aedc-c3f92035edd1)

#### Reservar una habitación.
Consiste en rellenar el nombre del cliente, así como su DNI sin letra y número de huespedes (1 o 2).
También te da la opción de introducir la palabra salir para cancelar el proceso de la reserva.

![image](https://github.com/Antonio0416/FernanHotel2/assets/150932456/97bf064e-3810-4ed8-aeab-62c6058f2536)

#### Realizar checkout de una habitación
Esta opción nos genera la factura con el precio total de la estancia en el hotel. Para ello nos pide que introduzcamos el nombre del cliente, número de confirmación (DNI) y la fecha de salida.
También te da la opción de introducir la palabra salir para cancelar el proceso de la reserva.

![image](https://github.com/Antonio0416/FernanHotel2/assets/150932456/a9506052-59bc-4bb8-8080-56366fb5f27c)

Una vez generada la factura, el cliente deberá introducir la cantidad del importe para realizar el pago. El programa le calcula el dinero restante y muestra por pantalla la menor cantidad posible y tipo de billetes/monedas que se le devolverá.

![image](https://github.com/Antonio0416/FernanHotel2/assets/150932456/6c329f28-6f0e-4dc9-9a22-e1975c0b30a1)

#### Menú de administrador
Al seleccionar está opción, nos llevará a un inicio de sesión para el menú de administrador. El programa nos pedirá el usuario y contraseña de administrador.
Una vez introducido dichos datos, nos mostrará otro pequeño menú con distintas opciones que podremos ejectuar como administrador.
También te da la opción de introducir la palabra salir para cancelar el proceso de la reserva.

![image](https://github.com/Antonio0416/FernanHotel2/assets/150932456/7a061a15-dcf4-4708-923b-19dac6ecca8c)

Encontrarás un menú con las siguientes opciones:
  1. Consultar los ingresos totales y número de reseravas finalizadas
  2. Consultar las monedas restantes para el cambio
  3. Volver al menú principal
  4. Apagar el software

#### Consultar los ingresos totales y número de reseravas finalizadas
Nos muestra los ingresos totales del hotel así como el número de reservas finalizadas.

![image](https://github.com/Antonio0416/FernanHotel2/assets/150932456/aedf82eb-2c48-428c-ad47-29a092c5411b)

#### Consultar las monedas restantes para el cambio
Muestra por pantalla la cantidad y tipos de billetes/monedas del hotel disponibles para devolver al realizar un checkout.

![image](https://github.com/Antonio0416/FernanHotel2/assets/150932456/a13ca983-568d-44da-a72a-6722decd1ca2)

#### Volver al menú principal
Esta opción nos permite salir del menú de administrador y volver al menú principal.

![image](https://github.com/Antonio0416/FernanHotel2/assets/150932456/9025d28b-4798-4d25-978b-e454212702fe)

#### Apagar el software
Esta última opción apaga por completo el software del hotel, es decir, apaga el programa por completo. Nos preguntará que confirmemos si deseamos apagar el sistema, en caso de no desear dicha opción te llevará de nuevo al menú de administrador.

![image](https://github.com/Antonio0416/FernanHotel2/assets/150932456/c6a03a3d-a4a0-45b7-89ba-f11d81a8a572)

## 📝 Colaboradores 📝

- Antonio Cámara Cámara - https://github.com/Antonio0416
- Manuel José Liebana Vilches - https://github.com/ManuelJose05
