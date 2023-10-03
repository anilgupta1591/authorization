# authorization
test app of symfony with registration feature
1. Run composer install
2. Create .env from .env.test
3. add : DATABASE_URL=mysql://db_user:db_password@127.0.0.1:3306/db_name?serverVersion=5.7
4. create db: php bin/console doctrine:database:create
5. migrate db: php bin/console doctrine:schema:update --force
6. start server: symfony serve


