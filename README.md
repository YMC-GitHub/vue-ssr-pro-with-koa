# vue-ssr-pro-with-koa

## desc

vue app ssr production with koa  (ssr mode)

## project diretory constructor

get detail [here](./note/dir-construtor.md)

## some important deps for csr production

- koa (use koa framework)
- koa-router (use route help you?)
- koa-static (use static file serve)
- koa-favicon (to quickly use favicon)
- koa-logger (use log for serve?)
- koa-compress (use zlip to compress)
- lru-cache (mirco cache sth.)

## some config

`config/server.config.js`

01.where the host is? [config](./config/server.config.js#L5)

02.which port will use?  [config](./config/server.config.js#L7)

03.where the html file to serve?  [config](./config/server.config.js#L9)

04.what is the name of html files?   [config](./config/server.config.js#11)

05.where the static file to serve?   [config](./config/server.config.js#13)

## some command

``` bash
# install dependencies
npm install # or yarn install

# serve in production mode
npm start
```

## author

yemiancheng <ymc-github@gmail.com>

## License
MIT
