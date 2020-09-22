## [Check the JS code](https://github.com/andrerferrer/445-night-mode/tree/master/src)

## Usage

First clone this repository to your laptop. You must have Node (> v4) and [yarn](https://yarnpkg.com/lang/en/docs/install/) installed.

```bash
cd ~/code/$USER
git clone git@github.com:andrerferrer/445-night-mode.git
cd 445-night-mode
yarn install
stt # Open this folder in Sublime Text
webpack-dev-server # run the server on localhost:8080
```


Make sure you have `./node_modules/.bin` in your `$PATH`! This way you can run this:

```bash
eslint lib
webpack-dev-server
```

Once a file has been updated in Sublime, you can run it with:

```bash
node lib/01_types.js
```
