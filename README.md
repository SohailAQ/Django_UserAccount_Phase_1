## User Accounts Phase-1
### A Starter project for user login-logout and Sign-up in Django.

Django has amazing built-in authentication system which needs to be implemented everytime a new project is started. Implementing the login-logout and Sign-up can sometimes feel redundant. This project aims to provide a basic starter pack for Developers.

The project relies on ``` django.contrib.auth ```  present under ```INSTALLED_APPS``` with implementing 3 base template files.
```
templates/registration/login.html
templates/base.html
templates/signup.html
```

A new app ```accounts``` is added which handles the Sign-up functionality.

Other details

```
Python      3.9.6
Django      3.2.5
psycopg2    2.9.1
---
Database        PostgreSQL
Databse Name    Phase_One
```

Navigatable URLs starter
```
http://127.0.0.1:8000/accounts/login/
http://127.0.0.1:8000/accounts/signup/
http://127.0.0.1:8000/accounts/logout/
```

NOTE - The ```home``` url is not defined. It is up-to the user to start a new app and redirect the ```home``` url to newly created app.


Visit https://coding-decoded.com for more details.