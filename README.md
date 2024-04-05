# Ex03 Time Table
## Date:31.10.2023

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
    <center>
        <img src="/static/logo.png" height="100" width="500">
    </center>
    <body >
        <hr>
		<table align="center" width="500" cellspacing="2" cellpadding="4" border="5" bgcolor="purple">	
			<caption><b>SLOT TIME TABLE - HEMA LOKITHA P(23007550)</b></caption>
			<tr align="center">
				<th bgcolor="yellow">Day/Time</th>
				<th bgcolor="yellow">Monday</th>
				<th bgcolor="yellow">Tuesday</th>
				<th bgcolor="yellow">Wednesday</th>
				<th bgcolor="yellow">Thursday</th>
				<th bgcolor="yellow">Friday</th>
			</tr>
            <tr align="center">
				<th bgcolor="yellow">8-10</th>
				<td>English</td>
				<td>English</td>
				<td>Web</td>
				<td>Softskills</td>
				<td>Python</td>
			</tr>
            <tr align="center">
				<th bgcolor="yellow">10-12</th>
				<td></td>
				<td>Python</td>
				<td></td>
				<td>Web</td>
				<td></td>
			</tr>
            <tr align="center">
				<th bgcolor="yellow">12-1</th>
				<td colspan="5">L U N C H</td>
			</tr>
            <tr align="center">
				<th bgcolor="yellow">1-3</th>
				<td>Chemistry</td>
				<td></td>
				<td>Chemistry</td>
				<td></td>
				<td>Web</td>
			</tr>
            <tr align="center">
				<th bgcolor="yellow">3-5</th>
				<td></td>
				<td></td>
				<td>Python</td>
				<td>Web</td>
				<td></td>
			</tr>
		</table>
        <br>
        <br>
        <table align="center" width="500" cellspacing="2" cellpadding="4" border="5" >
            <tr align="center">
                <th>S.No</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
            <tr>
                <td>1</td>
                <td>19AI414</td>
                <td>Fundamentals Of Web Development</td>
            </tr>
            <tr>
                <td>2</td>
                <td>19AI301</td>
                <td>Python And Linear Algebra</td>
            </tr>
            <tr>
                <td>3</td>
                <td>19EN101</td>
                <td>Communicate English</td>
            </tr>
            <tr>
                <td>4</td>
                <td>19CY205</td>
                <td>Principles Of Chemistry In Engineering</td>
            </tr>
            <tr>
                <td>5</td>
                <td>19EY701</td>
                <td>Soft Skills</td>
            </tr>
        </table>
	</body>
</html>
```

## OUTPUT
![Alt text](<Screenshot (25).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
