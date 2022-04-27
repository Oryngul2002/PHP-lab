
<!DOCTYPE HTML>
<html>  
<body>

<form action="welcome.php" method="post">
Name: <input type="text" name="name"><br>
E-mail: <input type="text" name="email"><br>
<input type="submit">
  <br><br>
  Gender:
  <input type="radio" name="gender" value="female">Female
  <input type="radio" name="gender" value="male">Male
  <input type="radio" name="gender" value="other">Other
  <br><br>
 echo  "<img src='https://www.google.com/url?sa=i&url=https%3A%2F%2Flifehacker.ru%2Fspecial%2Ffujifilm%2Fugaday-chto-na-foto%2F&psig=AOvVaw2SIzJMKNpAq7mHdnmgGqGc&ust=1651137395237000&source=images&cd=vfe&ved=0CAkQjRxqFwoTCLjc0qH0s_cCFQAAAAAdAAAAABAJ'>"
</form>
<?php
echo "<h2>Your Input:</h2>";
echo $name;
echo "<br>";
echo $email;
echo "<br>";
echo $gender;
echo “<br>”
?>
</body>
</html>
