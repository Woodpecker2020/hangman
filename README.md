### Игра "Виселица"
------

Язык программирования: **Ruby**


#### Условия игры

Программа случайным образом выбирает слово из имеющегося набора (загадывает). 
Пользователю нужно отгадать слово указывая возможные буквы этого слова. 
При отгадывании можно допустить до 6 ошибок, на 7 ошибке игра заканчивается. 
Процесс игры сопровождается интерфейсом с виселицей, которую обычно рисуют 
во время игры на бумаге.


#### Пример интерфейса

```
  Слово: К О __ О __ __
  _______
  |/
  |     ( )
  |      |
  |
  |
  |
  |
  |
__|________
|         |

Ошибки (2): Х, У
У вас осталось ошибок: 5

Введите следующую букву:
```


#### Запуск программы

`ruby main.rb`


#### Список слов

Список слов можно дополнить или изменить в файле `/data/words.txt`. Буквы слов необходимо 
записывать **в верхнем регистре** !


#### Особенности игры

Буквы Е и Ё считаются равнозначными, также как И и Й.
