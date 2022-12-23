# Library management System using Django

## Introduction

A library management is a project that manages and stores books information electronically according to students needs. The system helps both students and library manager to keep a constant track of all the books available in the library. It allows both the admin and the student to search for the desired book.

## Modules

### Admin Login
Admin is the one who administers the system by adding or removing e-books into and from the system respectively.

### User Login
Students have to register themselves into the system to create an account.After registering they can login and see the books issued to them.

### Add books
Admin can Add new books and Delete old books.

### Issue Books
Admin can Issue books to users.

## Getting Started

### Install Django in Python Using following Commands:
````
import pip
pip.main(["install","django"])
````
### Templates Directory
1. Go to your Project folder.
2. Copy the path of template folder in library folder.
3. Paste it here:

![Screenshot_20221223_065222](https://user-images.githubusercontent.com/121300594/209355194-8d20047f-a550-40f5-9c17-7bd028894017.png)

### Do as below to run the server:-

1. Open Project in VS Code.
2. Run the Following Commands in Terminal(Command Promt):
````
cd library
py manage.py runserver

````
3. Paste the server link in Web Browser.

### Start Page

This page shows all the links user can access.

![Screenshot_20221223_063218](https://user-images.githubusercontent.com/121300594/209354760-591e60d1-20d0-4abd-bc2e-2f3bee469218.png)



### Homepage

This page gives User the options to Sign up or Log in to Website.

![Screenshot_20221223_064907](https://user-images.githubusercontent.com/121300594/209354917-6d0cf7eb-b3a8-44c7-9cc4-ee9ef0440532.png)

### User Sign in

This page creates user with Usercreationform.

![Screenshot_20221223_082541](https://user-images.githubusercontent.com/121300594/209355771-be5b4f3c-3926-42f2-b7c8-6f408a45a7cd.png)

### User/Admin Login

This page let the user and admin login into website.
**Admin login info:- (Username:- admin) 
                      (Password:- admin)**
                      
![Screenshot_20221223_063348](https://user-images.githubusercontent.com/121300594/209355966-ba5b31a3-cca5-4704-9b04-d23991015a31.png)

### Admin Access

Admin can Add/See Books and Issue Books/See Issued Books to Users.
Admin can also create User and Groups and assign special status to them.

![Screenshot_20221223_063421](https://user-images.githubusercontent.com/121300594/209357045-2f99870e-32b9-4c83-ba34-4cd1a75d736b.png)

### Add Books Interface

Admin can Add Books by filling the form with following information:

![Screenshot_20221223_063449](https://user-images.githubusercontent.com/121300594/209357569-0e68e4b8-70ee-4cbd-91e5-45cee05b8273.png)

### Issue Books Interface

Admin can Issue Books to Users with following information:

![Screenshot_20221223_063515](https://user-images.githubusercontent.com/121300594/209357704-f576dfdb-8ab2-45ba-8373-25e9b03e3c17.png)

### User Access

Users can see Issued books by Admin.

![Screenshot_20221223_072447](https://user-images.githubusercontent.com/121300594/209357292-163d674c-4bb2-4c03-9d44-8a3871d530b1.png)
