### Насоки и подсказки

Вероятно е подобно условие да изглежда на пръв поглед **объркващо** и непълно, което **придава** допълнителна **сложност** на една лесна задача. Нека **разделим** заданието на няколко **подзадачи** и да се опитаме да **решим** всяка една от тях, което ще ни отведе и до крайния резултат:

* Нека **първата** подзадача бъде да **прочетем входните данни**, които потребителя въвежда, и да ги **запазим в подходящи променливи**.
* **Изпълнение** на основната програмна **логика**, което в нашия случай се свежда до прости пресмятания на данните, които вече имаме.
* **Пресмятане** и оформяне на крайния **резултат**.

**Съществената** част от програмната логика **се изразява** в това да **пресметнем** какво ще бъде **изминатото разстояние след всички промени** в скоростта. Тъй като по време на **изпълнението** на програмата, част от **данните**, с които разполагаме, **се променят**, то бихме могли да **разделим** програмния **код** на няколко **логически** обособени **части**:

* **Пресмятане** на изминатото **разстояние** с първоначална скорост.
* Промяна на **скоростта** и пресмятане на изминатото **разстояние**.
* Последна промяна на **скоростта** и **пресмятане**.
* **Сумиране**.