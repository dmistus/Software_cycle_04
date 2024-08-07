# Домашнее задание к занятию «Jenkins» 
  

### Подготовка к выполнению 

#### *Созданы две VM с помощью Terraform*

 ![](img/2024-07-08_02-40.png)
 
#### *Установил Jenkins при помощи playbook.*

![](img/2024-07-07_18-21.png)

![](img/2024-07-07_18-46.png)

![](img/2024-07-07_18-52.png)

![](img/2024-07-07_22-01.png)

### Основная часть 

#### *Создал Freestyle Job, который запускает molecule/test из моего репозитория с ролью vector-role:*

![](img/2024-07-07_22-58.png)

![](img/2024-07-08_01-47.png)

#### *Создал Declarative Pipeline Job, который запускает molecule/test из того же репозитория:*

![](img/2024-07-08_02-13.png)

#### *Перенес Declarative Pipeline в файл Jenkinsfile.*

#### *Создал Multibranch Pipeline на запуск Jenkinsfile из репозитория.*

![](img/1.png)

![](img/2.png)





#### *Создать Scripted Pipeline, наполнить его скриптом из pipeline.*

![](img/3.png)

#### *Отправить ссылку на репозиторий с ролью и Declarative Pipeline и Scripted Pipeline.*



[Vector-Role] (https://github.com/dmistus/vector-role-molecule/tree/main/ /)

[Declarative_Pipeline] (https://github.com/dmistus/vector-role-molecule/blob/main/Jenkinsfile)

[Scripted_Pipeline] (https://github.com/dmistus/vector-role-molecule/blob/main/ScriptedJenkinsfile)

