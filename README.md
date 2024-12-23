# Ex03 Time Table
# Date:27.09.2024
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using <table> tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Slot Timetable</title>
    <style>
       body {
            font-family: Verdana, Geneva, Tahoma, sans-serif
        }
        .container {
            text-align: center;
            margin: 20px;
        }
        h1, h2 {
            margin: 0;
            padding: 10px;
        }
        table {
            width: 90%;
            margin: 20px auto;
            border-collapse: collapse;
        }
        th, td {
            border: 3px solid #000;
            padding: 10px;
            text-align: center;
        }
        th {
            background-color: #ff8000;
        }
        td {
            background-color: #E0FFFF;
        }
           .vertical-text{
            writing-mode: vertical-lr;
            transform: rotate(180deg);
            font-weight: bold;
            text-align: center;
           }

    </style>
</head>
<body>
    <div class="container">
        <img src="/static/logo.png" alt="Saveetha Engineering College"
         width="900" height ="100">
        <h3>SLOT TIMETABLE - JISHA BOSSNE SJ (24900154)</h3>
        
        <table>
            <tr>
                <th>Day/Time</th>
                <th>8-10</th>
                <th>10-12</th>
                <th>12-1</th>
                <th>1-3</th>
            </tr>
            <tr>
                <th><i>Monday</i></th>
                <td><i>DE</i></td>
                <td><i>CDS</i></td>
                <td rowspan="5"
                class ="vertical-text">LUNCH</td>
                <td><i>FWAD</i></td>
            </tr>
            <tr>
                <th><i>Tuesday</i></th>
                <td rowspan="3"> FREE </td>
                <td><i>PHY</i></td>
                <td><i>MATH</i></td>
            </tr>
            <tr>
                <th><i>Wednesday</i></th>
                <td><i>CE</i></td>
                <td><i>Mentor Meeting</i></td>
            </tr>
            <tr>
                <th><i>Thursday</i></th>
                <td><i>MATH</i></td>
                 <td><i>DE</i></td>
            </tr>
            <tr>
                <th><i>Friday</i></th>
                <td><i>PHY</i></td>
                <td><i>FWAD</i></td>
                <td><i>Free</i></td>
            </tr>
        </table>

        <table>
            <tr>
                <th>S. No.</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
            <tr>
                <td><i>1</i></td>
                <td><i>19AI410</i></td>
                <td><i>Fundamentals of Web Application (FWAD)</i></td>
            </tr>
            <tr>
                <td><i>2</i></td>
                <td><i>SH3214</i></td>
                <td><i>Physics for Quantum Computing (PHY)</i></td>
            </tr>
            <tr>
                <td><i>3</i></td>
                <td><i>19EN101</i></td>
                <td><i>Communicative English(CE)</i></td>
            </tr>
            <tr>
                <td><i>4</i></td>
                <td><i>19EY708</i></td>
                <td><i>Career Development Skills(CDS)</i></td>
            </tr>
            <tr>
                <td><i>5</i></td>
                <td><i>19EE404</i></td>
                <td><i>Digital Electronics(DE)</i></td>
            </tr>
            <tr>
                <td><i>6</i></td>
                <td><i>19MA222</i></td>
                <td><i>Probability(MATH)</i></td>
            </tr>
        </table>
    </div>
</body>
</html>
```
# OUTPUT
![Screenshot (40)](https://github.com/user-attachments/assets/2e4b856f-c7bd-4565-bfa4-1918321b1188)


# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
