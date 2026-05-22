# Ex02 Time Table
## Date:21/05/2026

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
    <title>Slot Timetable</title>
    </head>
    <body>
        <center>
             <img src="c:\Users\acer\OneDrive\Pictures\Pictures\Screenshots\Screenshot 2026-05-21 173203.png" height="100" ; width="540">
        </center>
        <br>
        <table align="center" width="540" bgcolor="LIGHTGRAY" cellspacing="0" cellpadding="4" border >
            <caption><b>SLOT TIME TABLE - MADESHWARAN D (212225040212)</b></caption>
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
                <th bgcolor="ORANGE">8-10</th>
                <td>PYTHON PROGRAMMING</td>
                <td>FREE SLOT</td>
                <td>PYTHON PROGRAMMING</td>
                <td>FREE SLOT</td>
                <td>FREE SLOT</td>
                <td>FREE SLOT</td>
            </tr>
            <tr align="center">
                <th bgcolor="ORANGE">10-12</th>
                <td>FREE SLOT</td>
                <td>FUNDAMENTALS OF WEB APPLICATION</td>
                <td>FUNDAMENTALS OF WEB APPLICATION</td>
                <td>PYTHON PROGRAMMING</td>
                <td>FUNDAMENTALS OF WEB APPLICATION</td>
                <td>FREE SLOT</td>
            </tr>
            <tr align="center">
                <th bgcolor="ORANGE">12-1</th>
                <th colspan="5" align="center"><b>LUNCH</b></th>
            </tr>
            <tr align="center">
                <th bgcolor="ORANGE">1-3</th>
                <td>FREE SLOTT</td>
                <td>FUNDAMENTALS OF WEB APPLICATION</td>
                <td>MENTOR MEET</td>
                <td>PYTHON PROGRAMMING</td>
                <td>FREE SLOT</td>
                <td>FREE SLOT</td>
            </tr>
            <tr align="center">
                <th bgcolor="ORANGE">3-5</th>
                <td>FREE SLOT</td>
                <td>FREE SLOT</td>
                <td>FREE SLOT</td>
                <td>FREE SLOT</td>
                <td>FREE SLOT</td>
                <td>FREE SLOT</td>
            </tr>
        </table>
        <br>
        <table align="center" cellspacing="2" cellpadding="4" bgcolor="gold" border="2">
            <tr align="center">
                <th>S.no</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
            
            <tr>
                <td align="center">2.</td>
                <td align="center">19AI304</td>
                <td>PYTHON PROGRAMMING</td>
            </tr>
            <tr>
                <td align="center">3.</td>
                <td align="center">19AI414</td>
                <td>FUNDAMENTALS OF WEB APPLICATION</td>
            </tr>

            <tr>
                <td align="center">7.</td>
                <td align="center">ECA-M</td>
                <td>MENTOR</td>
            </tr>
        </table>
    </body>
</html>
```

## OUTPUT
<img width="1917" height="1077" alt="Screenshot 2026-05-21 173806" src="https://github.com/user-attachments/assets/5344fd63-e6cb-4bda-8ff0-0d76d025bddd" />


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
