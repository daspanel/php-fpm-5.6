
# Usage


### Get
```shell
$ docker pull daspanel/php-fpm-5.6:latest
```

### Run
```shell
$ docker run -e DASPANEL_MASTER_EMAIL=my@email.com --name=my-php-fpm-5.6 daspanel/php-fpm-5.6:latest
```

### Stop
```shell
$ docker stop my-php-fpm-5.6
```

### Update image
```shell
$ docker stop my-php-fpm-5.6
$ docker pull daspanel/php-fpm-5.6:latest
$ docker run -e DASPANEL_MASTER_EMAIL=my@email.com --name=my-php-fpm-5.6 daspanel/php-fpm-5.6:latest
```

# Tips
