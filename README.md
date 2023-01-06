# Commands and Tips


## _Artisan_

- **Create template, migration, and factory resource controller** : php artisan make:model Todo -a
- cria o Controller: php artisan make:controller TodoController
- Cria o Model e a Migrate: php artisan make:model NomeDaModel -m

## migrates

- Executa novamente todas migrates deletando antigas : php artisan migrate:fresh 
- Alterar campo em produçao: php artisan make:migration add_category_to_products_table 
- Desfaz a última migrate: php artisan migrate:rollback
- Desfaz todas migrate: php artisan migrate:reset
- Desfaz todas migrate e faz o migrate novamente sem deletar: php artisan migrate:refresh