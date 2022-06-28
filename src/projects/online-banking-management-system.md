---
title: Online Bank Management System
description: Built a Bank Management System Website with Python and Flask
author: Ahaan Kanaujia
date: 2022-03-15T00:32:34.644Z
tags:
  - Python
  - Flask
  - SQLAlchemy
  - HTML5/CSS3
  - Werkzeug_Security
---
### Overview:

<br>

This is a full stack website built using Python that allows users to sign up and login to online virtual bank accounts, where they can make transactions, avail loans, and invest in fixed deposits. It also includes security measures to prevent customer data being leaked. 

<br>

### Back End:

<br>

The back end of the website is implemented using the Flask micro-web framework and a SQLAlchemy database that stores user details such as usernames and passwords, previous transactions, and current and previous loans and investments. An API was used to retrieve form data from the website and interact with the database using Python connectors. 

<br>

### Front End:

<br>

The front end was designed using HTML5 and CSS3 along with the Bootstrap front end framework. The website includes multiple pages which interact with the database through the Django template language and display various records on the page, including previous and current loans, investments, deposits, and withdrawals.

<br>

### Security:

<br>

Improved the security of the website by applying to SHA256 hashing algorithm in the Werkzeug security library for secure passwords. The website also prevents first order SQL Injection and XSS (Cross Scripting) attacks by sanitizing user inputs and limiting the use of special characters. The secuirty measures detect any form of SQL or JS code entered in all input fields and disregards any such entries.

<br>

[<strong><u>GitHub](https://github.com/AhaanKanaujia/Online-Banking-Management-System)
