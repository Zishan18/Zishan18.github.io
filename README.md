# Zishan18.github.io
<!DOCTYPE html>
<html>
<head>
<meta charset="ISO-8859-1">
<title>Insert title here</title>
<style type="text/css">
.h11{
color: #800080;
}
#discounttable{
position: absolute;
right: 0;
}
</style>
</head>
<body bgcolor="#E6E6FA">
<h1 class="h11">E-book Grand Sale</h1>
<form action="">
<table>

<tr><td>Customer Name:</td><td><input type="text" required="required" pattern="[A-Za-z0-9].{1,}" title="Please Enter only Alphabets"></td></tr>
<tr><td>Mobile Number:</td><td><input type="number" required="required" pattern="[0-9]"></td></tr>
<tr><td>Book Category:</td><td><input name="name" type="radio">Science <input name="name" type="radio"> comic</td></tr>
<tr><td>Type:</td><td><input type="date"></td></tr>
<tr><td>No of  Required:</td><td><input type="range" min="0" max="100" step="1"></td></tr>
<tr><td><input type="button" value="Calculate Total Price"></td><td><input type="reset" value="Reset"></td></tr>
</table>
</form>
<br>
<br>
<table border="1" id="discounttable">
  <tr>
    <th>Book Type</th>
    <th>Per Book Cost</th>
    <th>Discount Rate (In percentage)</th>
  </tr>
  <tr>
    <td>Science</td>
    <td>400</td>
    <td>5% if total book count<=250</td>
  </tr>
  <tr>
    <td>Science</td>
    <td>400</td>
    <td>7% if total book count>250</td>
  </tr>
  <tr>
    <td>Comic</td>
    <td>300</td>
    <td>3% if total book count<=250</td>
  </tr>
  <tr>
    <td>Comic</td>
    <td>300</td>
    <td>4% if total book count>250</td>
  </tr>
</table>


</body>
</html>
