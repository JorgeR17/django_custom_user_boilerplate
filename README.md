## Django Custom User boilerplate.
The initial template for making custom users in django.

### Instructions
1- Create users app in your project.
2- Replace the generated files with the ones from this repository.
3- Add your custom fields to the User model.
4- In your settings.py add: AUTH_USER_MODEL = 'users.CustomUser'
5- Make your migrations

This should be done at the beginning of your project before any migrations have been made.

Tested with django 2.2 and 3.0
