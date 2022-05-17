now first rename the "env.example file to.env"
4. you can configure the database information here.
5. now open cmd and run some commands...
 -Run composer install or php composer.phar install
 -Run php artisan key:generate
 verander de warden bij database config  bij  mysql to 
 'charset' => 'utf8',
 'collation' => 'utf8_unicode_ci',
 
 shop.sql importeren 
