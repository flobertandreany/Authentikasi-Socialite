#Guide Instalasi Project

1. create project laravel dengan composer create-project laravel/laravel="8.*" AUTHENTIKASI

2. create database di phpmyadmin dan ubah DB_DATABASE di .env dengan nama authentikasi

3. composer require laravel/ui:*

4. php artisan ui bootstrap --auth

5. npm install && npm run dev

6. php artisan migrate

7. mendapatkan client id dan client secret pada https://console.cloud.google.com

8. copy client id, client secret, dan google redirect ke .env

9. composer require laravel/socialite

10. setting services.php

11. membuat tombol login google dan login controller

12. menambahkan routing di web.php
