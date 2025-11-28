# Ex03 Time Table
# Date:28.11.25
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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TIME TABLE</title>
    <link rel="icon" href="logo.jpg">
        <style>
            table,th,td{
                background-color: rgb(224, 69, 241);
                color:black;
                border-collapse:collapse;
                font-size: medium;
                font-style: italic;
                text-align: center;
                margin-left: auto;
                margin-right: auto;
                border: 2px solid black;
            }
            th,td{
                padding: 10px;
            }
            img{
                height: 150px;
                width:650px;
                margin-left: auto;
                margin-right: auto;
                display:block;
                border-radius: 5px;
            
            }
            body{
            
                background:aqua;
            }
           
            th {
            background-color: #2e0437;
            color: #fda8f5;
            font-weight: bold;
        }

        td {
            background-color: #fda8f5;
        }
        .vertical-text{
            writing-mode: vertical-rl;
            text-orientation: upright;
            letter-spacing: 10px;
            font-weight: bold;
        }
        p{
            text-align: center;
            font-size: 30px;
        }
        </style>
</head>
<body>
    <img src="SEC.png">
        <caption><h3 style="text-align:center;color:rgba(61, 12, 12, 0.922); "><u>TIMETABLE-NITHYA JEYSHRI (25018780)</u></h3></caption>
        <table>
            <tr>
              <th>DAY/TIME</th>
              <th>8am to 10am</th>
              <th>10am to 12am</th>
              <th>12pm to 1pm</th>
              <th>1pm to 3pm</th>
              <th>3pm to 5pm</th>
            </tr>
            <tr>  
                <td>MONDAY</td>
                <td colspan="2">FREE SLOT</td>
                <td rowspan="6" class="vertical-text"><span>LUNCH</span></td>
                <td colspan="2">Python</td>
            </tr>
            <tr>
                <td>TUESDAY</td>
                <td rowspan="2">FREE SLOT</td>
                <td>English</td>
                <td>FWAD</td>
                <td rowspan="3">FREE SLOT</td>  
            </tr>
            <tr>
                <td>WEDNESDAY</td>
        
                <td>FWAD</td>
                <td>Mentor Meet</td>
            
            
            </tr>
            <tr>
                <td>THURSDAY</td>
                <td>Python</td>
                <td>English</td>
                <TD>English</TD>
                
            </tr>
            <tr>
                <td>FRIDAY</td>
                <td>FREE SLOT</td>
                <td>FWAD</td>
                <td>FREE SLOT</td>
                <td>Python</td>
            </tr>
            <tr>
                <td>SATURDAY</td>
                <td colspan="2">FWAD</td>       
                <td>Python</td>
                <td>English</td>
                 </tr>
            
        </table>
        <p>⏱📅</p>
        <DIV ID="ONE">
        <table style="margin-top: 10px;">
            <tr>
                <th>S.no</th>
                <th>Course Name</th>
                <th>Course Code</th>
            </tr>
            <tr>
                <td>1.</td>
                <td>Python programming</td>
                <td>19AI301</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>Communicative English</td>
                <td>19EN101</td>

            </tr>
            <tr>
                <td>3.</td>
                <td>Fundamentals of Web Application Development</td>
                <td>19AI414</td>
            </tr>
        </table>
        </DIV>
</body>
</html>
```
# OUTPUT
![nithyaoutput](https://github.com/user-attachments/assets/05a50adf-9708-475b-b408-2b725fa7b627)


# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
