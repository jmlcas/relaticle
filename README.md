# Relaticle

Comando para cambiar APP_KEY:

$ echo "APP_KEY=base64:$(openssl rand -base64 32)"

Crear cuenta administrador, usando este comando:

$ docker compose exec app php artisan make:filament-user

Ver en "http://localhost:8200/app"

Y en: "http://localhost:8200/sysadmin"
