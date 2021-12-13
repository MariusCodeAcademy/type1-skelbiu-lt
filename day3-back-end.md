# Lets remember BE

1. Set up express server (you can use our boiler plate)
2. Create github repo for BE. skelbiu-api-(your initials) pvz skelbiu-api-mk
3. Set up empty Login route. `POST /api/auth/login` Console log the data from users login form in BE. Send back {msg: 'success', token: ''}
4. Set up empty Register route. `POST /api/auth/register` Console log the data from users Register form in BE. {msg: 'register success'}
5. Set up connection to DB. Use mysql or mongoDb.
6. Install JWT for tokens and bcrypt for password hashing
7. Create table users. Add one user manually.
8. Register route. When you get user email, check if such email already exists in the table. Send feedback to front end if exists.
9. Register route. Hash password and store it into a DB table users.
10. Login route. Set up JWT tokens and send back user token that has 1 hour expiration date. sent back user email for convenience.
