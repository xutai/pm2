Check the full documentation on 
[https://pm2.io/doc](https://pm2.io/doc)


basic
```
pm2
pm2 -h, --help
pm2 examples
pm2 <command> -h
```

examples
```
pm2 start app.js --name app
pm2 ls
pm2 delete app
pm2 stop app
pm2 start app
pm2 restart app

pm2 start -i max
npm install pm2 -g && pm2 update
pm2 completion install
```

serve app
```
pm2 start xxx
pm2 stop xxx
```