<html>
<head><title>Existing</title>
<style>
body{
background-image:url("world.jpg");
background-repeat:no repeat;
}
</style>
</head>
<body>
<form action="cost.php" method='post'>
</br></br></br>
<table align="center">
<th colspan="2">Enter travelling details</th>`
<tr><td>Boarding point</td><td><select name="board">
<option value="mum">Mumbai</option>
<option value="tpt">Tirupati</option>
<option value="hyd">Hyderabad</option>
<option value="che">Chennai</option>
<option value="bgr">Banglore</option></select></td></tr>
<tr><td>Destination</td><td><select name="dest">
<option value="pune">Pune</option>
<option value="jai">Jaipur</option>
<option value="del">Delhi</option>
<option value="ko">Kolkata</option>
<option value="nag">Nagpur</option></select></td></tr>
<tr><td>Mode of transport</td><td><select name="mode">
<option value="bus">Bus</option>
<option value="tr">Train</option>
<option value="fli">Flight</option>
<option value="car">Car</option></select></td></tr>
<tr><td>Departure date</td><td><input type="date"></td></tr>
<tr><td>Departure time</td><td><input type="time"></td></tr>
<tr><td>No.of persons</td><td><input type="number"></td></tr>
<tr><td><a href="cost.php" target="_self"><input type="Submit" value="Next"></a></td><td><input type="reset"></td></tr>
</table>
</form>
</br></br>
<a href="scam.php"><center><font size="5">Back to main page</font></center></a>
</body>
</html>
