# simple-esm-usage

[![Greenkeeper badge](https://badges.greenkeeper.io/cutenode/simple-esm-usage.svg)](https://greenkeeper.io/)

This repo is an example of how to use [simple-esm](https://github.com/bnb/simple-esm), a full-ES module published to npm, with Node.js without transpilation. 

## How

Clone this repo:

```
git clone git@github.com:bnb/simple-esm-usage.git
```

Navigate to the directory:

```
cd simple-esm-usage
```

Install dependencies:

```
npm install
```

Run the "app":

```
node --experimental-modules app.js

# OR

npm start
```

If you get an error...

```
node -v
```

Make sure that returns something above Node.js v12.0.0. If it doesn't, install something above Node.js v12.0.0 💖