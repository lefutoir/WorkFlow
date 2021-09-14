# Install Site via Local

## 👾 Create with Local

1. Create a website using Local with the followings parameters :

![1](https://user-images.githubusercontent.com/54714270/133250546-b2fb0b43-d244-4926-990a-45c96acaab2b.png)

Put the name of the website

![2](https://user-images.githubusercontent.com/54714270/133250559-e0c0e08b-ec78-4adb-9e37-395015107c20.png)

Let it on Preferred unless you need it Custom

![3](https://user-images.githubusercontent.com/54714270/133250583-f8225ec5-4041-4047-979d-feb7f1c3d08a.png)

We have to fill this part but it isn't important

![4](https://user-images.githubusercontent.com/54714270/133250611-328e3d32-0665-4830-ac44-d134d0bc8be2.png)

Put your password if asked

## 📂 Now manage your files

1. Unzip your compressed file
2. Replace all the equivalent from the file  created by Local with the files from your unzipped folder

![files](https://user-images.githubusercontent.com/54714270/133250675-eb6f404c-383b-4919-aa38-311c1caecf97.png)

<img width="2170" alt="5" src="https://user-images.githubusercontent.com/54714270/133250702-1aa61100-b5ec-4331-a664-a92ab32ee1ce.png">

# Keep the `.sql` file somewhere handy

## Once you're done go back to the followings step

![6](https://user-images.githubusercontent.com/54714270/133250996-76c15a26-daac-44e0-9e5a-6f1f458a0e88.png)

Open shell

## Import the database

Put this code in the terminal : `wb db import`

You can drag and drop the path to the .sql file or write it **after the command line**.

![7](https://user-images.githubusercontent.com/54714270/133251043-57f3a842-5b05-47af-b67a-e673ee9b98a6.png)

You can now restart the site via Local, fix the url if needed and go to site to see if it's working

![8](https://user-images.githubusercontent.com/54714270/133251082-bb2bc069-168a-4b06-b3af-aad08be1f0ec.png)

## 👤 Create User with shell

![Capture d’écran 2021-09-14 à 11 12 45 1](https://user-images.githubusercontent.com/54714270/133251213-866a30d0-836f-4d5d-82a8-bf02114f54f5.png)

exemple code with wp user

![Capture d’écran 2021-09-14 à 11 13 04](https://user-images.githubusercontent.com/54714270/133251265-fb7d8f32-ab2c-4a63-871f-bb99b0caafd4.png)

roles for user



Write `wp user create [name] [mail@mail.com] —role=[role]`

<img width="1033" alt="10" src="https://user-images.githubusercontent.com/54714270/133251717-32afcb63-c073-4dba-b5e7-831172ff85ac.png">


It will give you your password, you can now try to login with your username and password. You can change your password later from the WordPress Interface.
