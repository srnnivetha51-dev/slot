# Ex02 Time Table
## Date:
26-11-2025
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
        <title>
            Sample Page
        </title>
    </head>
    <body>
        <img src="logo.png" widht="1500" height="300">
        <table border="1" cellspacing="5" cellpadding="5">
            <caption>SLOT TIMETABLE-S.R.NIVEDHITHA(25000724)</caption>
            <tr bgcolor="cyan">
                <th>Day/Time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>Saturday</th>
            </tr>
            <tr bgcolor="violet ">
                <td bgcolor="cyan">8-10</td>
                <td>English</td>
                <td>English</td>
                <td>FWAD</td>
                <td>Free Slot</td>
                <td>Python</td>
                <td>fWAD</td>

            </tr>
            <tr bgcolor="violet ">
                <td bgcolor="cyan">10-12</td>
                <td>FWAD</td>
                <td>FWAD</td>
                <td>FWAD</td>
                <td>Free Slot</td>
                <td>Free Slot</td>
                <td>English</td>
            </tr>
            <tr bgcolor="violet ">
                <td bgcolor="cyan">12-1</td>
                <td colspan="7">Lunch</td>
            </tr>
            <tr bgcolor="violet ">
                <td bgcolor="cyan">1-3</td>
                <td>Python</td>
                <td>Free Slot</td>
                <td>Mentor Meet</td>
                <td>English</td>
                <td>Free Slot</td>
                <td>Python</td>
            </tr>
            <tr bgcolor="violet ">
                <td bgcolor="cyan">3-5</td>
                <td>Python</td>
                <td>Free Slot</td>
                <td>Free Slot</td>
                <td>Free Slot</td>
                <td>Python</td>
                <td>Free Slot</td>
            </tr>
        </table>
        <table border="1" cellspacing="5" cellpadding="5">
            <tr>
                <th>S.NO</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
            <tr>
                <td>1</td>
                <td>19AI414</td>
                <td>Fundamentals of Web Applicaton</td>
            </tr>
            <tr>
                <td>2</td>
                <td>19AI301</td>
                <td>Python Programming</td>
            </tr>
            <tr>
                <td>3</td>
                <td>19EN101</td>
                <td>Communicate Skills</td>
            </tr>
        </table>
    </body>
</html>
```

## OUTPUT
![alt text](<Screenshot 2025-11-29 124319-1.png>)
## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
