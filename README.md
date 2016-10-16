# ship
docker package manager, just for fun

## install

Place the ruby script `ship` in your path and get the repo:

```
curl https://raw.githubusercontent.com/ship-containers/ship/master/ship > /usr/local/bin/ship
chmod +x /usr/local/bin/ship
sudo git clone https://github.com/ship-containers/repo.git /opt/ship
```

## usage

```
$ ship help
ship package manager
just for fun           _
   __________      ___| |
  /          \___/   """|
~~~~~~ ~~ ~~~~ ~~~ ~~~~ ~~~

Usage:

ship list               see all available packages
ship installed          see all installed packages
ship update             update all Dockerfiles
ship upgrade            rebuild all installed packages
ship build   <package>  build a package
ship rebuild <package>  build a package with caches
ship install <package>  create executable for package
ship remove  <package>  delete image for package
ship search  <package>  find package name
ship help               this message
```

## example

<img src="https://github.com/ship-containers/ship/blob/master/ship.gif?raw=true">
