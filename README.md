# JS_Week18
Hometask, JS Week 18, Local and Session Storage, Cookies, JSON
# Вопросы 💎

1. Сколько живет localStorage?

*До тех пор, пока не будет удалена вручную (с помощью JavaScript или очистки кэша браузера)*

2. Как посмотреть localStorage в браузере?

*Inspect → Application → Storage → Local Storage*

3. Можно ли хранить данные пользователя в sessionStorage?

*Можно, но данные хранятся там временно и когда сессия заканчивается, данные будут удалены.*

4. Как очистить локальное хранилище в браузере?

- С помощью JS window.localStorage.clear()
- C помощью очистики кэша

5. Для чего нужны куки JS?

*- Для передачи данных на сервер*

6. В чём польза cookie?

- Данные можно передать на сервес
- Можно установить срок хранения
- Небольшой объем данных (не больше 4 кБайт)
- Можно сделать защищенными

7. Как работать с cookie?

*Запись через document.cookie = ‘ключ=значение’;
Чтение через вывод document.cookie;
Удаление через присвоение expiration даты меньшей текущей;*

8. Как добавить и получить значение из веб-хранилища? 

*Добавить: window.localStorage/sessionStorage.setItem('ключ', 'значение')
Получить:window.localStorage/sessionStorage.getItem('ключ', 'значение')*

9. Придумайте ещё минимум 3 ситуации, помимо предложенных в уроке, для чего может быть нужно сохранять данные пользователя и какие? 
    
    *Пример из урока: запомнить, что пользователь уже залогинился, что у него лежит в корзине или в каком разделе сайта он сейчас находится
    
    - запомнить переписку пользователя в мессенджерах (история сообщений)
    - запомнить, какие страницы были просмотрены и использовать их потом для рекламы 
    - запомнить прогресс выполнения задач пользователем (например, в трекере задач)*
    
10. Какие преимущества использования JSON?

- удобство хранения данных
- можно использовать при работе с любым популярным языком программирования
- может использовать массивы данных
- в сочетании с AJAX он позволяет асинхронно загружать данные в фоновом режиме, что делает работу сайта более быстрой и удобной для его пользователей

11. Какие значения могут быть использованы в JSON?

*массивы, объекты, булевые значения, строки, числа, null*

12. Как брать данные из JSON?

*JSON.parse()*
