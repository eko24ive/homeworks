#Домашнее задание #8

Полезные ссылки:

 - https://www.w3schools.com/js/js_whereto.asp
 - https://www.w3schools.com/js/js_syntax.asp
 - https://www.w3schools.com/js/js_variables.asp
 - https://www.w3schools.com/js/js_arithmetic.asp
 - https://www.w3schools.com/js/js_functions.asp
 - https://www.w3schools.com/js/js_datatypes.asp
 - https://www.w3schools.com/jsref/met_document_queryselector.asp
 - https://www.w3schools.com/jsref/met_document_queryselectorall.asp
 - https://www.w3schools.com/jsref/prop_html_innerhtml.asp
 - https://www.w3schools.com/jsref/jsref_forEach.asp

В рамках этого домашнего задания вам нужно создать следуюище функции:

 - `setText(selector, text)`
 - `setTextAll(selector, text)`

### setText
 Вот пример вызов функции `setText(selector, text)`:
 
 ```javasript
 setText("p", "hi there")
 ```
Результат работы - в первом теге `<p>` текст изменится на `"hi there"`

### setTextAll

 Вот пример вызов функции `setTextAll(selector, text)`:
 
 ```javasript
 setTextAll("p", "hi there")
 ```
Результат работы - во всех тегах `<p>` текст изменится на `"hi there"`

---

Обе функции принимают следующие аргументы:

`selector` - селектор в виде строки, то есть это может быть как и `"p"` так и `"div .block a"`

`text` - текст, который мы применим к тексту селектора

---

Задание может показаться простым, но здесь есть небольшой "подводный камень" :3