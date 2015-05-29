Node.js + Socket.io - Hello World Application
====================
This [Socket.IO][1] demo application was created so as to test compatibility on Smart TV browser but can be used for other purposes.

What is Socket.io?
---------------------
Socket.io is cross-browser Websocket-like API. It consist of client side and server side code. Before you start, socket.io package should be installed with npm (node package manager).

<code>
npm install socket.io
</code>

Its client side library is already included at 'client/js/socket.io.min.js' but current version can be found at installed socket.io module with following path: 'node_modules/socket.io/node_modules/socket.io-client/dist/socket.io.min.js' if you need it. 


How to run?
---------------------
Following command starts the app.js

<code>
node app.js
</code>

Now index.html page can reach  the server side. The red box can be moved by pressing arrow keys and it will be updated  on every clients window.

[1]: http://socket.io/        "Socket.IO"

## Licence

Released under [the MIT license](LICENSE).
