#### INTRODUCE

PHP是一种非常流行的高级脚本语言。


```PHP
tar zxvf php-7.0.12.tar.gz
cd php-7.0.12
./buildconf     # only necessary if building from git
./configure --prefix=/usr/local/php7 --enable-debug --enable-fpm
make
make install
```
