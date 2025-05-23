# Ex03 Time Table
## Date:17.04.2025

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
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8">
        <title>Slot TimeTable</title>
        <style>
            body{
                font-family: Arial, Helvetica, sans-serif;
                text-align: center;
                margin: 40px;
                background:linear-gradient(to right, #e20582);
            }
            .logo{
                width: 700px;
                margin-bottom: 20px;
                height : 100px;
            }
            table{
                width: 100%;
                border-radius: 20px;
                border-collapse: separate;
                border-spacing: 3;
                border: none;
            }
            th, td {
                
            padding: 10px;
            text-align: center;
            background-color: rgb(250, 215, 236);
            border: 1px solid #060501;
            }
            th {
            background-color: #f7f4f4;
            color: rgb(15, 0, 0);
            }
            #table_head{
                background-color: #00d3f4;
                color: white;
                font-size: 20px;
            }
            .Days{
                background-color: #f7f76c;
                color: black;
                font-weight: bold;
            }
        </style>
    </head>

    <body>
        <img src="/static/logo.png" alt="logo" class="logo">
        <h1>EVEN SEMESTER TIME TABLE</h1>
        <table>
            <tr>
                <th colspan="5" id="table_head">SLOT TIMETABLE - A.NABITHRA (212224230172)</th>
            </tr>
            <tr class="Days">
                <th></th>
                <th>8:00-10:00 </th>
                <th>10:00-12:00 </th>
                <th>1:00-3:00 </th>
                <th>3:00-5:00</th>
            </tr>
            <tr>
                <td class="Days">MONDAY</td>
                <td>FREE SLOT</td>
                <td>DIGITAL ELECTRONICS</td>
                <td>PHYSICS FOR QUANTUM COMPUTING</td>
                <td>FREE SLOT</td>
            </tr>
            <tr>
                <td class="Days">TUESDAY</td>
                <td>FREE SLOT</td>
                <td>FREE SLOT</td>
                <td>PROBABILITY AND QUEUING MODEL</td>
                <td>FREE SLOT</td>
            </tr>
            <tr>
                <td class="Days">WEDNESDAY</td>
                <td>FREE SLOT</td>
                <td>ENGINEERING DESIGN AND MODELLING</td>
                <td>MENTOR MEET</td>
                <td>PHYSICS FOR QUANTUM COMPUTING</td>
            </tr>
            <tr>
                <td class="Days">THURSDAY</td>
                <td>FUNDAMENTALS OF C PROGRAMMING</td>
                <td>DIGITAL ELECTRONICS</td>
                <td>COMPUTER NETWORKS</td>
                <td>FUNDAMENTALS OF WEB APPLICATION</td>
            </tr>
            <tr>
                <td class="Days">FRIDAY</td>
                <td>FUNDAMENTALS OF C PROGRAMMING</td>
                <td>FUNDAMENTALS OF WEB APPLICATION</td>
                <td>PROBABILITY AND QUEUING MODEL</td>
                <td>ENVIRONMENTAL SCIENCE AND SUSTAINABILITY</td>
            </tr>
            <tr>
                <td class="Days" >SATURDAY</td>
                <td>FREE SLOT</td>
                <td>COMPUTER NETWORKS</td>
                <td>ENGINEERING DESIGN AND MODELLING</td>
                <td>FREE SLOT</td>
            </tr>
        </table>

    </body>

</html>
```

## OUTPUT
![alt text](<Screenshot 2025-04-17 135145.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
