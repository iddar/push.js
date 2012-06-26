push.js
=======

Simple juego multijugador en el que el ganador es quien `pulse el boton mas rápida mente`.
Puedes ir probando los avances en el siguiente enlace [Jugar!](http://pushjs.herokuapp.com/)

Información tecnica:
---------------------

Herramientas utilizadas:
- Node.js   
- HTML5
- CSS3
- Javascript
- JQuery 1.7.2
- Socket.io
- Git/GitHub (Control de versiones)
- Cloud9 (IDE)
- Heroku (Distribución)

###Pueba de insercion de codigo
~~~~~~ js
io.sockets.on('connection', function (socket) {
    // echo the message
    socket.on('message', function (data) {
    console.info(data);
    socket.send("[ECHO] "+data);
    });
});
~~~~~

Notas del Autor:
-------------------------
Creado con la finalidad de aprender node.js 

    Fecha de inicio Lun, 25 jun del 2012