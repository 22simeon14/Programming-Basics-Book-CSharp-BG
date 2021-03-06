### Задача: точка върху отсечка

Върху хоризонтална права е разположена **хоризонтална отсечка**, зададена с **x** координатите на двата си края: **first** и **second**. **Точка** е разположена **върху** същата хоризонтална права и е зададена с **x координатата** си. Напишете програма, която проверява дали точката е **вътре или вън от отсечката** и изчислява **разстоянието до по-близкия край** на отсечката.

#### Вход

От конзолата се четат **3 цели числа** (по едно на ред):
- На първия ред стои числото first – **единия край на отсечката**.
- На втория ред стои числото second – **другия край на отсечката**.
- На третия ред стои числото point – **местоположението на точката**.

Всички входни числа са цели и в диапазона [**-1000 … 1000**].

#### Изход

Резултатът да се отпечата на конзолата:
- На първия ред да се отпечата "**in**" или "**out**" – дали точката е върху отсечката или извън нея.
- На втория ред да се отпечата разстоянието от точката до най-близкия край на отсечката.

#### Примерен вход и изход

|Вход|Изход|Визуализация|
|---|---|---|
|10<br>5<br>7|in<br>2|![](/assets/chapter-8-1-images/03.Point-on-segment-01.png)|

|Вход|Изход|Визуализация|
|---|---|---|
|8<br>10<br>5|out<br>3|![](/assets/chapter-8-1-images/03.Point-on-segment-02.png)|

|Вход|Изход|Визуализация|
|---|---|---|
|1<br>-2<br>3|out<br>2|![](/assets/chapter-8-1-images/03.Point-on-segment-03.png)|