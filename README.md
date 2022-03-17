# hangman_normalized
Hangman game
Компьютер загадывает слово (из списка в файле) и показывает, сколько в нем букв.
Игрок вводит буквы по одной. Если буква есть в слове, компьютер показывает, сколько раз она в нем
встречается и на каких местах. Если буквы нет, компьютер засчитывает ошибку. Если слово отгадано
полностью, игрок победил. После каждой ошибки, дорисовывается виселица. Всего можно сделать 7 ошибок.

Список слов для отгадывания хранится в файле `words.txt` в папке `data`. Так что меняйте слова в этом файле, 
чтобы разнообразить игру.

Программа написана на Ruby. Чтобы запустить ее, напишите в консоли:
```
ruby main.rb
```
