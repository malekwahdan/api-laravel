# api-laravel
# use php artisan serve 
# then open postman 
# write down this usrlhttp://localhost:8000 (depends on your serve)
# use http://localhost:8000/api/register to register a new user and write down on body section
{
    "name":"malek",
    "email": "malek@gmail.com",
    "password":"your-password",
    "confirmation_password": "your-password"

}
make sure to selece "row" and json option

# use http://localhost:8000/api/login to login and write down on body section
{
    "email": "malek@gmail.com",
    "password":"your-password"
}
# use http://localhost:8000/api/store to add a new todo to your list then in the body write down
{
    "title": "yourtassk",
    "description": "your description",
    "is_completed": true or false

}
(in headers section make sure to write down Authorization for key and Bearer followed up with your token that you get when you login for value
and another row ,write down Content-Type for key and application/json for value
)
# use http://localhost:8000/api/show/id to show a specifec todo of yours 
# use http://localhost:8000/api/delete/id to delete  a specifec todo of yours 
# use http://localhost:8000/api/update/id to update a specifec todo of yours and in the body section 

{
    "title": "your updated tassk",
    "description": "your updated description",
    "is_completed": true or false

}

