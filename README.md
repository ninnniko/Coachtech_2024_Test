・Dockerビルド
１git clone git@github.com:coachtech-material/laravel-docker-template.git
2mv laravel-docker-template todo
3git remote set-url origin git@github.com:ninnniko/Coachtech_2024_Test.git
4git push origin main
5docker-compose up -d –build

・Laravel環境構築
１composer create-project “laravel/laravel=8.*” . --prefer-dist
２cp .env.example .env
３php artisan make:migration create_authors_table
４php artisan make:seeder AuthorsTableSeeder

・使用技術
PHP：バージョン7.4.9
Laravel：バージョン8.83.8
nginx：バージョン1.21.1

・ER図
"\\wsl.localhost\Ubuntu\home\niko\coachtech\Test\contact-form\ER.png"
