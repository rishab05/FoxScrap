# FoxScrap
FoxScrap is a website which show mobiles phone price from different ecommerce site like Flipkart and Amazon. It also show the specification of products.


### Getting Started
To run this repository clone or download using above link.

### Prerequisites
 * Python-3.6
 * Django-1.9


#### Installing
Create a python virtual environment for the prokject
```
$ python3 -m env foxscrap-env
$ cd foxscrap-env
$ source bin/activate
```

Now after activating environment we install djnago in it.
```
$ pip install django==1.9
```
Go the location where you download this repo
```
$ cd webapp
```
Run the server
```
$ python manage.py runsrever
```
After you open localhost go to /products

You will see this login interface
![Alt text](/Screenshots/login.png?raw=true "LogIn")

You can sign up for a new account or use this account:
email- eliot@gmail.com  pswd- eliot

After SignIn index page will open:
![Alt text](/Screenshots/home.png?raw=true "home")

When you click on an Product its detail will open
![Alt text](/Screenshots/details.png?raw=true "product")

![Alt text](/Screenshots/searching.png?raw=true "other")

Amazon.json and flipkart.json are files which was created by using webscraping. (educational purpose only)
You can see olddata file for see the original json file.

Built With
Django - The web framework used
Python - Programming Language


Created with love by Rishabh Sharma
