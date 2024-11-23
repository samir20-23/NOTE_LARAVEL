laravel:
    [installing]
        php: https://www.php.net/downloads
        composer: https://getcomposer.org/download/
        nodejs: https://nodejs.org/en/download/
        git: https://git-scm.com/downloads
        vscode: https://code.visualstudio.com/download

[packg]
    composer create-project laravel/laravel namefile
    cd namefile
    composer install

[dev-server]
    php artisan serve

[database]
    php artisan migrate
    php artisan migrate:rollback
    php artisan migrate:refresh
    php artisan db:seed
    php artisan migrate:fresh --seed

[cache]
    php artisan cache:clear
    php artisan config:clear
    php artisan route:clear
    php artisan view:clear

[routes]
    php artisan route:list

[make-commands]
    php artisan make:model ModelName
    php artisan make:controller ControllerName
    php artisan make:migration create_table_name
    php artisan make:seeder SeederName
    php artisan make:middleware MiddlewareName
    php artisan make:request RequestName
    php artisan make:command CommandName
    php artisan make:policy PolicyName
    php artisan make:factory FactoryName
    php artisan make:event EventName
    php artisan make:listener ListenerName
    php artisan make:notification NotificationName
    php artisan make:job JobName
    php artisan make:resource ResourceName

[auth]
    php artisan make:auth        (For Laravel versions < 6)
    composer require laravel/ui  (For Laravel >= 6)
    php artisan ui vue --auth

[queue]
    php artisan queue:work
    php artisan queue:listen
    php artisan queue:restart

[storage]
    php artisan storage:link

[testing]
    php artisan test
    php artisan make:test TestName

[artisan-options]
    php artisan help CommandName
    php artisan list
