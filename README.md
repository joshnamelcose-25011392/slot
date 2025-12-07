# Ex03 Time Table
## Date:07/12/2025

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
<<html>
<head>
<title>Slot Timetable</title>
</head>
<body>
<center>
<img src="/static/logo.png" height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
<caption><b>SLOT TIME TABLE JOSHNA M (25011392)</b></caption>
<tr align="center">
<th bgcolor="yellow">Day/Time</th>
<th bgcolor="yellow">Monday</th>
<th bgcolor="yellow">Tuesday</th>
<th bgcolor="yellow">Wednesday</th>
<th bgcolor="yellow">Thursday</th>
<th bgcolor="yellow">Friday</th>
<th bgcolor="yellow">Saturday</th>
</tr>
<tr align="center">
<th bgcolor="yellow">8-10</th>
<td >PUBLIC SPEAKING</td>
<td>PUBLIC SPEAKING</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>PUBLIC SPEAKING</td>
<td>FREE SLOT</td>
</tr>
<tr align="center">
<th bgcolor="yellow">10-12</th>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
<td> FREE SLOT</td>
<td>PUBLIC SPEAKING</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FUNDAMENTALS OF C PROGRAM</td>
</tr>
<tr>
<th bgcolor="yellow">12-1</th>
<td colspan="5" align="center">LUNCH</td>
</tr>
<tr align="center">
<th bgcolor="yellow">1-3</th>
<td >FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT </td>
<td>FUNDAMENTALS OF C PROGRAM</td>
<td>FREE SLOT</td>
<td>FUNDAMENTALS OF WEB APPLICATION</td>
<td>FUNDAMENTALS OF C PROGRAM</td>
<td>FREE SLOT</td>
</tr>
<tr align="center">
<th bgcolor="yellow">3-5</th>
<td> FUNDAMENTALS OF C PROGRAM</td>
<td>FREE SLOT</td>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
<td>FREE SLOT</td>
<td>FUNDAMENTALS OF C PROGRAM</td>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19A1414</td>
<td>Fundamentals of Web Application Development (FWAD)</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19A1304</td>
<td>FUNDAMENTALS OF C PROGRAMMING (C PROGRAM) </td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19EN105</td>
<td>PUBLIC SPEAKING</td>
</tr>
</table>
</body>
</html>
```


## OUTPUT
<img width="1919" height="958" alt="Screenshot 2025-12-07 215702" src="https://github.com/user-attachments/assets/dbf6a9b3-085b-4f25-8718-778682fc7108" />



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
