# Ex03 Time Table
## Date:18-03-2025

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
        <img src="logo.png" height="100" width="540">
    </center>
    <br>
    <table align="center" width="540" cellspacing="4" cellpadding="5" border="5" bgcolor="pink">
    <caption><b>TIME TABLE - Thejashree.S (212224240175)</b></caption>
    <tr align="center">
        <th bgcolor="red">Day/Time</th>
        <th bgcolor="cyan">Monday</th>
        <th bgcolor="cyan">Tuesday</th>
        <th bgcolor="cyan">Wednesday</th>
        <th bgcolor="cyan">Thursday</th>
        <th bgcolor="cyan">Friday</th>
    </tr>
    <tr align="center">
        <th bgcolor="cyan">8-10</th>
        <td>Web development</td>
        <td>Task completion</td>
        <td>Assessment hour</td>
        <td>Task presentation</td>
        <td>Task completion</td>
    </tr>
    <tr align="center">
        <th bgcolor="cyan">10-12</th>
        <td>Task assignment</td>
        <td>Web development</td>
        <td>Task presentation</td>
        <td>Module completion</td>
        <td>Web development</td>
    </tr>
    <tr align="center">
        <th bgcolor="cyan">12-1</th>
        <td colspan="6" style="text-align:center;">Lunch Hour</td>
    </tr>
    <tr align="center">
        <th bgcolor="cyan">1-3</th>
        <td>Fundamentals of AI</td>
        <td>Module completion</td>
        <td>Mentor meet</td>
        <td>Fundamentals of AI</td>
        <td>Task completion</td>
    </tr>
    <br>
    </table>

    <br>

    <table align="center" cellspacing="2" cellpadding="7" border="2" style="margin-top:20;">
    <tr align="center">
        <th>S.No.</th>
        <th>Subject Code</th>
        <th>Subject Name</th>
    </tr>

    <tr>
        <td align="center">1.</td>
        <td align="center">19AI414</td>
        <td align="center">Fundamentals of web development</td>
    </tr>

    <tr>
        <td align="center">2.</td>
        <td align="center">19CS405</td>
        <td align="center">Operating System</td>
    </tr>

    <tr>
        <td align="center">3.</td>
        <td align="center">19AI403</td>
        <td align="center">Introduction to Data science</td>
    </tr>

    <tr>
        <td align="center">4.</td>
        <td align="center">19AI410</td>
        <td align="center">Introduction to Machine learning</td>
    </tr>
    <tr>
        <td align="center">5.</td>
        <td align="center">19AI305</td>
        <td align="center">Advanced C programming</td>
    </tr>
    <tr>
        <td align="center">6.</td>
        <td align="center">19EE404</td>
        <td align="center">Digital Electronics</td>
    </tr>

    <tr>
        <td align="center">7.</td>
        <td align="center">19CY205</td>
        <td align="center">Principles of Chemistry in Engineering</td>
    </tr>
    <tr>
        <td align="center">8.</td>
        <td align="center">SH7801</td>
        <td align="center">Human values and Professional ethics</td>
    </tr>

    </table>
</body>
</html>

```

## OUTPUT
![alt text](<Screenshot (21).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
