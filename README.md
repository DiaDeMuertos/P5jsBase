# P5 Base Project

## Content

- Tools
- Structure
- Run
- Links

## Tools

Install P5js mananer.

```
$ npm install p5-manager -g
```

Create a P5js project

```
$ p5 generate --bundle src
```

# Structure

```
.
├── package.json
├── package-lock.json
├── README.md
└── src
    ├── index.html
    ├── libraries
    │   ├── p5.dom.js
    │   ├── p5.js
    │   └── p5.sound.js
    └── sketch.js
```

# Run

We add the call to http-server.

```
"scripts": {
  ...
  "start:http-server": "http-server src",
  "start:live-server": "live-server src"
},
```

Now we can just run the start script.

With http-server.

```
$ npm start:http-server
```

With live-server.

```
$ npm start:live-server
```

## Links

- [npm](https://www.npmjs.com/package/p5-manager) - p5-manager
