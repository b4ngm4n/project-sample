## Base Template Readme Project Sample
this base template README.md for your project installation

### Clone this project 
```bash
git clone https://github.com/b4ngm4n/project-name.git
```

### Move to project
```bash
cd project-name
```

### Configure

```bash
composer install
```

```bash
php artisan key:generate
```

If you using npn you can run this command
```bash
# npm install && npm run dev
```

### Setup Database

```bash
cp .env.example .env
```

```bash
nano .env
```

```bash
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=database-anda
DB_USERNAME=usernama-database-anda
DB_PASSWORD=password-database-anda
```

```bash
php artisan migrate
```

If you have a seeder you can using this command
```bash
php artisan db:seed
```
