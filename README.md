# Electron App Domino
Aplicacion para gestion de torneos de domino desarrollada en Angular y compilada en Electron Js lista para usar y transformarla en una app de escritorio.

Instalador Windows: https://github.com/Jucema89/AppDominoElectron/tree/main/dist 

![](https://i.imgur.com/PhMAQVO.png)

## Funcionalidades
- Registro y login
- CRUD de Jugadores, jueces y torneos
- Gestion de Parejas y Equipos por torneo
- Ranking por torneo y Ranking Nacional
- Gestion de Puntos segun ubicación (local - visitante)
- Impresion de formato de registro de mesas en juego y puntos
- Envio de Mensajes a jugadores (Local y por SMTP)
- Base de datos local Sincronizada a servidor remoto

## Como usarla
Video de presentacion y muestra de funcionalidades de la app.
[![ScreenShot](https://i.imgur.com/ca3s8Jm.png)](http://youtu.be/vt5fpE0bzSY)


## Vistas Previas

![](https://i.imgur.com/hvFZl7l.png)
![](https://i.imgur.com/9kfkGQ8.png)
![](https://i.imgur.com/5m7g9LI.png)

## Clonar y Compilar

```bash
# Clona el repos
git clone https://github.com/Jucema89/AppDominoElectron
# Ingresa al repositorio
cd /carpeta-repositorio-master
# Instala dependencias
npm install
# Run the app
npm run main.js
```

## Para tener presente

- En esta app use Electron Js su quick start; una solucion para crear apps multiplataforma rapidamente:  https://github.com/electron/electron-quick-start
- El Codigo dentro de la carpeta app es la distribucion compilada que genera Angular, no es el core de la app en si.
- Las Bases de datos sincronizadas son CouchDB (BD remota) & PouchDb (BD Local) https://docs.couchdb.org/en/stable/  https://pouchdb.com/guides/
- Para produccion desarrolle un servidor de correos con NodeJs usando: https://nodemailer.com/about/

Gracias por leer, Exito en tu codigo! :smile:
