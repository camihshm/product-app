# ProductApp

#### 📍 This project was developed to manage products and 'likes' interactions.
--------------------------
### ⚒️ Tools
- **Database**: MYSQL.
- **Programming Language**: Python.
- **Framework**: Django Rest Framework.
- **Docker**.
- **IDE:** PyCharm Community Edition and VSCode.
- **Postman**

### 🪄 Instructions
1 - You need have docker installed and configured on your machine (regardless of OS).<br/>
2 - You need change the database settings in the project:
- docker-compose.
- admin/admin/settings.py - databases.
- You need to configure your database in the IDE's database (if you use VSCode use the extension Database Client).<br/>

### 💻 Commands
**PS:** The command changes according to the OS as I used Windows and use the commands below:
- You need use commands to create and use your docker container to start up the application: **docker-compose up** <br/>

- For create the migrates:
First you need execute: **docker-compose exec backend up** <br> and after you can write and execute: **python manage.py makemigration**<br/>
and after execute the command: **python manage.py migrate**

### 🧠 The project need deveploment front-end to integrate with API.





