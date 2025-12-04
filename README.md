# cam-geo-ft-Laravel

#! do not use this command if not sure or understand
php artisan db:wipe --database=sqlite_locations && php artisan migrate --database=sqlite_locations --path=database/migrations/locations && php artisan db:seed --class=LocationSeeder
