# Ex03 Time Table
## Date:4.4.2024

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
```<!DOCTYPE html>
<html>
<head>
    <title>Timetable</title>
</head>
<body style="display: flex; flex-direction: column; align-items: center; font-size: 1.5rem;">
    <img src="saveethalogo.png" width="40%">
    <h1>PAVITHRA M(212221040119)</h1>
	<table border='3'  cellspacing="4" cellpadding='4'   style="width: 50%;">
		<tr bgcolor="yellow">
			<th>Day/Time</th>
			<th>Monday</th>
			<th>Tuesday</th>
			<th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
		</tr>
		<tr>
			<td bgcolor="orange">8-10</td>
			<td>MAD</td>
			<td>FDW</td>
            <td>MPMC</td>
            <td>FDW</td>
            <td>FREE</td>
		</tr>

		<tr>
            <td bgcolor="orange">10-12</td>
			<td>FREE</td>
			<td>SPM</td>
			<td>FREE</td>
            <td>SPM</td>
			<td>MPMC</td>
		</tr>

		<tr>
            <td bgcolor="orange">12-1</td>
			<td colspan="5" align="center" bgcolor="#808080">LUNCH</td>
			
		</tr>
		<tr>
            <td bgcolor="orange">1-3</td>
			
			<td>FREE</td>
			<td>IPR</td>
			<td>FWD</td>
			<td>CNS</td>
			<td>CNS</td>
		</tr>
		<tr>
            <td bgcolor="orange">3-5</td>
			<td>AQLR</td>
			<td>FREE</td>
			<td>IPR</td>
			<td>FREE</td>
			<td>WEB</td>
		</tr>
	</table>
    <br>
    <table border='3' cellspacing="4" cellpadding='4' style="width: 50%;">
		<tr bgcolor="orange">
			<th>S.NO</th>
			<th>Subject code</th>
			<th>Subject Name</th>
			
		</tr>
		<tr>
			<td>1.</td>
			<td>19AI414</td>
            <td>Fundamentals of Web Apllication Development(FWD)</td>
		</tr>

		<tr>
            <td>2.</td>
			<td>19ME531</td>
            <td>Intellectual property rights(IPR)</td>
		</tr>

		<tr>
            <td>3.</td>
			<td>19EC408</td>
            <td>Microprocessor and Microcontroller(MPMC)</td>
			
		</tr>
		<tr>
            <td>4.</td>
			<td>19CS412</td>
            <td>Cryptography and Network Security(CNS)</td>
		</tr>
		<tr>
            <td>5.</td>
			<td>19CS414</td>
            <td>Mobile Application Development(MAD)</td>
		</tr>
        <tr>
            <td>6.</td>
			<td>19EY704</td>
            <td>Advanced Quantitive and Logical Reasoning(AQLR)</td>
		</tr>
        <tr>
            <td>7.</td>
			<td>19CS504</td>
            <td>Software Project Management</td>
		</tr>
	</table>
	</body>
</body>
</html>
```
## OUTPUT

![Screenshot (5)](https://github.com/Pavithra-M119/slot/assets/119229774/5bb902ca-993c-4ec8-ad1d-9eeb661fb46f)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
