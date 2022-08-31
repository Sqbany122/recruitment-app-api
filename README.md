## Instalation
- clone project using `git clone <project_url>
- `cd recruitment-app-api`
- run `composer install`
- run `cp .env_example .env`
- run `php artisan key:generate`
- after copying .env file we have to add `APP_PORT:10000` line under `APP_URL=http://localhost`
- run `./vendor/bin/sail up` to build docker containers
- run `php artisan migrate` and after that `php artisan db:seed` to provide basic roles for users eg [administrator, subscriber, editor, author]
