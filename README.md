![Screenshot (10)](https://github.com/Mohamedasils/slot1/assets/144870445/b44f8dda-23d3-4b2c-b063-36f2931c7099)# Ex03 Time Table
## Date:14/11/23
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
<html>

<head>
<title> Time Table </title>
</head>

<body>

<center>
<img src="/static/logo.png" height="100" width="540">
</center>
<br>

<table align="center" width="800" cellspacing="3" cellpadding="14" border="2" bgcolor="black">
<caption> <b> SLOT TIME TABLE - MOHAMED ASIL S(23013491) </b> </caption>

<tr align="center">
<th bgcolor="white"> Day / Time </th>
<th bgcolor="white"> 8 - 10 </th>
<th bgcolor="white"> 10 - 12 </th>
<th bgcolor="white"> 12 - 1 </th>
<th bgcolor="white"> 1 - 3 </th>
<th bgcolor="white"> 3 - 5 </th>
</th>

<tr align="center">
<th bgcolor="white"> Monday </th>
<td bgcolor="pink"> Free Slot </td>
<td bgcolor="pink">Basic Electrical,Electonics and Measurement Engineering</td>
<td rowspan="5" bgcolor="pink"> Lunch </td>
<td bgcolor="pink"> Principle's of Chemistry in Engineering </td>
<td bgcolor="pink"> Free Slot </td>
</tr>

<tr align="center">
<th bgcolor="white"> Tuesday </th>
<td bgcolor="pink"> Basic Electrical,Electonics and Measurement Engineering</td>
<td bgcolor="pink"> Soft Skill</td>
<td bgcolor="pink"> Engineering Design And Modelling </td>
<td bgcolor="pink"> Free Slot </td>
</tr>

<tr align="center">
<th bgcolor="white"> Wednesday </th>
<td bgcolor="pink"> Fundamentals of Web Application Development </td>
<td bgcolor="pink"> Python Programing </td>
<td bgcolor="pink"> Principle's of Chemistry in Engineering </td>
<td bgcolor="pink"> Calculas Matrix </td>
</tr>

<tr align="center">
<th bgcolor="white"> Thursday </th>
<td bgcolor="pink"> Engineering Design And Modelling </td>
<td bgcolor="pink"> Fundamentals of Web Application Development </td>
<td bgcolor="pink"> Python Programming </td>
<td bgcolor="pink"> Free Slot </td>
</tr>

<tr align="center">
<th bgcolor="white"> Friday </th>
<td colspan="2" align="centre" bgcolor="pink"> Free Slot </td>

<td bgcolor="pink"> Fundamentals of Web Application Development </td>
<td bgcolor="pink"> Calculas Matrix </td>
</tr>
</table>
<br>
<br>

<table align="center" cellspacing="3" cellpadding="15" border="2" bgcolor="black">

<tr align="center">
<th bgcolor="white"> S.No. </th>
<th bgcolor="white"> Subject Code </th>
<th bgcolor="white"> Subject Name </th>
</tr>

<tr>
<th align="center" bgcolor="pink"> 1. </th>
<td align="center" bgcolor="pink"> 19AI414 </td>
<td bgcolor="pink"> Fundamentals of Web Application Development </td>
</tr>

<tr>
<th align="center" bgcolor="pink"> 2. </th>
<td align="center" bgcolor="pink"> 19MA201 </td>
<td bgcolor="pink"> Calculas Matrix </td>
</tr>

<tr>
<th align="center" bgcolor="pink"> 3. </th>
<td align="center" bgcolor="pink"> 19CY205 </td>
<td bgcolor="pink"> Principle's of Chemistry in Engineering </td>
</tr>

<tr>
<th align="center" bgcolor="pink"> 4. </th>
<td align="center" bgcolor="pink"> 19AI302 </td>
<td bgcolor="pink"> Engineering Design and Modeling </td>
</tr>

<tr>
<th align="center" bgcolor="pink"> 5. </th>
<td align="center" bgcolor="pink"> 19EE305 </td>
<td bgcolor="pink"> Basic Electrical,Electronics and Measurement Engineering </td>
</tr>

<tr>
<th align="center" bgcolor="pink"> 6. </th>
<td align="center" bgcolor="pink"> 19EY701 </td>
<td bgcolor="pink"> Soft Skill </td>
</tr>

<tr>
<th align="center" bgcolor="pink"> 7. </td>
<td align="center" bgcolor="pink"> 19AI301 </td>
<td bgcolor="pink"> Python Programming </td>
</tr>

</body>
</html>


```

## OUTPUT
![Screenshot (9)](https://github.com/Mohamedasils/slot1/assets/144870445/e1033a1b-f487-4d9c-815a-86a04bd30124)
![Screenshot (10)](https://github.com/Mohamedasils/slot1/assets/144870445/f9116216-9621-432a-87b1-b3a0261a167a)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
