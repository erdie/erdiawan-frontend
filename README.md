# Erdiawan Frontend

web frontend for erdiawan.com

## Install and Run
```bash
$ npm install gulp gulp-sass browser-sync --save-dev
$ npm run gulp watch
```

## Copy all JS to src/js
```bash
$ npm run gulp copyjs
```

## FAQ

#### How to deploy?

Just run

`npm run gulp watch`

and copy all **src** folder 

#### How to edit styling?

You can edit **style.sass** on *src/sass/style.sass*

And generate the css using this command

`npm run gulp watch`