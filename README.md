# yii2-init-db
Указание настроек для базы данных при инициализации проекта.

Используется для того, чтобы в процессе инициализации проекта (при выполнении команды php init в консоли) сразу можно было указать настройки для подключения к базе данных (сохранятся в файле common/config/main-local.php)

* Разместить файл initDb в корень проекта на Yii-2 (advanced)

* Добавить в  самый конец файла init (в корне проекта) строки:
```
require "$root/initDb";
dbConfig($root);
```

-------------

Пример диалога:

![enter image description here](https://klisl.com/frontend/web/images/external/initDb.png)


Мой блог: [klisl.com](https://klisl.com)  
