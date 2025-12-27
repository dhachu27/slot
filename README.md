# Ex02 Time Table
## Date:17.12.25

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
        <title>tables</title>
    </head>
    <body>
        <img src="logo.png" width="600" height="150">
        <br>
        <br>
        <table border="1" cellspacing="5" cellpadding="5">
            <caption>SLOT TIME TABLE- rajaprabu</caption>
            <tr bgcolor="periwinkle">
                <th>Day/Time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>Saturday</th>
            </tr>
            <tr bgcolor="cyan">
                <th>8-10</th>
                <td>free slot</td>
                <td>python</td>
                <td>FWAD</td>
                <td>free slot</td>
                <td>python</td>
                <td>FWAD</td>
            </tr> 
            <tr bgcolor="cyan">
                <th>10-12</th>
                <td colspan="3" align="center">FWAD</td>
                <td colspan="3" align="center">free slot</td>
                
            </tr>
            <tr bgcolor="cyan">
                <th>12-1</th>
                <td colspan="6" align="center">LUNCH</td>
               
            </tr>
            <tr bgcolor="cyan">
                <th>1-3</th>
                <td>free slot</td>
                <td>CE</td>
                <td>Mentor meet</td>
                <td>python</td>
                <td>CE</td>
                <td>free slot</td>
            </tr>
            <tr bgcolor="cyan">
                <th>3-5</th>
                <td colspan="2">python</td>
                <td colspan="2">CE</td>
                <td colspan="2">free slot</td>
            </tr>

        </table>
        <br>
        <br>
        
        <table border="1" cellspacing="4" cellpadding="3">
            <tr>
                <th>S.NO</th>
                <th>SUBJECT CODE</th>
                <th>SUBJECT NAME</th>
            </tr>
            <tr>
                <td>1</td>
                <td>19AI414</td>
                <td>Fundamental Of Web Application Development(FWAD)</td>
            </tr>
            <tr>
                <td>2</td>
                <td>19AI301</td>
                <td>Python Programming(Python)</td>
            </tr>
            <tr>
                <td>3</td>
                <td>19EN101</td>
                <td>Communicative English(CM)</td>
            </tr>
            <tr>
                <td>4</td>
                <td>ECA-M</td>
                <td>Mentor meet</td>            
            </tr>
        </table>
    </body>
</html>
```

## OUTPUT
<img width="1138" height="538" alt="image" src="https://github.com/user-attachments/assets/073ab377-91d6-45a2-b424-587b2e06697d" />


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
