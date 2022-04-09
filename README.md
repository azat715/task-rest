POST   /tasks/              :  создаёт задачу и возвращает её ID
DELETE /tasks/<taskid>      :  удаляет задачу по ID

GET    /tasks/<taskid>      :  возвращает одну задачу по её ID
GET    /tasks/?tag=<tag>     :  возвращает список задач с заданным тегом

GET    /tasks/              :  возвращает все задачи


GET    /due/<yy>/<mm>/<dd> :  возвращает список задач, запланированных на указанную дату