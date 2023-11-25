Уразгалиев Асланбек Ахатович - Тестировщик 

Обо мне
Привет! Меня зовут Аслан, я начинающий тестировщик.
В этом репозитории вы можете найти некоторые из моих проектов, выполненных во время обучения и практики.

Навыки и технологии
Jira, qase.io,SQL, Postman,Fiddler, Swagger, Trello,PpostgresSQL
SoapUI, Android Studio, xCode, Charles, Git, Chrome DevTools,pgAdmin  

Проекты

Проект 1: тест веб-приложения для учителей от Skyeng

https://arkham0.atlassian.net/wiki/spaces/~63dd33e4790148a180953aba/pages/131150/1+2 - ссылка на проект в Atlassian.

Что нужно было сделать:
№1 
        .составить тест план
        . подготовить тестовую документацию, 
        . провести smoke и приемочное тестирование функционала 

№2
        .изучить API документацию
        .Создать Postman-коллекцию
        .выполнить тестирование API

В ходе работы , я, изучил новый функционал Skyeng для учителей.А иммено добовление личных событий .Составил функциональный чек-лист проверил как валидные так и не валидные запросы к серверу.
После чего составил еще smoke тест кейсы , провел тестирование по ним.
Еще на этапе тестирования Web нашел несколько весьма значительных быгов.Описал их в Jira.
А уже на 2 этапе тестирования API. Я изучил документацию по API.
Проверил функционал через коллекцию в Postman/
Убедился в правильности приходящих статус ответов от сервера.
Все ошибки как и всегда занес в Jira.

Выводы (итоги):
        Новая функция ,добавления  личных событий, частично соответствует заявленному ожиданию,а также в результате проверок  был выявлен 1 серьезный дефект связанный с добавлением нового функционала .
        Один из найденных багов ,весьма, серьезно мешает работе портала так ,как не дает создать событие в текущий момент. Т.Е. не работает чать функционала ПО.Прошу принять во внимание данный дефект и вводить обновление в эксплуатацию после его устранения.


Проект 2
тестирование моб приложения Sky-Eng
Задачи
- составить тест-план
- проанализировать требований 
- Тестовая документация к ситуациям и видеопрактике составить чек-листы или тест-кейсы
- Анализ выбора устройства
- Отчет о тестировании

Тестирование разделов "Ситуации" и "Видеопрактика" мобильного приложения "Skyeng" 																									
Тестировщики: Асланбек Уразгалиев																									
Тестируемые устройства:	Iphone 13(ios 17.0.3), android studio(one plus 11 pro)																							
																									
Требования	Вопросы к требованиям	Критерий																							
Раздел "Ситуации"																									

Если ситуация новая и все уроки в ней новые (бэк возвращает параметр "hasNewLessons":true и "isNew": true), то в правом верхнем углу картинки отображается иконка New.	Какая иконка отображается в правом верхнем углу картинки, если ситуация новая но не все уроки в ней новые?	Требование не соответствует критерию "Полнота", "Завершенность"																							

Потом отображаются завершенные ситуации. У данных ситуаций есть галочка о завершенности.	Какого цвета должна быть галочка о завершенной ситуации?	Требование не соответствует критерию "Полнота"																							

Есть кнопка «Здесь нет того, что я хочу».	Какая функция должна выполнять кнопка "Здесь нет того что я хочу"?	Требование не соответствует критерию "Проверяемость"																							

Раздел "Видеопрактика"																									

У каждой темы есть заголовок (Popular, Travel, Sport).	Это все количество заголовков или их больше?	Требование не соответствует критерию "Полнота"																							

При нажатии на кнопку «Назад» возвращаемся на главную.	Возвращаемся на главную страницу темы или каталога "Видеопрактики"?	Требование не соответствует критерию "Завершенность"																							

Если со страницы с видео нажать кнопку «Назад», попадаем на главную страницу.	Где расположена кнопка "Назад" и как она выглядит?	Требование не соответствует критерию "Полнота"																							
																									
																									
														
отчет о тестировании																									
																									
																									
Во время проведения тестирования было выявлено 6 замечаний состовления требований к моб.приложению а именно :																									
																									
Если ситуация новая и все уроки в ней новые (бэк возвращает параметр "hasNewLessons":true и "isNew": true), то в правом верхнем углу картинки отображается иконка New.	Требование не соответствует критерию "Полнота", "Завершенность"																								
Потом отображаются завершенные ситуации. У данных ситуаций есть галочка о завершенности.	Требование не соответствует критерию "Полнота"																								
Есть кнопка «Здесь нет того, что я хочу».	Требование не соответствует критерию "Проверяемость"																								
Если ситуация новая и все уроки в ней новые (бэк возвращает параметр "hasNewLessons":true и "isNew": true), то в правом верхнем углу картинки отображается иконка New.	Требование не соответствует критерию "Полнота", "Завершенность"																								
Потом отображаются завершенные ситуации. У данных ситуаций есть галочка о завершенности.	Требование не соответствует критерию "Полнота"																								
Есть кнопка «Здесь нет того, что я хочу».	Требование не соответствует критерию "Проверяемость"																								
																									
А также было выявлено 2 бага это :																									
																									
баги	серьзеность																								
Открытие видео при соединении интернета UMTS (3G)	Значительная																								
Включить видео в полноэкранный режим	Значительная																								
																									
Для проведение функционального и дополнительного тестирования были сформированы 3 чек-листа  (всего 63 теста) 																									
• Тестирование раздела «Ситуации» 23 теста																									
• Тестирование раздела «Видеопрактика» 24 теста																									
• Дополнительные виды тестирования 16 тесто																									
Потраченное время на тестирование 7 дней																									
																									
Вывод:																									
																									
																									
Исходя из проделанной работы по тестированию моб приложения SkyEng, прошу отправить версию моб.приложения на небольшую доработку. Так как не работает часть функционала. Прошу принять во внемание данные дефекты и вводить приложение в эксплуатацию после их устранения.																									
																							

Контактная информация
Почта-Arkham057@icloud.com
Telegram-@Arkham057

