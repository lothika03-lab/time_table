# Ex03 Time Table
# Date: 21.11.2025
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using `<table>` tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```
<html>
<head>
    <title>Time Table</title>
    <style>
        table{
            color: rgb(102, 49, 49);
            border: 3px solid black;
            border-collapse: collapse;
            text-align: center;
            padding: 5px;
            font-style: italic;
            margin-left: auto;
            margin-right: auto;
            font-size: 18px;
        }
        th{
            background-color: blanchedalmond;
            color: rgb(102, 49, 49);
            border: 3px solid black;
            border-collapse: collapse;
            padding: 5px;
        }
        td{
            background-color: rgb(255, 246, 233);
            color: rgb(102, 49, 49);
            border: 3px solid black;
            border-collapse: collapse;
            padding: 5px;
        }
        span {
            writing-mode: vertical-lr;
            text-orientation: upright;
            letter-spacing: 10px;
        }
        body{
            background:linear-gradient(white,white,blanchedalmond, rgb(254, 210, 218))
        }
        .pi{
            background-color: rgb(255, 205, 214);
            color: rgb(102, 49, 49);
            border: 3px solid black;
            border-collapse: collapse;
            padding: 5px;
        }
        .tp
        {
            background-color: rgb(255, 223, 229);
            color: rgb(102, 49, 49);
            border: 3px solid black;
            border-collapse: collapse;
            padding: 5px;
        }
    </style>
</head>
<body>
    <center>
        <img src="logo.png" height="180" width="680">
    </center>
    <table>
        <caption><h2>Slot Time Table - Lothika M (25006771)</h2></caption>
        <caption>___________________________________________________________________________________________</caption>
            <th class="">Day/time</th>
            <th>8:00-10:00</th>
            <th>10:00-12:00</th>
            <th>12:00-1:00</th>
            <th>1:00-3:00</th>
            <th>3:00-5:00</th>
        </tr>
        <tr>
            <th>Monday</th>
            <td>C programming</td>
            <td>FREE SLOT</td>
            <th rowspan="6"><span>LUNCH</span></th>
            <td>FREE SLOT</td>
            <td>Communicative English</td>
        </tr>
        <tr>
            <th>Tuesday</th>
            <td colspan="2">FREE SLOT</td>
            <td>FWAD</td>
            <td>FREE SLOT</td>
        </tr>
        <tr>
            <th>Wednesday</th>
            <td>C programming</td>
            <td>FWAD</td>
            <td>Mentor Meet</td>
            <td>Communicative English</td>
        </tr>
        <tr>
            <th>Thursday</th>
            <td rowspan="2">FREE SLOT</td>
            <td>Communicative English</td>
            <td rowspan="3">C programming</td>
            <td rowspan="2">FREE SLOT</td>
        </tr>
        <tr>
            <th>Friday</th>
            <td>FWAD</td>
        </tr>
        <tr>
            <th>Saturday</th>
            <td colspan="2">FWAD</td>
            <td>Communicative English</td>
        </tr>
    </table>
    <table>
        <caption>_________________________________________________________________________</caption>
        <tr>
            <th class="pi">Si No</th>
            <th class="pi">subject code</th>
            <th class="pi">subject</th>
            <th class="pi">faculty</th>
        </tr>
        <tr>
            <th class="pi">1</th>
            <td class="tp">19AI304</td>
            <td class="tp">Fundamentals Of C Programming</td>
            <td class="tp">Trainer 1</td>
        </tr>
        <tr>
            <th class="pi">2</th>
            <td class="tp">19AI414</td>
            <td class="tp">Fundamentals Of Web Application Development</td>
            <td class="tp">Berlin Magthalin</td>
        </tr>
        <tr>
            <th class="pi">3</th>
            <td class="tp">19EN101</td>
            <td class="tp">Communicative English</td>
            <td class="tp">David Raja</td>
        </tr>
        <tr>
            <th class="pi">4</th>
            <td class="tp">-</td>
            <td class="tp">Mentor Meet</td>
            <td class="tp">Suguna Devi</td>
        </tr>
    </table>
</body>
</html>
```

# OUTPUT
<img width="1920" height="1080" alt="Screenshot (51)" src="https://github.com/user-attachments/assets/63a30fb7-bb4b-4865-89fc-3fc4fab5a9b3" />

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
