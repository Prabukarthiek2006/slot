# Ex03 Time Table
## Date: 15-11-2024

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
    <body>
        <img src="logo.png" width="1500px" height="150px">

<table border="2"  cellpadding="5">
    <caption> <b> TIME TABLE  </b>  </caption>
    <caption> <b> PRABU KARTHIEK B (24010663)</b></caption>
    <tr bgcolor="cyan">
        <th>DAY</th>
        <th>8am-10am</th>
        <th>10am-12pm</th>
        <th>12pm-1pm</th>
        <th>1pm-3pm</th>
        <th>3pm-5pm</th>
    </tr>
    <tr>
        <th>MONDAY</th>
        <td>Free Slot</td>
        <td>Maths</td>
        <th>Lunch</th>
        <td>C Programming</td>
        <td bgcolor="yellow">Free Slot</td>
    </tr>
    <tr>
        <th>TUESDAY</th>
        <td>Web Class</td>
        <td bgcolor="yellow">Free Slot</td>
        <th>Lunch</th>
        <td>Maths</td>
        <td>Digital Electronics</td>
    </tr>
    <tr>
        <th>WEDNESDAY</th>
        <td bgcolor="yellow">Free Slot</td>
        <td>Chemistry</td>
        <th>Lunch</th>
        <td>Mentor Meet</td>
        <td bgcolor="yellow">Free Slot</td>
    </tr>
    <tr>
        <th>THURSDAY</th>
        <td>Human Values</td>
        <td>Career Development Skills</td>
        <th>Lunch</th>
        <td>Digital Electronics</td>
        <td bgcolor="yellow">Free Slot</td>
    </tr>
    <tr>
        <th>FRIDAY</th>
        <td bgcolor="yellow">Free Slot</td>
        <td>Chemistry</td>
        <th>Lunch</th>
        <td>Web Class</td>
        <td bgcolor="yellow">Free Slot</td>
    </tr>
    <tr>
        <th>SATURDAY</th>
        <td bgcolor="yellow">Free Slot</td>
        <td>C Programming</td>
        <th>Lunch</th>
        <td>Web Class</td>
        <td bgcolor="yellow">Free Slpt</td>
    </tr>
</table>
<br>
<table border="2" cellpadding="5">
    <caption> <b>COURSE</b></caption>
    <tr bgcolor='cyan'>
        <th>S.no</th>
        <th>Course Code</th>
        <th>Course Name</th>
    </tr>
    <tr>
        <td>1</td>
        <td>19AI304</td>
        <td>FUNDAMENTAL of C PROGRAMMING</td>
    </tr>
    <tr>
        <td>2</td>
        <td>19AI414</td>
        <td>FUNDAMENTAL of WEB APPLICATION</td>
    </tr>
    <tr>
        <td>3</td>
        <td>19CY205</td>
        <td>PRINCIPLES of CHEMISTRY</td>
    </tr>
    <tr>
        <td>4</td>
        <td>19EE404</td>
        <td>DIGITAL ELECTRONICS</td>
    </tr>
    <tr>
        <td>5</td>
        <td>19EY708</td>
        <td>CAREER DEVELOPMENT SKILLS</td>
    </tr>
    <tr>
        <td>6</td>
        <td>19MA201</td>
        <td>CALCULUS AND MATRIX ALGEBRA</td>
    </tr>
    <tr>
        <td>7</td>
        <td>SH7801</td>
        <td>HUMAN VALUES</td>
    </tr>
    <tr>
        <td>8</td>
        <td>ECA-M SCOFT</td>
        <td>MENTOR MEET</td>
    </tr>
</table>

</body>
</html>

```


## OUTPUT
![alt text](<Screenshot 2024-11-15 144726.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
