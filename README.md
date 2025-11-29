# Ex02 Time Table
## Date:25-11-2025

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
```<html>
    <body>
        <img src="logo.png" height="100" width="600">
        <h3>SLOT TIME TABLE- RAKISHA(25008669)</h3>
        <table border = "5" cellpadding ="5" cellspacing="5">
            <tr bgcolor="pink">
                <th>Day/Time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>Saturday</th>
            </tr>
            <tr bgcolor="blue">
                <th bgcolor="pink">8-10 </th>
                <td colspan="2" align="center">ENG</td>
                <td>FWAD</td>
                <td>FREE</td>
                <td>C PROGRAM</td>
                <td>FWAD</td>
            </tr>
            <tr bgcolor="blue">
                <th bgcolor="pink">10-12 </th>
                <td colspan="3" align="center">FWAD</td>
                <td colspan="2"  align="center">FREE</td>
                <td>ENG</td>
               
            </tr>
            <tr bgcolor="blue">
                <th bgcolor="pink">12-1</th>
                <th colspan="7">LUNCH</th>
            </tr>
            <tr bgcolor="blue">
                <th bgcolor="pink">1-3</th>
                <td colspan="2" align="center">FREE</td>
                <td >MENTOR MEET</td>
                <td>ENG</td>
                <td colspan="2" align="center">FREE</td>
            </tr>
            <tr bgcolor="blue">
                <th bgcolor="pink">3-5</th>
                <td colspan="4" align="center">C PROGRAM</td>
                <td colspan="2" align="center">FREE</td>
                
            </tr>
        </table>
        <br>
        <br>
        <table border="2" cellpadding="5">
            <tr>
                <th>S.No.</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
            <tr>
                <td>1.</td>
                <td>19A1414</td>
                <td>Fundamentals of Web Application Development(FWAD)</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>19A1301</td>
                <td>C PROGRAM(C PROGRAMMING LANGUAGE) </td>
            </tr>
            <tr>
                <td>3.</td>
                <td>19EN101</td>
                <td>Communicative English(ENG)</td>
            </tr>
        </table>
    </body>
</html>
```
## OUTPUT
![alt text](<Screenshot 2025-11-29 123037.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
