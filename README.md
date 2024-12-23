DatabaseProject
This project about usage Data Base in web-application in java. Manage your restaurant's data easily with this web app.

Як запустити проект
Переконайтеся, що у вас встановлений Docker.
Клонуйте репозиторій: bash git clone https://github.com/your-username/your-repo.git cd your-repo
Впевніться що змінили параметри в середовищі, або в файлах application.properties, copmpose.yaml, а саме ${LOGIN}, та ${PASSWORD}, на необхідні.
Запустіть проект за допомогою Docker(з кореневої папки проєкту): docker-compose up
Відкрийте браузер і перейдіть за адресою: http://localhost:8081
Щоб зупинити контейнер: docker-compose down
Або
Завантажте PostgreSQL: PostgreSQL Maven: Maven JDK 21: JDK
Впевніться що змінили параметри в середовищі, або в файлах application.properties, copmpose.yaml, а саме ${LOGIN}, та ${PASSWORD}, на необхідні.
Запакуйте проект завдяки Maven: maven package
Запустіть проект за допомогою вашої IDE, або напряму з папки target
Відкрийте браузер і перейдіть за адресою: http://localhost:8081