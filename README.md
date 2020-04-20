## Мастерская "Интерактивный словарь (сленга)"

**Руководитель:** Даша Попова ([почта](mailto:daschapopowa@gmail.com))

**Участники:**
* прошлого года:
  - Валерия Морозова ([почта](mailto:tito_alba@mail.ru)), 
  - Тимур Жетписов ([почта](mailto:volponebt@gmail.com)),
  - Эдуард Григорьев ([почта](mailto:happypuffin7@gmail.com)), 
  - Наталья Озерчук ([почта](mailto:fishow36@gmail.com)),
  - Анастасия Макунина ([почта](mailto:asetorn@gmail.com)),
  - Галина Рязанская ([почта](mailto:galka1999@gmail.com)) (пока на стажировке)
* этого года:
  - Леонова Елизавета ([почта](mailto:eeleonova_1@edu.hse.ru))
  - Анна Им ([почта](mailto:akim_1@edu.hse.ru))
  - Анна Евтодиева ([почта](mailto:aniatta1999@gmail.com))

#### Описание проекта:

Словарь, в который каждый желающий может добавить слово, его определение, примеры, и поставить лайк/дислайк добавленным определениям.

#### Задачи:

1. <a href="./db_maker/">База данных</a> с полями -- слово, определение, пример, метаинфа про добавившего (ник, город, дата) -- сделана, Лера

2. [веб-интерфейс](https://github.com/fishow36/Interactive-Dictionary), где есть: -- сделано, Наташа, Эдуард

3. функция поиска (если слово есть, то выдаёт список всех имеющихся для него определений; если слова нет, то отсылает к форме добавления слова, где есть поля 'слово|определение|пример|ник|город|дата', когда мы сделаем авторизацию, то метаинфа будет сохраняться автоматически)

4. функция добавления слова в базу данных: проверяет, есть ли слово в БД, если нет, то добавляет все поля 'слово|определение|пример|ник|город|дата'; если слово есть в БД, то добавляются поля 'определение|пример|ник|город|дата'

5. [список слов с определениями и с примерами для последующего добавления в словарь](https://docs.google.com/document/d/1Hsk6Wy5AaYlIgYOE2jQjxuJY2huhjQetD9_HcYsppNU/edit?usp=sharing) -- сделано, Настя, Тимур

6. возможность ставить лайки и дислайки определениям и счётчик лайков и дислайков -- почти сделано, Лиза ([пока что лайки привязываются к словам](https://github.com/luckysandra/Interactive-Dictionary))

7. авторизация пользователей -- сделано, [Аня](https://github.com/Gratisfo/Interactive-Dictionary)

7. в планах:
+ сортировка по популярности для определений одного слова;
+ возможность авторизации пользователей


#### На какие моменты мы хотели бы получить реакцию рецензета:

+ достаточно ли мы собираем метаинфы (ник, город, дата)?
+ нужны ли тэги -- "сленг", "мат", "диалект", "заимствование" и т.д.?
+ нужна ли возможность ставить дислайки определениям, или достаточно лайков? или другая система поощрения будет более адекватной?
+ нужна ли опция поиска по алфавиту, поиска по популярности поиска?
+ нужна ли цензура того, что добавляют пользователи? (например, можно удалять определения, не набравшие ни одного лайка; ввести стоп-слова и т.п.)

**Заранее большое спасибо за комментарии!**
