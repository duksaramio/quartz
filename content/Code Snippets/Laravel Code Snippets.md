

```bash
/bin/bash -c "$(curl -fsSL https://php.new/install/linux/8.4)"
composer global require laravel/installer
laravel new example-app
cd example-app
npm install && npm run build
composer run dev
```

```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=laravel
DB_USERNAME=root
DB_PASSWORD=
```

```
php artisan migrate
```

```
composer require laravel/boost --dev
php artisan boost:install
```

