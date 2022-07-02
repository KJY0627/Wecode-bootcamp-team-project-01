## ✅ 
---
<p align="center">
  <br>
  <img src="./images/nose_main_image.png">
  <br>
  This is a main page.
</p>

📍 __Description__

This repository shows one of the clone coding projects as a backend developer as the first team project from Wecode coding Bootcamp 34th located in South Korea. 
[Wecode-bootcamp-Korea](https://github.com/wecode-bootcamp-korea)


Frontend Repository : (https://github.com/wecode-bootcamp-korea/34-1st-Nose-frontend)

<br>

📍 __Index__

1. Introduction  

2. Technology stack

3. Fuctions



<br>
<br>

## ✅ Introduction
---

This project aimed to apply things learned from the boot camp by implementing some features from the Paffem [PAFFEM](https://paffem.cafe24.com/) website which is available to recommend personal perfume function.

The images that this project is all from [pixabay](https://pixabay.com/ko/)which is regardless of copyright.

We used `Trello` and `Notion` for communiction.
<p align="center">
  <br>
  <img src="./images/nose_trello.png">
  <br>
  Trello
</p>

<p align="center">
  <br>
  <img src="./images/nose_notion.png">
  <br>
  Notion
</p>

<br>

### 📌 Purpose

1. Optimizing server by using `Django` of Python.

2. Implements Database by utilzing MySQL, and understanding ORM.

3. Building communication skills via various tools as backend developers.

4. Experiencing Scrum work.

<br>

### 📌 Team 'Nose'

2 members of Backend developers.

__김상웅 [sangwoong03](https://github.com/sangwoong03)__

- By using `dbdiagram` Data Modeling.

- `Django` Project initial setting.

- 'Login feature' and via `bcrpyt`, `pyjwt` implements Authorization API.

- 'Products list feature' and 'Products details' API .

<br>

__김지영 [KJY0627](https://github.com/KJY0627)__

- By using `dbdiagram` Data Modeling.

- Implements MySQL DataBase.

- 'Signup feature' and via `bcrypt`, save encoded personal information as Database.

- Carts API - POST, GET, DELETE.

<br>
<br>

## ✅ Technology stack
---



`requirements.txt` .

<br>

### 📌 Backend technology stack
| Language | Framwork |  Database |  ENV | HTTP  |
| :------: | :------: | :-------: | :--: | :--: |
|    <img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white">   |   <img src="https://img.shields.io/badge/django-092E20?style=for-the-badge&logo=django&logoColor=white">    | <img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=black">| <img src="https://img.shields.io/badge/miniconda3-44A833?style=for-the-badge&logo=anaconda&logoColor=white"> | <img src="https://img.shields.io/badge/postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white">

<br>
<br>

## ✅ Fuctions
---
This project contains four features.


__1. Signup feature API__

- Member `validation check`

- Password `bcrypt` encode

<br>

__2. Login feature API__

- By using `bcrypt` encode/decode

- `jwt`token authorization/creat

<br>

__3. Products API__

- `Shop` - load products shopping list
- Products filtering via `Qeury Parameter'
- Loading detailed products information via `Path Parameter`

<br>

__4. Carts API__

- Add products from the product detail page
- Check authorized user's added products from the cart
- Delete authorized user's products from the cart
