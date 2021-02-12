# Plan Of Action

- Initialize our NodeJS Project <DONE>
- Initialize our first view <DONE>
- Create a Room ID <DONE>
- Add the ability to view our own Video <DONE>
- Add ability to allows others to stream their Video <DONE>
- Add styling <DONE>
- Add ability to create messages <DONE>
- Add mute button <DONE>
- Add Stop Video button <DONE>

### commander

1.  npm -init -y
2.  npm i express
3.  npm i nodemon
4.  npm i ejs
5.  npm i uuid
6.  npm i socket.io
7.  npm i peer
8.  npm i -g heroku

- server start => nodemon server.js

### deploy

- heroku create
- git push heroku master (단 .git이 있는 가장 상위에서 해야함.)
- heroku ps:scale web=1
- heroku open
