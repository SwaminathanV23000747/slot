# Ex03 Time Table
## Date:
13-03-24
## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```
<!DOCTYPE html>
<html>
<head>
<title>SEC Timetable</title>
</head>
<img src="sec.jpg"

<body >
    <br>
    <b>SLOT TIME TABLE - Aravind R. (212223230019)</b>
</body>
<body>
<table border="5" width="570">
<tr>
<th bgcolor="yellow">Day/Time</th>
<th bgcolor="yellow">Monday</th>
<th bgcolor="yellow">Tuesday</th>
<th bgcolor="yellow">Wednesday</th>
<th bgcolor="yellow">Thursday</th>
<th bgcolor="yellow">Friday</th>
</tr>
<tr>
<th bgcolor="yellow">8-10</th>
<th bgcolor="cyan">EN</th>
<th bgcolor="cyan">EN</th>
<th bgcolor="cyan">FWAD</th>
<th bgcolor="cyan">FREE SLOT</th>
<th bgcolor="cyan">FREE SLOT</th>
</tr>
<tr>
<th bgcolor="yellow">10-12</th>
<th bgcolor="cyan">FREE SLOT</th>
<th bgcolor="cyan">FWAD</th>
<th bgcolor="cyan">FREE SLOT</th>
<th bgcolor="cyan">CHE</th>
<th bgcolor="cyan">PHY</th>
</tr>
<tr>
<th bgcolor="yellow">12-1</th>
<th colspan="5" align="center" bgcolor="cyan">LUNCH</th>
</tr>
<tr>
<th bgcolor="yellow">1-3</th>
<td bgcolor="cyan">FWAD</th>
<th bgcolor="cyan">PY</th>
<th bgcolor="cyan">FREE SLOT</th>
<th bgcolor="cyan">FREE SLOT</th>
<th bgcolor="cyan">PY</th>
</tr>
<tr>
<th bgcolor="yellow">3-5</th>
<th bgcolor="cyan">PHY</th>
<th bgcolor="cyan">CHE</th>
<th bgcolor="cyan">FWAD</th>
<th bgcolor="cyan">PY</th>
<th bgcolor="cyan">FREE SLOT</th>
</tr>
</table>
<br>
<table border="5" width="570">
<tr>
<td>S.NO.</td>
<td>Subject Code</td>
<td>Subject Name</td>
</tr>
<tr>
<td>1.</td>
<td>19AI414</td>
<td>Fundamentals of Web Application Developement (FWAD)</td>
</tr>
<tr>
<td>2.</td>
<td>19EN101</td>
<td>Communicative Enflish (EN)</td>
</tr>
<tr>
<td>3.</td>
<td>19PH214</td>
<td>Physics for Quantum Computing (PHY)</td>
</tr>
<tr>
<td>4.</td>
<td>19CY205</td>
<td>Principles of Chemistry in Engineering (CHE)</td>
</tr>
<tr>
<td>5.</td>
<td>19AI301C</td>
<td>Python and linear Algebra (PY)</td>
</tr>
<tr>
<td>6.</td>
<td>22HS101</td>
<td>Tamil (Tam)</td>
</tr>
</table>
</body>
</html>

```
## OUTPUT
![Screenshot 2024-03-18 132950](https://github.com/SwaminathanV23000747/slot/assets/148931113/ef147c95-7449-4c62-a587-1097da72d1cf)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
