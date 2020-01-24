# Proyecto Rlink - Camaras BOSCH con intercomunicador mas botón de pánico

## Alcance del proyecto

1. ###Rack con Servidor BVMS mas Monitor, teclado y Mouse, con swich y router para funcionamiento local
#### Importante
  - [x] Servidor con Windows Server 2012 que albergue el programa BVMS (necesario para el disco iSCSI)
  
#### Necesario
  - [x] Acceso remoto a traves del protocolo RDP al servidor
#### Deseable
  - [ ] Operator Client corriendo en el servidor (aunque corre, no puede desplegar los trazos que dibujan la cámara bosh, ya que se necesita la experiencia de visualizacion de windows de escritorio y no de windows server, ademas no hay driver de video para este tipo de equipo)

### Audio entre la Cámara y el Operator Client (Colocar intercomunicador entre la camara y el operator client)
#### Importante
  - [x] Escuchar Audio desde la Cámara hacia la PC donde corre el operator client
  - [x] Escuchar Audio desde el microfono de la PC donde corre el operator client hacia la Cámara
#### Necesario
  - [x] Debe funcionar Full-duplex

### Botón de Pánico con led indicador y envio de señal a plataforma Rlink
#### Importante
  - [x] Configurar un evento de alarma en el BVMS que indique que se presionó el botón
  - [x] El Botón debe estar situado en la cada del interdomunicador
  - [x] Debe tener un led indicador de que se presionó el botón
  - [x] Debe enviar una señal via http a la plataforma Rlink de que se presionó el botón como evento de alarma
#### Necesario
  - [x] Debe enviar un correo electrónico de que se presionó el botón como evento de alarma
  
## Enlaces Importantes
- [Google Drive](https://drive.google.com/drive/folders/1FrOAyKeX065JWgvLuxZXtvzO_pDl1mcq?usp=sharing) 
