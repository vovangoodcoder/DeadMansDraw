# Карточная игра "Карта сокровищ"  
## Правила игры

### Как играть?

В начале игры формируется колода из 50 карт, и игроки по очереди тянут столько карт, сколько хотят. Все действия происходят в открытую, то есть игроки видят, какую карту вытянул соперник. Игроки обязаны применить свойство карты, если оно имеется, как только кладут её в игровую зону. Каждая карта имеет свою стоимость и масть. Если в один заход были вытянуты две карты одинаковой масти, игрок теряет все награбленные карты в этот ход, и они отправляются в стопку сброса, после чего ход переходит другому игроку. Если же игрок решил  остановиться и не вытащил одинаковых карт, то он может совершить грабёж и завершить рейд, убрав все вытянутые карты в свой тайник. В таком случае ход передаётся следующему игроку.  

### Кто победил?

Игра заканчивается тогда, когда игрок вытягивает последнюю карту колоды. Игрок, набравший наибольшую сумму карт, объявляется победителем. В случае ничьей победителем становится тот, у кого в тайнике больше всего карт. Если их поровну, то победа делится пополам.  

### Особые карты и их свойства:

-	**Якорь:** все карты, выложенные до якоря, отправляются в тайник даже при провале хода.
-	**Кракен:** игрок обязан выложить следующую карту.
-	**Магический шар:** игрок узнаёт, какая карта будет следующей.
-	**Русалка:** не обладает особыми свойствами, но ее стоимость выше, чем у других карт.

## Описание функций приложения
1. Добор карт осуществляется нажатием на колоду, при этом должен изменяться счетчик оставшихся в колоде карт
2. Если на столе оказываются две карты одинаковой масти, то они подсвечиваются, после чего появляется сообщение о том, что ход провален
3. Кнопки завершения хода и "Начать сначала" находятся на игровом поле
4. После того, как колода закончится, выводится имя победителя и предложение начать игру заново

## Как играть
1. Скачайте проект
2. Зайдите в папку с проектом и с помощью Shift+Клик правой кнопкой мыши и открыть окно PowerShell
3. Ввести в открывшемся окне npm install (если не установлена node.js, то надо скачать установщик с официального сайта, после установки перезагрузить компьютер)
4. Ввести npm start после этого запустится сервер. Будет предложено открыть страницу в браузере. Либо перейти по адресу http://localhost:3000

Либо открыть сразу открыть в браузере по ссылке: https://py0q53oywq.codesandbox.io

