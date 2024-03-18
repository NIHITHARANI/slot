# Ex03 Time Table
## Date:13-03-2024

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
        <title>SLOT TIMETABLE-SUSITHRA</title>
</head>
<body bgcolor="yellow">
    <center>
    <img src="/static/logo.png" height="100" width="540">
    </center>
<table border="3" cellspacing="4" cellpadding="6" align="center" bgcolor="lightgrey">
<caption>SLOT TIMETABLE-SUSITHRA(23011936)</caption>
            <tr>
               <th bgcolor="pink">Day/Time</th>
               <th bgcolor="pink">Monday</th>
               <th bgcolor="pink">Tuesday</th>
               <th bgcolor="pink">Wednesday</th>
               <th bgcolor="pink">Thursday</th>
               <th bgcolor="pink">Friday</th>
               <th bgcolor="pink">Saturday</th>
          </tr>
           <tr>
               <td>8:00-10:00</td>
               <td>Digital Electronics</td>
               <td>Free Slot</td>
               <td>Fundamentals of web applications</td>
               <td>Japanese</td>
               <td>Chemistry</td>
               <td>Maths</td>
          </tr>
          <tr>
               <td>10:00-12:00</td>
               <td>Free Slot</td>
               <td>fundamental of web applications</td>
               <td>Free Slot</td>
               <td>Maths</td>
               <td>Python</td>
               <td>OperatingSystem</td>
          </tr>
          <tr>
               <td>12:00-1:00</td>
               <td colspan="6" align="center" bgcolor="skyblue">Lunch</td>
          </tr>
          <tr>
               <td>1:00-3:00</td>
               <td>Fundamentals of web applications</td>
               <td>Chemistry</td>
               <td>Creative Skill</td>
               <td>Free Slot</td>
               <td>Digital Electronics</td>
               <td>Japanese</td>

          </tr>
          <tr>
               <td>3:00-5:00</td>
               <td>OperatingSystem</td>
               <td>Free Slot</td>
               <td>Japanese</td>
               <td>Python</td>
               <td>Free Slot</td>
               <td>Free Slot</td>
         
          </tr>
<table border="3" cellspacing="4" cellpadding="6" align="center" bgcolor="lightgrey">
<caption>SUBJECT DETAILS</caption>
          <tr>
               <th bgcolor="pink">S.no</th>
               <th bgcolor="pink">Subject Code</th>
               <th bgcolor="pink">Subject Name</th>
               
          </tr>
          <tr>
               <td>01</td>
               <td>19EE404</td>
               <td>Digital Electronics</td>
           </tr>
            <tr>
               <td>02</td>
               <td>19AI414</td>
               <td>Python</td>
           </tr> <tr>
               <td>03</td>
               <td>19AI414</td>
               <td>Fundamentals of web</td>
           </tr>
            <tr>
               <td>04</td>
               <td>19CS405</td>
               <td>Operating System</td>
           </tr>
             <tr>
               <td>05</td>
               <td>19CY205</td>
               <td>Chemistry</td>
           </tr>
            <tr>
               <td>06</td>
               <td>19EN404</td>
               <td>Japanese</td>
           </tr>
            <tr>
               <td>07</td>
               <td>19EY615C</td>
               <td>SoftSkill</td>
           </tr>
            <tr>
               <td>08</td>
               <td>19MA222</td>
               <td>Maths</td>
           </tr>
          
</body>
</html>
```
## OUTPUT
[text](README.md)
## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
