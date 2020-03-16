# php7_mysql_phpmyadmin For Docker Mac(OSX) 

Set up Host
```
sudo vi /etc/hosts

127.0.0.1       laravel-quickstart.local
127.0.0.1       laravel-quickstart-db.local
```

Start Docker
```
docker-compose up --build -d
```

Migrate Database
```
./migrate.sh
```

Use By
```
Web : http://laravel-quickstart.local
DataBase : http://laravel-quickstart-db.local
```
