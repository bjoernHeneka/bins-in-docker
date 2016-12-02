# php-bin-in-docker
different shell scripts that execute stuff as docker container


## PHP

#### Install php:5.6-cli
```bash
curl https://raw.githubusercontent.com/bjoernHeneka/bins-in-docker/master/php/php5.6.sh > /usr/local/bin/php5.6
chmod +x /usr/local/bin/php5.6
```

#### Install php:7.1-rc
```bash
curl https://raw.githubusercontent.com/bjoernHeneka/bins-in-docker/master/php/php7.1.sh > /usr/local/bin/php7.1
chmod +x /usr/local/bin/php7.1
```

#### Install php:7.0-cli
```bash
curl https://raw.githubusercontent.com/bjoernHeneka/bins-in-docker/master/php/php7.sh > /usr/local/bin/php7
chmod +x /usr/local/bin/php7
```

#### Install bjoernheneka/php7-symfony-fpm:latest
```bash
curl https://raw.githubusercontent.com/bjoernHeneka/bins-in-docker/master/php/php7-symfony-fpm.sh > /usr/local/bin/php7-symfony-fpm
chmod +x /usr/local/bin/php7-symfony-fpm
```