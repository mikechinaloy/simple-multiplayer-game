# simple-multiplayer-game

A simple multiplayer game that combines two classic games: Pong and Asteroids. Technologies used:

[NodeJS](https://nodejs.org/en/) /
[Socket.io](http://socket.io/) /
[Phaser.io](http://phaser.io/) /
[Supervisord](http://supervisord.org/)

===================
Running locally
===================

To run locally you must install nodejs e.g. ``` yum install nodejs```  and update update the following files:

``` 
public/index.html
public/js/game.js 
```

You should change the IP addresses located in these so that they match your local IP.

Once you have done this you can simply run: 

``` npm install ``` 

followed by: 

``` npm start ```

===================
Running in the cloud
===================

Hosted on [Google Compute Engine](https://cloud.google.com/compute/)

http://104.155.19.241:8000/
