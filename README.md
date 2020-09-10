pm2@4.4.1
```
npm install pm2 -g && pm2 update
```


projects prod
> at the **root** directory **~**
```
cd ~/home/
pm2 start home/server.js --name home
cd ~/gaming-admin
pm2 start gaming-admin/server.js --name admin
cd ~/serving-resources
pm2 start serving-resources/server.js --name resources
```