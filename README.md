## User Accounts Phase-1
### A Starter project for user login-logout and Sign-up in Django.

Django has amazing built-in authentication system which needs to be implemented everytime a new project is started. Implementing the login-logout and Sign-up can sometimes feel redundant. This project aims to provide a basic starter pack for Developers.

Along with above-mentioned functionalities, the Phase-1 project also includes the necessary ```Password Change``` and ```Password Reset``` functionalities as well.

##### Sign-up functionality does not create users with staff status.


The project relies on ``` django.contrib.auth ```  present under ```INSTALLED_APPS``` with implementing 3 base template files.
```
templates/registration/login.html
templates/registration/password_change_form.html
templates/registration/password_change_done.html
templates/base.html
templates/home.html
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

Navigatable URLs
```
http://127.0.0.1:8000/accounts/login/
http://127.0.0.1:8000/accounts/signup/
http://127.0.0.1:8000/accounts/logout/

-- PasswordChange
http://127.0.0.1:8000/accounts/password_change/
http://127.0.0.1:8000/accounts/password_change/done/

-- PasswordReset
http://127.0.0.1:8000/accounts/password_reset/
```

NOTE - The ```home``` url is not defined. It is up-to the user to start a new app and redirect the ```home``` url to newly created app.

The emails generated are at project level.

Visit https://coding-decoded.com for more details.
