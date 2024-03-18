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
<<<<<<< HEAD
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
=======
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
```
>>>>>>> 132b979009390c3e3220d2620564842f041b6a1f

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
![output](<ex 3 vs.png>)
![output](<ex 3 final.png>)
## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
