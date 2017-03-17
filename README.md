[![version](https://img.shields.io/badge/version-1.0.0-green.svg?style=flat-square)](https://github.com/pierrechls/tweetscape) [![Build status](https://img.shields.io/badge/build-passing-green.svg?style=flat-square)](https://img.shields.io/badge/build-passing-green.svg?style=flat-square) [![front-end-framework](https://img.shields.io/badge/front--end%20framework-vue.js-lightgrey.svg?style=flat-square)](http://vuejs.org/) [![vr-framework](https://img.shields.io/badge/vr%20framework-a--frame-lightgrey.svg?style=flat-square)](https://aframe.io/) [![js-standard-style](https://img.shields.io/badge/code_style-standard-lightgrey.svg?style=flat-square)](http://standardjs.com/)

<h1 align="center" style="text:align:center;">T W E E T S C A P E</h1>

<h6 align="center" style="text:align:center;">A WebVR experience displaying tweets along a 3D timeline</h6>

<p align="center" style="text:align:center;">
  <img src="http://cdn.rawgit.com/pierrechls/tweetscape/master/static/preview.gif" style="width:100%;">
</p>

## 🚀 How to use it

### Clone the repo

```bash
$ git clone git@github.com:pierrechls/tweetscape.git
```

### Connect your Twitter API

- Duplicate the `.env.example` file and rename it to `.env`
- Get your application settings from the [Twitter Application Management](https://apps.twitter.com/)
- Remplace the default values into your `.env` file by your Twitter Application values
- Keep `NODE_ENV` value to `production` from your [Heroku application](https://heroku.com) to deploy the API

### Install dependencies

```bash
$ npm install
```

### Serve the client port

```bash
$ npm run dev
```

### Serve the API port

```bash
$ npm run server
```

### Build for production

```bash
$ npm run build
```

### Lint your code

```bash
$ npm run lint
```

### Deploy your build

```bash
$ npm run deploy
```

Set API production URL from the `default.json` file into `settings` folder.

## 🛠 Prior installation

You have to download [Node.js](https://nodejs.org/en/download/)


## 🎉 Credits

Project developed by [Pierre Charles](https://github.com/pierrechls/), [Jules Tantot](https://github.com/lujlujluj) and [Victor Viale](https://github.com/Koroeskohr), 3 students of [IMAC](http://www.ingenieur-imac.fr/) Engineering school.