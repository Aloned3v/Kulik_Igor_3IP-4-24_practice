Web3 answer:
Method: GET
Status: 200
Content-Type: application/json, 10 id
Other status: нет

Web4 answer:
Вернулось: 5
Равные 5: 5

Web5 answer:
id: 1, 2, 3

Web6 answer:
5, 5
postId - уникальное id поста

Web7 answer:
параметр _limit отвечает за лимит json objects
со значением _limit=2:  2 объекта
со значением _limit=7:  7 объекта

Web8 answer:
в urls.md
Web9 answer:
Вывод: одни и те же данные получены двумя разными дорогами

Web10 answer:
/users/1 - 200 OK
/users/11 - 404 Not Found
/users/1?foo=bar - 200 OK
Ломает: неверный id в path (/users/11)
Не ломает:  ?foo=bar

Web11 answer:
Content-Type: application/json; charset=utf-8
Content-Length: -

Web12 answer:
/todos?_limit=5&_page=1 - 5 объектов, id первого = 1
/todos?_limit=5&_page=2 - 5 объектов, id первого = 6
Параметр _page задаёт номер страницы
