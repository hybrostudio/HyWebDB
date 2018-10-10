# HyWebDB
**Hybro Web DataBase written in PHP**, compatible with Apache & PHP <br>

***Our HyWebDB DataBase : <br>
Main DataBase : https://webdb.hybro.io <br>
DataBase 2 (Without SSL) : http://tinywebdb.hybrostud.io <br>***

---
---

# How to host your own TinyWebDB Instance
This tutorial will help you to host your **own TinyWebDB Instance** for FREE
This means that you can use _any hosting provider_ or a _VPS with a running Apache & PHP server_

The tutorial is divided in **4 different sections**:
1. [Signup into a hosting service](#1-signup-into-a-hosting-service)
2. [Uploading the files](#2-uploading-the-files)
3. [Configuration](#3-configuration)
4. [Hybro Studio setup](#4-Hybro-Studio-setup)

---

### 1. Signup into a hosting service

You can skip this step and go to "[2. Uploading the files](#2-uploading-the-files)" if you already have a hosting provider or a VPS

***This tutorial will guide you how to host HyWebDB on Cpanel Hosting***

1. **Signup** a Hosting Provider

2. Coming Soon ....

### 2. Uploading the files

For this section, we will use File Manager to upload the File

1. First of all, login to your cpanel 

2. Now, go to "File Manager" and browse into the folder of your domain, you may also create a subdomain (webdb.example.com) and browse to that folder.

3. Download the source code in this page and upload to your folder in the cpanel

4. Now, unzip the source code and copy it into the main folder of your domain/subdomain

### 3. Configuration

1. In Cpanel, go to the folder, make right click to `database.txt` and click on "_File permissions..._":
You need to make the new dialog like this:
![image|285x337](https://community.makeroid.io/uploads/default/original/2X/c/c36a5a46532b377a3ed80f935e722cb95767244d.png)
What is important is the **Numeric value**, which should be **666**
Hit "_OK_" and _configuration will be done for hosting providers_

### 4. Hybro Studio setup

1. Open your project in Hybro Studio, drag a HyWebDB Component to your project, then go to the **Properties** of the HyWebDB Component

2. Now, in the **Service URL**, Type the URL of Your Own HyWebDB (The domain/subdomain that you upload the source code) <br>
![image|201x59](https://cloud.hybro.io/uploads/propertiesserviceurl.png)

2. **Enjoy your own HyWebDB Service!** :tada:

###  ***Can you run this on Github Page ?***
No, you can't ! You can load the index page, but the service will NOT run !
Here is an example : https://hybrostudio.github.io/HyWebDB/

###  ***About this Project***
This project is orginally created by Makeroid under MIT License. <br>
You can Reuse, Commercial use, Modify, Distribute or Private use under MIT License ! <br>
For more information, please read this post : https://community.hybro.io/d/11-hywebdb-the-web-db-for-hybro-services !
