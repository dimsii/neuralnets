# Нейронные сети
Практика для курса по нейронным сетям.   
Слайды к лекциям можно найти [здесь](https://drive.google.com/drive/folders/114QaNFTlvY3oXLmzqiGzE48MfpozMTCh?usp=drive_link).

## Начало работы
В первую очередь необходимо завести на github собственный аккаунт и сделать себе форк репозитория.  
Затем клонировать **свой** репозиторий на локальную машину.  

```shell
git clone https://github.com/yourname/neuralnets.git
cd neuralnets
```

Далее нужно настроить виртуальное окружение, если Ваша IDE не сделает это автоматически.   

Ubuntu, Mac:
```shell
python -m venv venv
source venv/bin/activate
```

Windows:
```commandline
python -m venv venv
venv/bin/Activate.bat
```

Установка зависимостей:
```shell
pip install -r requirements.txt
```

Решение задач заключается в реализации функций в файлах seminar*.py  
В файлах test*.py находятся тесты, редактировать эти файлы НЕЛЬЗЯ. 

За каждую правильно решенную задачу начисляется один балл. 
На каждую задачу приходится несколько тестов. 
Количество тестов больше, чем количество задач, поэтому будьте внимательны. 
Правильность решения проверяется тестированием unittest

```shell
python -m unittest discover -v -s src
```

Срок сдачи каждого задания - до начала следующего занятия.
На каждом следующем занятии будем разбирать решение предыдущего. 
Для каждого файла seminar*.py срок выполнения определяется по Вашему последнему коммиту в этот файл. 
Если Вы модифицируете файл после разбора решения на следующем занятии, количество баллов делится на 2. 


## План практических занятий

1. Настройка рабочего окружения, разминка с numpy
2. Обучение Softmax классификатора
3. Многослойный персептрон
4. Обратное распространение ошибки
5. Сверточные сети
6. Машинное зрение
7. Рекуррентные сети
8. Обработка текстов NLP

