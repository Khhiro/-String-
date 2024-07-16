# ЧТО ТАКОЕ `методы string на JS`.

![alt text](https://i.redd.it/qjn4q16b2yw51.png)


В JavaScript есть метода для получения подстроки: substring , substr и slice . Возвращает часть строки от start до (не включая) end . Возвращает часть строки между start и end (не включая) end . Это — почти то же, что и slice , но можно задавать start больше end .



<br>

### 1. `CharAt` 
char charAt(int index) возвращает значение char по указанному индексу. Индекс колеблется от 0 до length()-1.

![](https://media.dev.to/cdn-cgi/image/width=1080,height=1080,fit=cover,gravity=auto,format=auto/https%3A%2F%2Fdev-to-uploads.s3.amazonaws.com%2Fuploads%2Farticles%2Fej885r0tq28kud0cw73e.png)

<br>




### 2. `concat`

Метод concat() возвращает новый массив, состоящий из массива, на котором он был вызван, соединённого с другими массивами и/или значениями, переданными в качестве аргументов.

![alt text](https://prepbytes-misc-images.s3.ap-south-1.amazonaws.com/assets/1688973771638-Topic%20%283%29.jpg)


```cs
const array1 = ['a', 'b', 'c'];
const array2 = ['d', 'e', 'f'];
const array3 = array1.concat(array2);

console.log(array3);
``` 
<br>

### 2. `replace`

Метод replace() предназначен для простой замены символьных литералов, тогда как replaceAll() использует регулярные выражения для реализации более сложной леханики поиска и замены.
В примере для replace():

![alt text](https://www.homeandlearn.co.uk/java/images/strings/replace.gif)

```cs
String result = "foo".replace("oo", "ood"); // Результат: "food" (в переводе "еда")
```
