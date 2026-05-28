# MemeBoard - Доска мемов

**ФИО:** Ткаченко ВМ
**Группа:** ИСП-231

## Краткая инструкция по запуску
```bash
cd MemesApi
dotnet run
```
Сервер запустится по адресу: http://localhost:5000
Swagger UI доступен по адресу: http://localhost:5000/swagger
(вообще адресс не помню(()
## Что изучили
| Концепция | Где используется |
| --- | --- |
| fetch(url) | GET-запрос к API |
| fetch(url, { method, headers, body }) | POST и DELETE запросы |
| response.ok | Проверка успешности ответа |
| response.json() | Чтение JSON из ответа |
| JSON.stringify(...) | Объект JS → JSON-строка для отправки |
| async / await | Ожидание ответа от сервера |
| try / catch / finally | Обработка ошибок при fetch |
| CORS | Разрешение запросов между разными портами |
| AddCors + UseCors | Включение CORS в ASP.NET Core — два шага |
