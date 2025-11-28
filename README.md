# Ex02 Time Table
## Date:28/11/2025

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create an App inside the Django project.

### STEP 2
Create a static folder uder the created App and insert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html with the relevant attributes.

### STEP 4
Add rows using ```<tr>``` tag.

### STEP 5
Add your course schedule using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```
<html>
 
    <head>
        <title>time table </title>
    </head>
    
    <body>
        <center>
            <img src="logo.png" >
        </center>
        <table width="900" height="300" border="3" cellspacing="3"><caption><h1 align="center"><B>SLOT_TIME_TABLE</B> </h1></caption>
        <tr bgcolor="green">
            <td align="center"><b>Day </b></td>
            <td align="center"><b>8 to 10 </b></td>
            <td align="center"><b>10 to 12</b></td>
            <td align="center"><b>12 to 1</b></td>
            <td align="center"><b>1 to 3</b></td>
            <td align="center"><b>3 to 4:30</b></td>
        </tr>
        <tr bgcolor="PINK">
            <td align="center"><b>MONDAY</b></td>
            <td align="center"><b>C </b></td>
            <td colspan="1"  align="center"><b>FREE SLOT</b></td>
            <td align="center"><b>LUNCH</b></td>
            <td align="center"><b>WED</b></td>
            <td align="center"><b>ENGLISH</b></td>

        </tr>
        <tr bgcolor="YELLOW">
            <td align="center"><b>TUESDAY</b></td>
            <td colspan="2" align="center"><b>FREE SLOT</b></td>
            <td align="center"><b>LUNCH</b></td>
            <td align="center"v><b>WEB</b></td>
            <td align="center"><b>FREE SLOT</b></td>
        </tr>
        <tr bgcolor="BLUE">
            <td align="center"><b>WEDNESDAY</b></td>
            <td align="center" align="center"><b>C </b></td>
            <td align="center"><b>FREE SLOT</b></td>
            <td align="center"><b>LUNCH</b></td>
            <td align="center"><b>Mentor meet</b></td>
            <td align="center"><b>ENGLISH</b></td>
        </tr>
        <tr bgcolor="WHITE">
            <td align="center"><b>THURSDAY</b></td>
            <td align="center"><b>fREE SLOT</b></td>
            <td align="center"><b>ENGLISH</b></td>
            <td align="center"><b>LUNCH</b></td>
            <td align="center"><b>C</b></td>
            <td align="center"><b>FREE SLOT </b></td>
        </tr>
        <tr bgcolor="SANDAL">
            <td align="center"><b>FRIDAY</b></td>
            <td colspan="2" align="center"><b>WEB</b></td>
            <td align="center"><b>LUNCH</b></td>
            <td align="center"><b>C</b></td>
            <td align="center"><b>FREE SLOT</b></td>
        </tr>
        <tr bgcolor="RED">
            <td align="center"><b>SATURDAY</b></td>
            <td align="center"><b>FREE SLOT</b></td>
            <td align="center"><b>WEB</b></td>
            <td align="center"><b>LUNCH</b></td>
            <td align="center"><b>C </b></td>
            <td align="center"><b>ENGLISH</b></td>

        </tr>
        </table>
        <table  width="500"  height="300" border="5" cellspacing="5" ><caption><h1>SUBJECTS</h1></caption>
            <tr>
                <td>S>NO</td>
                <td>SUBJECT CODE</td>
            </tr>
            <tr>
            <td>1.</td>
            <td><b>19AI304-- FUNDAMENTALS OF C PROGRAMMING</b></td>
            </tr>
            <tr>
                <td>2.</td>
                <td><b>19EN101-- COMMUNICATION ENGLSIH</b></td>
            </tr>
            <tr>
                <td>3.</td>
                <td><b>19AI414-- FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</b></td>
            </tr>
            <tr>
                <td>4.
                </td>
                <td><b>ECA-M -- MENTOR MEET</b></td>
            </tr>
        
        
        </table>
        
    </body>

</html>
```

## OUTPUT
![alt text](<niran/tysonapp/static/Screenshot 2025-11-28 091425.png>)
## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
