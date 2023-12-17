В проекте коллекция из 5 запросов. 
1 - получаю возможные валюты и записываю первое значчение symbol в переменную firstSymbol в окружение. 
2 - получаю возможные пары и записываю рандомной значение пары в переменную randomPair.
3 - поучаю минимальное и максимальные значения и записываю их в переменные min_range и max_range соответственно.
4,5 - отправляю POST запросы с min_range и max_range.

В каждом проверяю, что пришел 200 ответ. 
Для запуска запросов необходимо вставить API Key в переменные в запросах. 



In the project, there is a collection consisting of 5 requests:
1 - retrieves possible currencies and saves the first 'symbol' value into the variable 'firstSymbol' in the environment.
2 - retrieves possible pairs and saves a randomly selected pair into the variable 'randomPair'.
3 - obtains the minimum and maximum values and saves them into the variables 'min_range' and 'max_range' respectively.
4,5 - POST requests are then sent using the values from 'min_range' and 'max_range'.

For each request, it checks that a 200 response is received.
To execute the requests, it is necessary to insert an API Key into the variables in the requests.
