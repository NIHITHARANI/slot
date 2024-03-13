# Ex03 Time Table
## Date:

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
'''
<html>
    <head align="center">
        <img src="logo.png" height="100" width="900">
    </head>
    <body align="center">
        <caption><b><br><br>SLOT TIME TABLE-B.NIHITHA RANI (212223040131)</b></caption>
        <table  border="3" cellspacing="4" cellpadding="6" align="center" bgcolor="mediumseagreen">
            <br>
            <tr bgcolor="yellow">
                <th>Day/Time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
            </tr>
            <tr>
                <th bgcolor="yellow">8-10</th>
                <td>FREE SLOT</td>
                <td>19EN101</td>
                <td>19AI414</td>
                <td>19CS405</td>
                <td>FREESLOT</td>
            </tr>
            <tr>
                <th bgcolor="yellow">10-12</th>
                <td>19EE305</td>
                <td>19AI414</td>
                <td>FREESLOT</td>
                <td>19MA222</td>
                <td>19EE404</td>
            </tr>
            <tr>
                <th bgcolor="yellow">12-1</th>
                <td colspan="5" align="center" bgcolor="yellow">LUNCH</td>
            </tr>
            <tr>
                <th bgcolor="yellow">1-3</th>
                <td>19AI414</td>
                <td>19EE404</td>
                <td>19MS156</td>
                <td>19EE305</td>
                <td>19MS156</td>
            </tr>
            <tr>
                <th bgcolor="yellow">3-5</th>
                <td>19AI305</td>
                <td>FREESLOT</td>
                <td>19AI305</td>
                <td>FREESLOT</td>
                <td>19CS405</td>
            </tr>
        </table>
        <table border="3" cellspacing="4" cellpadding="6" align="center">
            <caption align="center"><b><br>SUBJECTS</b></caption>
            <tr bgcolor="white">
                <th>S.No</th>
                <th>Subject Code</th>
                <th align="center">Subject Name</th>
            </tr>
            <tr>
                <td>1</td>
                <td>19EE305</td>
                <td>Bsic Electrical,Electronics and Measurement Engineeering</td>
            </tr>
            <tr>
                <td>2</td>
                <td>19AI414</td>
                <td>Fundamentals of Web Application Development</td>
            </tr>
            <tr>
                <td>3</td>
                <td>19AI305</td>
                <td>Advanced C Programming</td>
            </tr>
            <tr>
                <td>4</td>
                <td>19EN101</td>
                <td>Communicative English</td>
            </tr>
            <tr>
                <td>5</td>
                <td>19EE404</td>
                <td>Digital Electronics</td>
            </tr>
            <tr>
                <td>6</td>
                <td>19MS156</td>
                <td>Human Resource Management and Team Building</td>
            </tr>
            <tr>
                <td>7</td>
                <td>19CS405</td>
                <td>Operating System</td>
            </tr>
            <tr>
                <td>8</td>
                <td>19MA222</td>
                <td>Probability and Queueing Models</td>
            </tr>
        </table>
    </body>
</html>
'''

## OUTPUT
![alt text](<ex 3 vs.png>)
![alt text](<ex 3.png>)
## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
