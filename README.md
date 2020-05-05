# Reminder
userGroups - группы с пользователями. Даём название группе, и добавляем в них пользователей. Формат: "название группы": [имя участников, добавляем по почте]  
rules - методы, для отправки сообщений пользователям. Пример формата: {  
"id": 0,  
"users": [  
"group2"  
],   
"todo": "Do smth",   
"time": "06-05-2020_01:41:30",   
"repeat": {   
"days": 0,   
"hours": 0,   
"minutes": 1   
}   
}   
id - номер задачи   
users - кому отправляем сообщения. Перечисляем группы(allGroups если хотим всем)   
to do - Сообщение, которое мы хотим отправить пользователям   
time - В какое время будет отправлено первое сообщение. Формат: '%d-%m-%Y_%H:%M:%S'   
repeat - С какой частотой мы хотим отправлять сообщения.(Days - отправлять раз в n дней, hours - отправлять раз в n часов, minutes - раз в n минут, none - если хотим, чтобы сообщение отправилось одинь раз).
