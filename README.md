В первом задании я использовала регулярное выражение: (^\s*\n*\r)|(\n) и заменила все вхождения на пустую строку: 
![](https://github.com/xristi4irina/results.txt/blob/master/%D0%B7%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5%201.jpg?raw=true)
Во втором задании я использовала регулярное выражение (^|\s)+[А-Я][а-я]*(слав). Всего упоминаний нашла 471:
![](https://github.com/xristi4irina/results.txt/blob/master/%D0%B7%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5%202.jpg?raw=true)
В третьем задании я использовала регулярное выражение (^|\s)+[Н][а-я]*(город). Всего упоминаний нашла 32:
![](https://github.com/xristi4irina/results.txt/blob/master/%D0%B7%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5%203.jpg?raw=true)
# Бонусное задание
Используя формулы ([.,:;!?])(\w) и \1 \2 , я после каждого знака препинания поставила пробелы:
![](https://github.com/xristi4irina/results.txt/blob/master/%D0%B1%D0%BE%D0%BD%D1%83%D1%81%D0%BD%D0%BE%D0%B5%20%D0%B7%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5.jpg?raw=true)
