- Post ответ
![post_answer](https://github.com/AlexSartsev/Postman/blob/main/screenshots/1.%20POST%20ответ.png)
{
    "status": "OK",
    "place_id": "d6b1a9823ea220d75869d52bffa8d27a",
    "scope": "APP",
    "reference": "cb7e07bf458bf2e5d8546bc562759fd4cb7e07bf458bf2e5d8546bc562759fd4",
    "id": "cb7e07bf458bf2e5d8546bc562759fd4"
}
- Get ответ (позитивное тестирование)
![get_answer](https://github.com/AlexSartsev/Postman/blob/main/screenshots/2.%20GET%20ответ.png)
{
    "location": {
        "latitude": "-38.383494",
        "longitude": "33.427362"
    },
    "accuracy": "50",
    "name": "Frontline house",
    "phone_number": "(+91) 983 893 3937",
    "address": "29, side layout, cohen 09",
    "types": "shoe park,shop",
    "website": "http://google.com",
    "language": "French-IN"
}
- Get ответ (негативное тестирование)
![get_answer_negative](https://github.com/AlexSartsev/Postman/blob/main/screenshots/3.%20GET%20ответ%20(негативное%20тестирование).png)
{
    "msg": "Get operation failed, looks like place_id  doesn't exists"
}
- Put ответ (позитивное тестирование)
![put_answer](https://github.com/AlexSartsev/Postman/blob/main/screenshots/4.%20PUT%20запрос%20-%20ответ.png)
{
    "msg": "Address successfully updated"
} 
- Put ответ (негативное тестирование)
![put_answer_negative](https://github.com/AlexSartsev/Postman/blob/main/screenshots/5.%20PUT%20запрос%20-%20ответ%20(негативное%20тестирование).png)
{
    "msg": "Update address operation failed, looks like the data doesn't exists"
}
- Delete ответ (позитивное тестирование)
![delete_answer](https://github.com/AlexSartsev/Postman/blob/main/screenshots/6.%20DELET%20запрос-ответ%20(позитивное%20тестирование).png)
{
    "status": "OK"
}
- Delete ответ (негативное тестирование)
![delete_answer](https://github.com/AlexSartsev/Postman/blob/main/screenshots/7.%20DELETE%20ответ%20(негативное%20тестирование).png)
{
    "msg": "Delete operation failed, looks like the data doesn't exists"
}