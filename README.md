# Игра "Виселица"

Это простая игра "Виселица", реализованная на языке Python. Игрок должен угадать слово, загаданное компьютером, вводя по одной букве. За каждую ошибку игрок теряет одну попытку, и если все попытки исчерпаны, игрок проигрывает.

## Содержание

1. [Описание игры](#описание-игры)
2. [Как запустить игру](#как-запустить-игру)
3. [Игровой процесс](#игровой-процесс)
4. [Требования](#требования)
5. [Авторы](#автор)

---

## Описание игры

Игрок пытается угадать слово, предложенное компьютером, по буквам. Каждый раз, когда игрок вводит правильную букву, она отображается в нужной позиции. Когда игрок делает ошибку, количество оставшихся попыток уменьшается, а на экране появляется изображение виселицы, которое постепенно "заполняется".

Цель игры — угадать все буквы в слове до того, как исчерпаются попытки.

### Правила:
- Игрок вводит по одной букве.
- При неправильном вводе отнимается одна попытка.
- Если все буквы угаданы до того, как закончились попытки, игрок выигрывает.
- Если попытки заканчиваются, и слово не угадано — игрок проигрывает.

---

## Как запустить игру

1. Скачайте или клонируйте этот репозиторий на свой компьютер:
    ```bash
    git clone https://github.com/yourusername/hangman-game.git
    ```

2. Перейдите в директорию с проектом:

3. Убедитесь, что у вас установлен Python 3.x. Если не установлен, скачайте его с [официального сайта Python](https://www.python.org/downloads/).

4. Запустите игру, используя shift+F10:
    

После этого начнется игра, и вам нужно будет вводить буквы в консоли.

---

## Игровой процесс

- Игра предложит вам слово, которое нужно угадать, скрытое под символами "_".
- Каждый раз, когда вы вводите букву, которая есть в слове, она будет отображаться на своем месте.
- Если буква неверная, вы потеряете одну из попыток, и виселица будет отображать следующий этап.
- Игра заканчивается, когда вы либо угадаете все буквы в слове, либо исчерпаете все попытки.

### Пример:
Текущее слово: _ _ _ _ _ _ Оставшиеся попытки: 6 Использованные буквы:

Введите букву: p Угадали букву! Текущее слово: p _ _ _ _ _ Оставшиеся попытки: 6 Использованные буквы: p

Введите букву: a Ошибка! Буквы a нет в слове. Текущее слово: p _ _ _ _ _ Оставшиеся попытки: 5 Использованные буквы: p, a


---

## Требования

- Python 3.x
- Модуль `random` (предустановлен в стандартной библиотеке Python)

---

## Автор

Проект был создан в учебных целях.

Авторы: 
Разработчики: [polnecha](https://github.com/polnecha), [embloyd](https://github.com/embloyd), [Atari7690](https://github.com/Atari7690)
