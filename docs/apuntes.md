- Creamos el proyecto de laravel con:
    ```
    composer create-project laravel/laravel .
    ```
- Nos conectamos a mysql

    mysql -u root -p
    (colocamos pass)    

- Creamos la base de datos en mysql
    create schema api_laravel;

- Creamos los modelos
    
    php artisan make:model nombre_del_modelo -mcr
    
    - -m: Esta opción indica que se debe crear una nueva migración para el modelo. Laravel generará un archivo de migración en el directorio database/migrations que puedes usar para definir la estructura de la tabla clients en tu base de datos.

    - -c: Esta opción indica que se debe crear un nuevo controlador para el modelo. Laravel generará un controlador en el directorio app/Http/Controllers. Por defecto, este controlador estará vacío, a menos que también uses la opción -r.

    - -r: Esta opción indica que el controlador generado debe ser un controlador de tipo "resource", lo que significa que incluirá métodos para las operaciones CRUD (Create, Read, Update, Delete) básicas. Estos métodos corresponden a diferentes rutas y acciones en una típica aplicación basada en recursos.

