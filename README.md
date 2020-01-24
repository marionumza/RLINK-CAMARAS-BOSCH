# Proyecto Rlink - Camaras BOSCH con intercomunicador mas botón de pánico

## Alcance del proyecto

## Audio entre la Cámara y el Operator Client (Colocar intercomunicador entre la camara y el operator client)
#### Importante
  - [x] Escuchar Audio desde la Cámara hacia la PC donde corre el operator client
  - [ ] Escuchar Audio desde el microfono de la PC donde corre el operator client hacia la Cámara
#### Necesario
  - [ ] Debe funcionar Full-duplex

## Botón de Pánico con led indicador y envio de señal a plataforma Rlink
#### Importante
  - [ ] Configurar un evento de alarma en el BVMS que indique que se presionó el botón
  - [ ] El Botón debe estar situado en la cada del interdomunicador
  - [ ] Debe tener un led indicador de que se presionó el botón
  - [ ] Debe enviar una señal via http a la plataforma Rlink de que se presionó el botón como evento de alarma
#### Necesario
  - [ ] Debe enviar un correo electrónico de que se presionó el botón como evento de alarma
