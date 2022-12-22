#Guide Instalasi Project

1. composer create-project laravel/laravel="8.*" Authentikasi
2. create database di phpmyadmin dengan nama authentikasi dan ubah pada database di .env dengan nama yang sama
3. composer require laravel/ui:*
4. php artisan ui bootstrap --auth
5. npm install && npm run dev
6. php artisan migrate
7. mendapatkan Client Id dan Client Secret pada https://console.cloud.google.com
8. menambahkan client Id, client secret, dan google redirect pada .env
9. composer require laravel/socialite
10. setting services.php di dalam folder config
11. membuat tombol login google pada view
12. setting LoginController
13. menambahkan routing pada web.php
