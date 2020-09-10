pm2@4.4.1
```
npm install pm2 -g && pm2 update
```


projects prod
> at the **root** directory **~**
```
pm2 start gaming-admin/server.js --name admin
pm2 start serving-resources/server.js --name resources
```