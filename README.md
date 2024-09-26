### Playbook site.yml устанавливает nginx, php 8.1, mariadb-server и cms joomla
#### Для запуска 
```bash
ansible-playbook -i inventory.yaml site.yml --vault-password-file password.txt
```  

#### Настройка самой Joomla  

Указываем название сайта:  

![image](screens/image1.png)  

Заполняем учетные данные и создаем пароль администратора:

![image](screens/image2.png)  

Меняем тип базы данных с MysqlLi на Mysql PDO. Заполняем учетные данные из нашего задания.

![image](screens/image3.png)

Все CMS Joomla установлена корректно

![image](screens/image4.png)