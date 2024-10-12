29-09-2024:
Proyecto para practicar filamentphp creando un cms basico

git clone https://github.com/anchicoque/filamentphpcms.git <nuevo-nombre> <br>
composer install <br>
cp .env.example .env <br>
php artisan key:generate <br>

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=nombre_de_tu_base_de_datos
DB_USERNAME=tu_usuario
DB_PASSWORD=tu_contraseña

php artisan migrate

php artisan make:filament-user

npm install && npm run dev
