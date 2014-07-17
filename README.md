###  
This is a angular static server, Maybe you alwalys create a node server for your angularJS app, so that app can load all static files correctly. Now you don't need to write the node server again, you just need run the app in your app directory, then open it on your browser.


### Usage
* Download the app in any directories.
* Add it to you profile`.bash_profile`.
```
SSERVER_BIN=/path/to/static-server
export PATH=$SSERVER_BIN:$PATH
```
* Run it in your app directory.
```
$ SServer
```
* Enter url in your browser.
```
127.0.0.1:3000
```

### Help `SServer -h`
```
  Usage: SServer [options]

  Options:

    -h, --help             output usage information
    -V, --version          output the version number
    -p, --path [value]     add the static files paths, default="./", multi paths separate by ","
    -P, --Port [value]     set the server listen port, default="3000
    -d, --default [value]  set default page, default="index.html/default.html"
```

