Этот тег HTML предназначен для группирования элементов формы. Это облегчает работу с формами, содержащими большое количество данных.

### Синтаксис:
```html
<form>
	<fildset>...</fildset>
</form>
```

### Атрибуты:

- [[disabled]]
Блокирует поля формы в группе.

- [[form]]
Связывает группу с формой.

- [[title]]
Добавляет всплывающую подсказку к группе формы.

### Пример
```html
<!DOCTYPE HTML>
<html>
 <head>
  <meta charset="utf-8">
  <title>Тег FIELDSET</title>
 </head>
 <body>  

 <form action="handler.php">
  <fieldset>
   <legend>Работа со временем</legend>
     <input type="checkbox"> создание пунктуальности (никогда не 
      будете никуда опаздывать);<br>
     <input type="checkbox"> излечение от пунктуальности (никогда 
      никуда не будете торопиться);<br>
     <input type="checkbox"> изменение восприятия времени и часов.
      <p><input type="submit"></p>
  </fieldset>
 </form> 

 </body>
</html>
```