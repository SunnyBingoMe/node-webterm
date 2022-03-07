terminal.js-webshell
====================

this is a demo application for [child_pty](https://github.com/Gottox/child_pty) and [terminal.js](https://github.com/Gottox/terminal.js).

running this demo
-----------------

```
cd node-webterm
npm install
npm start
```

Then point your browser to http://127.0.0.1:3000

![Demo](https://raw.githubusercontent.com/Gottox/terminal.js-webshell/master/demo.gif)

To share a terminal ([ref](https://www.gabriel.urdhr.fr/2016/10/18/terminal-sharing/)):

```sh
script -f ~/script.log # in the terminal to be shared
```

Then change the input to:
```
"login": "tail -f ~/script.log",
```

**WARN**: all content is sent via pure HTTP (plain text).
