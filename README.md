# js
<

<!DOCTYPE html>
<html>
    <head>
       <meta charset="utf-8">
	
		
	 </head>
	 <body>
	
	<form action="/action_page.php">
  <label for="email">Enter your email:</label>
  <input type="email" id="email" name="email">
  <input type="submit">
 </form>
	<p>Натисніть кнопку, щоб відобразити доменне ім’я сервера, який завантажив цей документ.</p>

	<button onclick="myFunction()">Тицяй</button><br><br>

	<form action="/action_page.php">
  <label for="phone">Enter a phone number:</label><br><br>
  <input type="tel" id="phone" name="phone" placeholder="123-45-67-890" pattern="[0-9]{3}-[0-9]{2}-[0-9]{3}" required>
  <small>Format: 123-45-67-890</small><br><br>
  <input type="submit">
</form>

 <script>
	function myFunction() {
  var x = document.domain;
  document.getElementById("").innerHTML = x;
 }
 

var myDate = new Date();
document.getElementById("").innerHTML = isDate(myDate);

function isDate(myDate) {
  return myDate.constructor.toString().indexOf("Date") > -1;
}
var d = new Date();
document.getElementById("demo").innerHTML = d.getDate();
 </script>
	</body>
</html>>
