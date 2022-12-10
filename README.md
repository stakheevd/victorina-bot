# victorina-bot

## Курсовая работа по Конструированию ПО 

3530904/00104 
1. Зубарев 
2. Смирнов
3. Стахеев

### 1 Этап  
**Постановка задачи**  
Решается проблема избытка время досуга. Организовывается времяпрепровождение с друзьями как онлайн, так и оффлайн. И проверяется, у кого шире кругозор в соревновательном формате. 

**Описание**  
Телеграм бот онлайн-игры в викторину. Пользователь-создатель создает сессию, к ней подключаются остальные игроки. Создатель начинает игру. Каждый игрок за отведенное время должен ответить на очередной вопрос. За каждый правильный ответ игрок получает очки. Игрок, набравший больше всех очков, побеждает в игре. После этого создатель может начать новую игру или завершить сессию.

***

### 2 Этап   
**Описание**   
Телеграм бот онлайн-игры в викторину. Пользователь-создатель создает сессию, к ней подключаются остальные игроки. Создатель начинает игру. Каждый игрок должен ответить на очередной вопрос. За каждый правильный ответ игрок получает очки. Игрок, набравший больше всех очков, побеждает в игре. После этого создатель может начать новую игру или завершить сессию.

1. Пользователь заходит в чат к боту и инициализирует сессию
2. Администратор получает ключ
3. Администратор выбирает тему, кол-во игроков, кол-во вопросов
4. Администратор ждет в лобби (не больше установленного кол-ва P игроков)
5. Игроки заходят в лобби по коду команты
6. Администратор начинает игра
7. Процесс игры:   
 a. Выводится вопрос и варианты ответов  
 b. Игроки выбирают ответы и накапливают очки за правильные ответы  
 c. После M вопросов игра заканчивается  
 d. Выводится рейтинг игроков по кол-ву очков (LeaderBoard)   
8. Администратор может закрыть комнату или начать новую игру в этой же комнате (пункт 7) 

**Cхема**  
![2 этап](https://user-images.githubusercontent.com/90210620/205923544-cbc8befc-a365-48d0-a1f8-d0036e91bffd.png)

***

### 3 Этап   
**Разработка архитектуры и детальное проектировани**  
System context diagram:   
<img width="353" alt="3 " src="https://user-images.githubusercontent.com/90210620/205928415-be865e62-5bb9-43b8-a48e-5164299db526.png">

Container diagram:   
<img width="547" alt="3 1" src="https://user-images.githubusercontent.com/90210620/205928503-bd7e744a-e487-41a4-ab47-dab9cbc6a339.png">

***

### 4 Этап  
**Исходный код**  
**Используемые технологии**
Для CI используются GitHub Actions, yaml скрипты: тестов, сборки и деплоя можно посмотреть в .github/workflows

***

### 5 Этап   
**Unit тесты**  

***

### 6 Этап  
**CI**
