# docker-php7-mariadb-phpmyadmin
Run php7, MariaDb and phpmyadmin using docker-compose


```bash
git clone https://github.com/ruslyrossi47/docker-php7-mariadb-phpmyadmin.git
cd docker-php7-mariadb-phpmyadmin/
docker-compose up -d
```

You can access using http://localhost/ and phpMyAdmin using http://localhost:8181/phpmyadmin

To connect from php code to MySql:

    <?php $con=mysqli_connect("mysql","root","pass","my_db");

