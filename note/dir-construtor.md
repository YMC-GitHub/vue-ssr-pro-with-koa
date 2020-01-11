# project diretory construtor

```
|--build #some config for the project
|--app #koa server file for ssr pro
|--license #project license file
|--note #save my some note for the project
|--package.json #use npm ,and it's description
|--readme.md #readme before
|--dist #where the html file to serve?
|--public #static resource file to serve
```

# html file diretory construtor(fe)
```
|--dist
| |--static #js/css/img file for web
| |--index.html #csr html index file
| |--service-worker.js #(optional)
| |--vue-ssr-client-manifest.json #ssr client bundle
| |--vue-ssr-server-bundle.json #ssr server bundle
```

# app file diretory construtor(be)
```
|--app
| |--router.js #set the route for server
| |--server.js #web server entey
| |--view.js #render with  client-manifest and server-bundle
```
