# Laravel 8 - UI Bootstrap y API con JWT Authentication

## Comenzando 馃殌

_Sigue las siguientes instruscciones para clonar este repositorio en tu m谩quina local y poder trabajar con Laravel 8 API con JWT Authentication._

### Pre-requisitos 馃搵

Para clonar este repositorio, debes tener instalado un servidor Apache, PHP y MSQL (Wamp, Xampp, Mamp o Lamp) y los gerenciadores de dependencias para PHP (Composer).

Antes de comenzar verifica si tienes composer con cualquiera de los siguientes comandos en tu terminal.
```
composer --version 
composer -v
```
Si no lo tienes instalado lo pueden instalar siguiendo la documentaci贸n oficial en:  
https://getcomposer.org/doc/00-intro.md


Verifica las versiones de cada uno de ellos

Versi贸n PHP - 7.4.2  
Versi贸n Mysql - 5.7.26  
Versi贸n Composer - 1.10.1  

### Instalaci贸n 馃敡

_Sigue las siguientes instrucciones para clonar el repositorio_

_Clone el repositorio_

```
git clone https://github.com/jorgehernandezch/Laravel-8-ui-Api-JWT.git
```

_Instale todas las dependencias del Proyecto con_

```
composer install
```

_Copie el Archivo .env.example en un archivo nuevo .env con_

```
cp .env.example .env
```
_Configure la base de datos y las demas variables de entorno en el archivo .env_

_Genere una nueva Key para el protecto con_

```
php artisan key:generate
```
_Genere una nueva Key para JWT con_

```
php artisan jwt:secret
```
_Corra las migraciones del proyecto con_

```
php artisan migrate
```

_Corra los seeder del proyecto con_

```
php artisan db:seed
```
_Corra el proyecto con_

```
php artisan serve
```

_Si todo est谩 correcto puede acceder al proyecto en la direcci贸n http://localhost:8000/api, el sistema devolver谩 un error en formato JSON diciendo que el usuario no est谩 autenticado, eso significa que la API est谩 funcionando correctamente._

Use Postman o Insomnia para enviar datos GET y POST

---
[Jorge Edo. Hern谩ndez](https://github.com/jorgehernandezch)  
_Ingeniero y Desarrollador Web_
