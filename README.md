mysqlenv
========

setup
------
```
git clone git://github.com:shim0mura/mysqlenv.git

export PATH=/path/to/mysqlenv:$PATH
mysqlenv init
```

commands
-------

install mysql
```
mysqlenv install 5.5.30
```

start mysql
```
mysqlenv start 5.5.30
```

stop mysql
```
mysqlenv stop 5.5.30
```

start all installed versions concurrently
```
mysqlenv -a start
```

show location of my.cnf and socket
```
mysqlenv info 5.5.30
```
