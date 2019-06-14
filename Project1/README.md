# Project1
This is based on the tutorials by Bucky Roberts on his channel thenewboston on Youtube.  
[Click here for the Youtube playlist](https://www.youtube.com/playlist?list=PL6gx4Cwl9DGBlmzzFcLgDhKTTfNLfX1IK)

Start an app (Edit this) 

```
django-admin startproject website
```
Enter the directory created by the above line 

```
cd website
```

Run the development server

```
python manage.py runserver
```

The output should look like this 

```
Performing system checks...

System check identified no issues (0 silenced).

You have 13 unapplied migration(s). Your project may not work properly until you apply the migrations for app(s): admin, auth, contenttypes, sessions.
Run 'python manage.py migrate' to apply them.

June 13, 2019 - 06:35:09
Django version 1.11.21, using settings 'website.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CONTROL-C.
```

Navigate to http://127.0.0.1:8000/ and you should see a page that says 'It worked!
Congratulations on your first Django-powered page' 

Superuser details are: 

```
username: somansh 
email: admin@example.com  
password: password123  
```
