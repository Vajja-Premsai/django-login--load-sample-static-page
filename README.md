# Django Login & Register
This a Django project that allows users to login to your website and allows them to register for an account as well! The HTML templates use the [Bootstrap login template](https://getbootstrap.com/docs/4.0/examples/sign-in/) and the user data is stored in a JSON file. You can use this in your website!

## Prerequisites:
* [Python](https://www.python.org/) Installed (I used 3.8.9)
* [Django](https://www.djangoproject.com/) installed. (I used 3.1.2)
* A Terminal.

You can install Django with:
```bash
pip install Django==3.1.2
```


```

You also have to enter the directory. You can do that with Terminal / Command Prompt:

```bash
cd django-login-and-register
```

Once that is done, you can run it on a localhost!

## Running The Server On Localhost

In your Terminal / Command Prompt, type the following:

```bash
python manage.py runserver
```
You would see some logs now. Ignore them. All you have to do is visit [`localhost:8000`](http://localhost:8000) on your browser. To stop the server, return to your terminal and press `CTRL-C`.

## Logging In

Visit the [login page](http://localhost:8000/login/) and try to login! The preloaded user's email is `person1@org.com` and the password is `placeholder`. You can view this in [user_data.json] If you enter incorrect details, you will see a [Bootstrap Alert](https://getbootstrap.com/docs/4.0/components/alerts/). To register with an account, visit the [registration page](http://localhost:8000/register).

## Register For An Account

Visit the [registration page](http://localhost:8000/register/) and create an account!



Using an email that is already in use will give you a [Bootstrap Alert](https://getbootstrap.com/docs/4.0/components/alerts/).



It also returns an alert if the passwords do not match.



The `Name` field is not used anywhere by the server. It is up to you to use that!

## The JSON File

The [JSON File] contains all the emails and passwords of users. Without this file, The project will have no function at all! You may read, remove items and add them from anywhere, but there must be atleast one email and password.

## Next Steps

You can incorporate this inside your website as well! You can modify the templates and the fields. Use this project to authenticate your users.

## Authors

*Vajja Premsai
