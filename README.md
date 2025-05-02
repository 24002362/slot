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
    <!DOCTYPE html> 
    <html>
    <head>
        <title>Slot Timetable (2024-25)</title>
        <style>
            body {
                background-color: #FFF8DC; 
                font-family: Arial, sans-serif;
                color: #333;
            }
            table {
                border-collapse: collapse;
                margin: auto;
                width: 80%;
            }
            th, td {
                border: 2px solid #8B4513; 
                padding: 10px;
                text-align: center;
            }
            th {
                background-color: #DEB887; 
                color: white;
            }
            caption {
                font-size: 1.5em;
                margin: 10px;
                font-weight: bold;
            }
            h1 {
                text-align: center;
                color: #8B0000;
            }
            hr {
                border: 1px solid #8B0000;
            }
            .logo {
                display: block;
                margin-left: auto;
                margin-right: auto;
                width: 80%; 
                height: auto;
            }
        </style>
    </head>
    <body>
        <img src="/static/logo.png" height="100" width="540">
    
        <h1>Odd-Junior Timetable (2024-25)</h1>
        <p align="center">Name: <b>Hari Priya M</b> &nbsp;&nbsp; Register No: <b>212224240047</b></p>
        <hr>
    
        <table>
            <caption>Class Timetable</caption>
            <tr>
                <th>Day/Time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>Saturday</th>
            </tr>
            <tr>
                <td>8-10</td>
                <td>Free</td>
                <td>Communicative English</td>
                <td>Free</td>
                <td>EDM</td>
                <td>Communicative English</td>
                <td>EDM</td>
            </tr>
            <tr>
                <td>10-12</td>
                <td>Digital Electronics</td>
                <td>Free</td>
                <td>Career Development Skills</td>
                <td>Python and Linear Algebra</td>
                <td>Free</td>
                <td>Fundamentals of C Programming</td>
            </tr>
            <tr>
                <td>12-1</td>
                <td colspan="6">Lunch hour</td>
            </tr>
            <tr>
                <td>1-3</td>
                <td>Fundamentals of C Programming</td>
                <td>Python and Linear Algebra</td>
                <td>Mentor Hour</td>
                <td>Digital Electronics</td>
                <td>Python and Linear Algebra</td>
                <td>Python and Linear Algebra</td>
            </tr>
        </table>
    
        <br><br>
    
        <table>
            <caption>Courses Taken</caption>
            <tr>
                <th>S.No</th>
                <th>Course Code</th>
                <th>Course Name</th>
            </tr>
            <tr><td>1</td><td>19AI304</td><td>Fundamentals of C Programming</td></tr>
            <tr><td>2</td><td>19EN101</td><td>Communicative English</td></tr>
            <tr><td>3</td><td>19EE404</td><td>Digital Electronics</td></tr>
            <tr><td>4</td><td>19EY708</td><td>Career Development Skills</td></tr>
            <tr><td>5</td><td>19AI301C</td><td>Python & Linear Algebra</td></tr>
            <tr><td>6</td><td>19AI302</td><td>Engineering Design and Modelling (EDM)</td></tr>
        </table>
    </body>
    </html>


## OUTPUT
![Screenshot 2025-05-02 164505](https://github.com/user-attachments/assets/1d60fce2-205f-4822-a9f9-f12527bc9b80)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
