# packages-laravel

### AdminLTE

Info: Add AdminLTE to the project.

Docs: https://github.com/jeroennoten/Laravel-AdminLTE

Install:
  I: composer require jeroennoten/laravel-adminlte
  II: composer require laravel/ui (Laravel 7)
  III: php artisan ui:controllers (Laravel 7)
  IV: php artisan adminlte:install
  
- Views authenticate  
  I: php artisan adminlte:install --only=auth_views
  
- Others
  I: php artisan adminlte:install --only=config (Pubish config)
  II: php artisan adminlte:install --only=main_views (Customize view)
