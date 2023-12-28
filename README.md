<h1 align="center"> МИНИСТЕРСТВО НАУКИ И ВЫСШЕГО ОБРАЗОВАНИЯ РОССИЙСКОЙ ФЕДЕРАЦИИ ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ОБРАЗОВАНИЯ «САХАЛИНСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ»</h1>
<br>
<br>
<br>
<br>
<br>
<br>
<p align="center">Лабораторная работа №7</p>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<p align="right">Выполнил: Шандро Никита Богданович</p>
<p align="right">Проверил: Соболев Е. И.</p>
<br>
<br>
<br>
<br>
<br>
<br>

<p align="center">г. Южно-Сахалинск <br> 2023 год</p>

<h2 align="center">Введение</h2>
<p align="justify">Разработка серверных скриптов.</p>

<h2>Цели и задачи</h2>
1.	Создайте переменную $var и присвойте ей значение 'hello'. Обращаясь к отдельным символам этой строки выведите на экран символ 'h', символ 'e', символ 'o'.
<br>
2.	Напишите скрипт, который считает количество секунд в часе.
<br>
3.	Переделайте приведенный код так, чтобы в нем использовались операции +=, -=, *=, /=, ++, --. Количество строк кода при этом не должно измениться. Код для переделки:

```php
<?php
$var = 1;
$var = $var + 12;
$var = $var - 14;
$var = $var * 5;
$var = $var / 7;
$var = $var + 1;
$var = $var - 1;
echo $var;
?>
```
<br>
4.	Создайте переменную $a и присвойте ей значение 3. Выведите значение этой переменной на экран.
<br>
5.	Создайте переменные $a=10 и $b=2. Выведите на экран их сумму, разность, произведение и частное (результат деления).
<br>
6.	Создайте переменные $c=15 и $d=2. Просуммируйте их, а результат присвойте переменной $result. Выведите на экран значение переменной $result.
<br>
7.	 Создайте переменные $a=10, $b=2 и $c=5. Выведите на экран их сумму.
<br>
8.	Создайте переменные $a=17 и $b=10. Отнимите от $a переменную $b и результат присвойте переменной $c. Затем создайте переменную $d, присвойте ей значение 7. Сложите переменные $c и $d, а результат запишите в переменную $result. Выведите на экран значение переменной $result.
<br>
9.	Создайте переменную $text и присвойте ей значение 'Привет, Мир!'. Выведите значение этой переменной на экран.
<br>
10.	 Создайте переменные $text1='Привет, ' и $text2='Мир!'. С помощью этих переменных и операции сложения строк выведите на экран фразу 'Привет, Мир!'.
<br>
11.	 Создайте переменную $name и присвойте ей ваше имя. Выведите на экран фразу 'Привет, %Имя%!'. Вместо %Имя% должно стоять ваше имя.
<br>
12.	 Создайте переменную $age и присвойте ей ваш возраст. Выведите на экран 'Мне %Возраст% лет!'.
<br>
13.	Создайте переменную $text и присвойте ей значение 'abcde'. Обращаясь к отдельным символам этой строки выведите на экран символ 'a', символ 'c', символ 'e'.
<br>
14.	 Дана произвольная строка, например, 'abcde'. Поменяйте первую букву (то есть букву 'a') этой строки на '!'.
<br>
15.	 Создайте переменную $num и присвойте ей значение '12345'. Найдите сумму цифр этого числа.
<br>
16.	Напишите скрипт, который считает количество секунд в часе, в сутках, в месяце.
<br>
17.	 Создайте три переменные - час, минута, секунда. С их помощью выведите текущее время в формате 'час:минута:секунда'.
18.	 Создайте переменную, присвойте ей число. Возведите это число в квадрат (это значит нужно умножить его само на себя). Выведите его на экран.
<br>
19.	Переделайте этот код так, чтобы в нем использовались операции +=, -=, *=, /=. Количество строк кода при этом не должно измениться.

```php
$var = 47;
$var = $var + 7;
$var = $var - 18;
$var = $var * 10;
$var = $var / 20;
echo $var;
```
<br>
20.	 Переделайте этот код так, чтобы в нем использовалась операция .=. Количество строк кода при этом не должно измениться.

```php
$text = 'Я';
$text = $text.' хочу';
$text = $text.' знать';
$text = $text.' PHP!';
echo $text;
```
<br>
21.	 Переделайте этот код так, чтобы в нем использовались операции ++ и --. Количество строк кода при этом не должно измениться.

```php
$var = 10;
$var = $var + 1;
$var = $var + 1;
$var = $var - 1;
echo $var;
```
<br>
22.	 Переделайте этот код так, чтобы в нем использовались операции ++, -- , +=, -=, *=, /=. Количество строк кода при этом не должно измениться.

```php
$var = 10;
$var = $var + 7;
$var = $var + 1;
$var = $var - 1;
$var = $var + 12;
$var = $var * 7;
$var = $var - 15;
echo $var;
```
<br>
https://www.codewars.com/kata/534ea96ebb17181947000ada
https://www.codewars.com/kata/5552101f47fc5178b1000050
https://www.codewars.com/kata/52988f3f7edba9839c00037d
https://www.codewars.com/kata/5506b230a11c0aeab3000c1f
https://www.codewars.com/kata/57bf599f102a39bb1e000ae5
https://www.codewars.com/kata/5901f361927288d961000013
https://www.codewars.com/kata/546f922b54af40e1e90001da
https://www.codewars.com/kata/5679aa472b8f57fb8c000047
https://www.codewars.com/kata/57a2013acf1fa5bfc4000921
https://www.codewars.com/kata/5a995c2aba1bb57f660001fd
https://www.codewars.com/kata/57ed30dde7728215300005fa
https://www.codewars.com/kata/582746fa14b3892727000c4f
https://www.codewars.com/kata/5b39e3772ae7545f650000fc
<br>
<br>
Задачи Node JS
Написать скрипт для парсинга данных с веб-страницы и сохранения их в базу данных.
Написать скрипт для отправки электронной почты через SMTP-сервер.
Создать простой микросервис для генерации QR-кодов.


<h2>Решение задач</h2>

### PHP

```php
// 1.
echo '1 задание.<br><br>';
$var = 'hello';
echo $var[0] . $var[1] . $var[strlen($var) - 1];

// 2.
echo '<br><br><br> 2 задание.<br><br>';
echo 'Количество секунд в часе = ' . 60 * 60;

// 3.
echo '<br><br><br> 3 задание.<br><br>';
$var = 1;
$var += 12;
$var -= 14;
$var *= 5;
$var /= 7;
$var += 1;
$var -= 1;
echo $var;

// 4.
echo '<br><br><br> 4 задание.<br><br>';
$a = 3;
echo $a;

// 5.
echo '<br><br><br> 5 задание.<br><br>';
$a = 10;
$b = 2;
echo $a + $b;
echo $a - $b;
echo $a * $b;
echo $a / $b;

// 6.
echo '<br><br><br> 6 задание.<br><br>';
$c = 15;
$d = 2;
$result = $c + $d;
echo $result;

// 7.
echo '<br><br><br> 7 задание.<br><br>';
$a = 10;
$b = 2;
$c = 5;
echo $a + $b + $c;

// 8.
echo '<br><br><br> 8 задание.<br><br>';
$a = 17;
$b = 10;
$c = $a - $b;
$d = 7;
echo $result = $c + $d;

// 9.
echo '<br><br><br> 9 задание.<br><br>';
echo $text = 'Привет, Мир!';

// 10.
echo '<br><br><br> 10 задание.<br><br>';
echo $text1 = 'Привет, ' . $text2 = 'Мир!';

// 11.
echo '<br><br><br> 11 задание.<br><br>';
$name = 'Артем';
echo "Привет, $name!";

// 12.
echo '<br><br><br> 12 задание.<br><br>';
$age = 18;
echo "Мне $age лет!";

// 13.
echo '<br><br><br> 13 задание.<br><br>';
$text = 'abcde';
echo $text[0] . $text[1] . $text[-1];

// 14.
echo '<br><br><br> 14 задание.<br><br>';
$text[0] = '!';
echo $text;

// 15.
echo '<br><br><br> 15 задание.<br><br>';
$num = '12345';
echo array_sum(str_split($num));

// 16.
echo '<br><br><br> 16 задание.<br><br>';
echo 'Количество секунд в часе: ' . 60 * 60 . '<br>';
echo 'Количество секунд в сутках: ' . 60 * 60 * 24 . '<br>';
echo 'Количество секунд в месяце: ' . 60 * 60 * 24 * 30 . '<br>';

// 17.
echo '<br><br><br> 17 задание.<br><br>';
$hour = 11;
$min = 15;
$sec = 42;
echo "$hour:$min:$sec";

// 18.
echo '<br><br><br> 18 задание.<br><br>';
$num = 5;
echo $num * $num;

// 19.
echo '<br><br><br> 19 задание.<br><br>';
$var = 47;
$var += 7;
$var -= 18;
$var *= 10;
$var /= 20;
echo $var;

// 20.
echo '<br><br><br> 20 задание.<br><br>';
$text = 'Я';
$text .= ' хочу';
$text .= ' знать';
$text .= ' PHP!';
echo $text;

// 21.
echo '<br><br><br> 21 задание.<br><br>';
$var = 10;
$var++;
$var++;
$var--;
echo $var;

// 22.
echo '<br><br><br> 22 задание.<br><br>';
$var = 10;
$var += 7;
$var++;
$var--;
$var += 12;
$var *= 7;
$var -= 15;
echo $var;
  
```

### MAIL

```js
const nodemailer = require('nodemailer');

// Настройте транспорт (SMTP)
const transporter = nodemailer.createTransport({
  host: 'host',
  port: port,
  auth: {
    user: 'user', // Ваш адрес электронной почты
    pass: 'pass' // Ваш пароль от почты
  }
});

// Настройте параметры письма
const mailOptions = {
  from: 'nkpiyhxv@rambler.ru', // Ваш адрес электронной почты
  to: 'nikitashandro@gmail.com', // Адрес получателя
  subject: 'Тема вашего письма',
  text: 'Текст вашего письма'
};

// Отправьте письмо
transporter.sendMail(mailOptions, (error, info) => {
  if (error) {
    console.error('Ошибка отправки письма:', error);
  } else {
    console.log('Письмо успешно отправлено:', info.response);
  }
});
```

### QR
```js
const express = require('express');
const QRCode = require('qrcode');

const app = express();

app.get('/generate', async (req, res) => {
  const url = req.query.url;

  if (!url) {
    return res.status(400).send('URL не указан.');
  }

  try {
    const qr = await QRCode.toDataURL(url);
    res.send(`<img src="${qr}" />`);
  } catch (err) {
    res.status(500).send('Ошибка при создании QR-кода.');
  }
});
app.get('/', async (req, res) => {
    res.send("Создание QR-кода. Пример:/generate?url=https://github.com/shandro0")
  });

app.listen(3000, () => {
  console.log(`Сервер запущен на порту 3000`);
});
//http://localhost:3000/generate?url=https://github.com/shandro0

```

### DB
```js
const axios = require('axios');
const mysql = require('mysql');

// Создание подключения к базе данных
const connection = mysql.createConnection({
  host: 'host',
  user: 'user',
  password: 'password',
  database: 'database'
});

// Установка соединения с базой данных
connection.connect((err) => {
  if (err) {
    console.error('Ошибка подключения к базе данных:', err);
  } else {
    console.log('Успешное подключение к базе данных');
  }
});

// Функция для парсинга данных с веб-страницы и сохранения их в базе данных
async function parseData(name) {
  try {
    const response = await axios.get(`https://api.genderize.io?name=${name}`);
    const { name: responseName, gender, probability, count } = response.data;

    // Создание SQL-запроса для вставки данных в базу данных
    const query = `INSERT INTO users (name, gender, probability, count) VALUES (?, ?, ?, ?)`;
    const values = [responseName, gender, probability, count];

    // Выполнение SQL-запроса
    connection.query(query, values, (err, result) => {
      if (err) {
        console.error('Ошибка при выполнении SQL-запроса:', err);
      } else {
        console.log('Данные успешно сохранены в базе данных');
      }
    });
  } catch (error) {
    console.error('Ошибка при парсинге данных:', error);
  }
}

// Вызов функции для парсинга и сохранения данных
parseData('John');
```

<h2>Вывод</h2>
В этой лабораторной работе я научился работать с PHP и javascript.
