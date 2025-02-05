# Ex03 Time Table
## Date: 18-03-24

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
<html lang="en">
<head>
    <title>Timetable</title>
</head>
<body bgcolor="cyan">
    <img src="./logo.png" height="200" width="1080">
    <h4 align="center">My Time Table : GOWTHAM N 212223100008</h4>
    <table align="center" border="3" cellspacing="4" cellpadding bgcolor="beige" height="300" width="1000">
        <tr>
        <th>Day/Time</th>
        <th>8 - 10</th>
        <th>10 - 12</th>
        <th>1 - 3</th>
        <th>3 - 5</th>
        </tr>

        <tr>
            <th>Mon</th>
            <th>DE</th>
            <th>-</th>
            <th>Web</th>
            <th>C</th>
        </tr>

        <tr>
            <th>Tue</th>
            <th>-</th>
            <th>Web</th>
            <th>-</th>
            <th>EDM</th>
        </tr>

        <tr>
            <th>Wed</th>
            <th>C</th>
            <th>CN</th>
            <th>Creative</th>
            <th>-</th>
        </tr>

        <tr>
            <th>Thu</th>
            <th>EDM</th>
            <th>Probability</th>
            <th>-</th>
            <th>DE</th>
        </tr>

        <tr>
            <th>Fri</th>
            <th>-</th>
            <th>C</th>
            <th>Soft</th>
            <th>-</th>
        </tr>

        <tr>
            <th>Sat</th>
            <th>Probability</th>
            <th>CN</th>
            <th>-</th>
            <th>-</th>
        </tr>
    </table>
    <br>

    <table align="center" border="2" cellspacing="2" cellpadding="4" bgcolor="beige" height="300" width="1000">
        <tr>
            <th>S.No</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr>
            <td align="center">1.</td>
            <td align="center">19MA222</td>
            <td align="center">Probability and Queueing Models</td>
        </tr>
        <tr>
            <td align="center">2.</td>
            <td align="center">19AI304</td>
            <td align="center">Fundamental of C Programming</td>
        </tr>
        <tr>
            <td align="center">3.</td>
            <td align="center">19AI414</td>
            <td align="center">Fundamental of Web Application</td>
        </tr>
        <tr>
            <td align="center">4.</td>
            <td align="center">19CS406</td>
            <td align="center">Computer Network</td>
        </tr>
        <tr>
            <td align="center">5.</td>
            <td align="center">19EE404</td>
            <td align="center">Digital Electronic</td>
        </tr>
        <tr>
            <td align="center">6.</td>
            <td align="center">19EY7017</td>
            <td align="center">Soft Skill</td>
        </tr>
        <tr>
            <td align="center">7.</td>
            <td align="center">19EY702</td>
            <td align="center">Creative Skills for Communication</td>
        </tr>
    </table>
</body>
</html>
```
## OUTPUT
![alt text](<Screenshot 2024-03-18 140745.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
