# Задание 1: виджет для оценки с комментарием
В рамках тестового задания необходимо придумать, сверстать и закодить виджет для оценки. Вы могли видеть подобный виджет в конце справочных статей. С помощью него авторы статьи могут понять, была ли она полезна, либо нет.

Когда пользователь кликает на какую-то из оценок, она выделяется, нажать на неё больше нельзя.
При перезагрузке страницы, состояние виджета должно сохраняться. То есть проголосовать ещё раз мы не можем.
Если пользователь выбирает отрицательную оценку, показываем форму для отправки комментария (пользователь может написать, что стоит улучшить).

___
### План и итоговая реализация:
#### Состояния можно переключать, пока страница не будет перезагружена.

#### После перезагрузки нельзя изменить состояние если:
- был поставлен лайк
- был поставлен дизлайк и отправлена форма

#### В случае, если был поставлен дизлайк и форма не была отправлена, то после перезагруки у пользователя остается возможность отправить форму, но изменить свое решение в "оценке" формы уже не получится.
