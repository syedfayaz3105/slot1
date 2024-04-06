![image](https://github.com/syedfayaz3105/slot1/assets/147144126/6144010b-ea79-4d9a-b9ec-5a67e89c43d5)# Ex03 Time Table
## Date:30/03/2024

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
<html>
<head>
<title>Slot Timetable</title>
</head>
<body>
<center>
<img src="/static/logo.png" height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
<caption><b>SCHEDULE OF ALL COURSES</b></caption>
<tr align="center">
<th bgcolor="yellow">Day/Time</th>
<th bgcolor="yellow">Monday</th>
<th bgcolor="yellow">Tuesday</th>
<th bgcolor="yellow">Wednesday</th>
<th bgcolor="yellow">Thursday</th>
<th bgcolor="yellow">Friday</th>
<th bgcolor="yellow">saturday</th>
</tr>
<tr align="center">
<th bgcolor="yellow">8-10</th>
<td >FWAD</td>
<td>Chemistry</td>
<td>BEEM</td>
<td>Free Slot</td>
<td>Free Slot</td>
<td> Chemistry</td>
</tr>
<tr align="center">
<th bgcolor="yellow">10-12</th>
<td>OS</td>
<td>FREE SLOT </td>
<td>PROBABILITY</td>
<td>FREE SLOT</td>
<td>C PROG</td>
<td>FREE SLOT</td>
</tr>
<tr>
<th bgcolor="yellow">12-1</th>
<td colspan="5" align="center">L U N C H</td>
</tr>
<tr align="center">
<th bgcolor="yellow">1-3</th>
<td >BEEM </td>
<td>FREE SLOT</td>
<td>OS</td>
<td>FWAB</td>
<td> FWAB</td>
<td> PROBABILITY</td>
</tr>
<tr align="center">
<th bgcolor="yellow">3-5</th>
<td > C PROG</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td> Free Slot</td>
<td> Free Slot</td>
</tr>
<tr align="center">
<th bgcolor="yellow">5-7</th>
<td>EMPD</td>
<td> FREE SLOT</td>
<td>FREE SLOTt</td>
<td>EMPD</td>
<td> FREE SLOT</td>
<td> FREE SLOT</td>
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
<td align="center">19CS405</td>
<td>Operating System(OS)</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI304</td>
<td>Fundamentals of C programming(C PROGRAM)</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19AI414</td>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT (FWAD)</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19CY205</td>
<td>Principles of Chemistry in Engineering (CHE)</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19MA222</td>
<td> Probability and queing modelling</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19EE305</td>
<td>BEEM</td>
</tr>
</table>
</body>
</html>

'''


## OUTPUT

![Screenshot (167)](https://github.com/syedfayaz3105/slot1/assets/147144126/9aadb8eb-7941-4f9f-ae9b-b70ed0220334)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
