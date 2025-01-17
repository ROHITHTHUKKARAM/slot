# Ex03 Time Table
## Date:18-03-2024

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
		<title>Rohith T Time Table</title>
	</head>
	<body align="center">
        <img src="/static/logo.png" height="200" width="800" >
	<table border="2" cellspacing="5" cellpadding="5" width="800" height="50" align="center">
        <caption> SLOT TIME TABLE-Rohith T(212223040173)</caption>
		<tr bgcolor="Light blue" align="center">
			<th>Day/Time</th>
			<th>Monday</th>
			<th>Tuesday</th>
                        <th>Wednesday</th>
			<th>Thursday</th>
			<th>Friday</th>
		</tr>
		<tr bgcolor="gold" align="center">
			<th bgcolor="Light blue">8-10</th>
			<td>DE</td>
			<td>FREE SLOT</td>
			<td>Chemistry</td>
			<td>EDM</td>
			<td>WEB</td>
		</tr>
		<tr bgcolor="gold" align="center">
			<th bgcolor="Light Blue">10-12</th>
			<td>FREE SLOT</td>
			<td>C Prog</td>
			<td>Probability</td>
			<td>C Prog</td>
			<td>FREE SLOT</td>
		</tr>
		<tr bgcolor="gold" align="center">
			<th bgcolor="LIght blue">12-1</th>
			<td colspan="5" align="center">LUNCH</td>
		</tr>
		<tr bgcolor="gold" align="center">
			<th bgcolor="Light Blue">1-3</th>
			<td>Creative Skill</td>
			<td>WEB</td>
			<td>FREE SLOT</td>
			<td>WEB</td>
			<td>Computer Network</td>
		</tr>
		<tr bgcolor="gold" align="center">
			<th bgcolor="Light Blue">3-5</th>
                        <td>FREE SLOT</td>
			<td>EDM</td>
			<td>Computer Network</td>
			<td>DE</td>
			<td>FREE SLOT</td>
			
	</table>
    <br>
    <table border="2" cellspacing="5" cellpadding="5" width="800" height="50" align="center">
        <tr bgcolor="Light Blue" align="center">
            <th>S.No</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr bgcolor="gold" align="center">
            <th bgcolor="light blue">1.</th>
            <td>19AI304</td>
            <td>Fundamentals of C Programming(C prog)</td>
        </tr align="center">
        <tr bgcolor="gold" align="center">
            <th bgcolor="light blue">2.</th>
            <td>19AI414</td>
            <td>Fundamentals of Web application Development(FWAD)</td>
        </tr>
        <tr bgcolor="gold" align="center">
            <th bgcolor="light blue">3.</th>
            <td>19CS406</td>
            <td>Computer Network</td>
        </tr>
        <tr bgcolor="gold" align="center">
            <th bgcolor="light blue">4.</th>
            <td>19EE404</td>
            <td>Digital Electronics(DE)</td>
        </tr>
        <tr bgcolor="gold" align="center">
            <th bgcolor="light blue">5.</th>
            <td>19EY702</td>
            <td>Creative skills for communications(CSFC)</td>
        </tr>
        <tr bgcolor="gold" align="center">
            <th bgcolor="light blue">6.</th>
            <td>19MA222</td>
            <td>Probability and Queueing Models</td>
        </tr>
        <tr bgcolor="gold" align="center">
            <th bgcolor="light blue">7.</th>
            <td>19CY205</td>
            <td>Chemistry</td>
        </tr>
    </table>
	</body>
</html>
```

## OUTPUT
![alt text](image.png)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
