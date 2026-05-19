# Ex02 Time Table
## Date:

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
<!DOCTYPE html>
<html>
<head>
    <title>Slot Timetable</title>
</head>
<body>
<center>
    <img src="/static/images/Screenshot 2026-05-19 162216.png" height="100" width="540">
</center>
<h2 align="center">Slot Timetable</h2>

<table border="1" align="center" cellpadding="10">
    <tr>
        <th>S.No</th>
        <th>Subject Code</th>
        <th>Subject Name</th>
    </tr>

    <tr>
        <td align="center">1</td>
        <td align="center">19AI414</td>
        <td>Fundamentals of Web Application Development (FWAD)</td>
    </tr>

    <tr>
        <td align="center">2</td>
        <td align="center">19AI304</td>
        <td>Fundamentals of C Programming (C Program)</td>
    </tr>

    <tr>
        <td align="center">3</td>
        <td align="center">19AI414</td>
        <td>Fundamentals of Web Application Development (FWAD)</td>
    </tr>

    <tr>
        <td align="center">4</td>
        <td align="center">19CY205</td>
        <td>Principles of Chemistry in Engineering (CHE)</td>
    </tr>

    <tr>
        <td align="center">5</td>
        <td align="center">19MA211</td>
        <td>Statistics and Numerical Methods (MAT)</td>
    </tr>

    <tr>
        <td align="center">6</td>
        <td align="center">19EY101</td>
        <td>Soft Skills (SS)</td>
    </tr>
</table>

</body>
</html>
```

## OUTPUT
<img width="1915" height="1017" alt="Screenshot 2026-05-19 171842" src="https://github.com/user-attachments/assets/67a46b1b-e110-40b3-bc0a-ed968f0c6842" />
DEVELOPED BY: MIRDULA D   REGISTRATION NO. 212225040234

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
