# CRUD_API_Using_Resources_LARAVEL8

## how to test?

-   git clone repository

-   php artisan key: generate

### I created a database using phpmyadmin. You can create one and add your bank name to the .env file in the DB_DATABSE field

-   php artisan migrate

Once this is done, it is necessary to fill the POSTS table, to fill the factory will be used to create the records.

-   php artisan db: seed

-   php artisan serves

Use an insomnia / postman or similar applications for interactions with the API

-   GET: http://127.0.0.1:8000/api/posts/

-   GET: http://127.0.0.1:8000/api/posts/{ID}

-   PUT: http://127.0.0.1:8000/api/posts/{ID} - Send in the body

-   POST: http://127.0.0.1:8000/api/post/ - Send in the body

-   DELETE: http://127.0.0.1:8000/api/posts/{ID}
