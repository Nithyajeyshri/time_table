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
<html>
    <head>
        <title>TIMETABLE</title>
        <link rel="icon" href="ICON.jpeg">
        <style>
            table,th,td{
                background-color: rgb(248, 238, 250);
                color:black;
                  background: #ffffffcc;
                border-collapse:collapse;
                font-size: medium;
                font-style: italic;
                text-align: center;
                padding:10px ;
                margin-left: auto;
                margin-right: auto;
                border: 2px solid #3e0a46;
                backdrop-filter: blur(4px);
                box-shadow: 0 0 10px rgba(0,0,0,0.2);
                overflow: hidden;
            }
            img{
                height: 100px;
                width:600px;
                margin-left: auto;
                margin-right: auto;
                display:block;
                border-radius: 10px;
            
            }
            body{
            
                background: linear-gradient(rgb(212, 228, 233),rgb(243, 218, 240),rgb(250, 211, 240));
            }
           
            th {
            background-color: #ffe6fa;
            color: #0a0a0a;
            font-weight: bold;
        }

        td {
            background-color: #fdf7ff;
        }

           .day {
            font-weight: bold;
            background-color: #f8e4ff !important;
        }
        .vertical-text{
            writing-mode: vertical-rl;
            text-orientation: upright;
            letter-spacing: 10px;
            font-weight: bold;
            background-color: #f8d3f8;
           }
           
           

            
        </style>
    </head>
    <body>
        <img src="logo-1.png" alt="saveetha engineering college logo" style="border: 2px dotted bisque;">
        <caption><h1 style="text-align:center;color:rgb(15, 14, 15); "><u>TIMETABLE-NITHYA JEYSHRI(25018780)</u></h1></caption>
        <table>
            <tr>
              <th>DAY/TIME</th>
              <th>8am - 10am</th>
              <th>10am - 12am</th>
              <th rowspan="7" class="vertical-text"><span>LUNCH</span>
              </th>
              <th>1pm - 3pm</th>
              <th>3pm - 5pm</th>
            </tr>
            <tr>  
                <td class="day">MONDAY</td>
                <td colspan="2">FREE SLOT</td>
                <td colspan="2">Python</td>
            </tr>
            <tr>
                <td class="day">TUESDAY</td>
                <td rowspan="2">FREE SLOT</td>
                <td>English</td>
                <td>FWAD</td>
                <td rowspan="3">FREE SLOT</td>  
            </tr>
            <tr>
                <td class="day">WEDNESDAY</td>
        
                <td>FWAD</td>
                <td>Mentor Meet</td>
            
            
            </tr>
            <tr>
                <td class="day">THURSDAY</td>
                <td>Python</td>
                <td>English</td>
                <TD>English</TD>
                
            </tr>
            <tr>
                <td class="day">FRIDAY</td>
                <td>FREE SLOT</td>
                <td>FWAD</td>
                <td>FREE SLOT</td>
                <td>Python</td>
            </tr>
            <tr>
                <td class="day">SATURDAY</td>
                <td colspan="2">FWAD</td>       
                <td>Python</td>
                <td>English</td>
                 </tr>
            
        </table>
        <DIV ID="ONE">
        <table style="margin-top: 30px; ">
            <tr>
                <th>S.no</th>
                <th>Course Name</th>
                <th>Course Code</th>
            </tr>
            <tr>
                <td>1</td>
                <td>Python programming</td>
                <td>19AI301</td>
            </tr>
            <tr>
                <td>2</td>
                <td>Communicative English</td>
                <td>19EN101</td>

            </tr>
            <tr>
                <td>3</td>
                <td>Fundamentals of Web Application Development</td>
                <td>19AI414</td>
            </tr>
        </table>
        </DIV>
        
    </body>
</html>
<html>
    <head>
        <title>TIMETABLE</title>
        <link rel="icon" href="ICON.jpeg">
        <style>
            table,th,td{
                background-color: rgb(248, 238, 250);
                color:black;
                  background: #ffffffcc;
                border-collapse:collapse;
                font-size: medium;
                font-style: italic;
                text-align: center;
                padding:10px ;
                margin-left: auto;
                margin-right: auto;
                border: 2px solid #3e0a46;
                backdrop-filter: blur(4px);
                box-shadow: 0 0 10px rgba(0,0,0,0.2);
                overflow: hidden;
            }
            img{
                height: 100px;
                width:600px;
                margin-left: auto;
                margin-right: auto;
                display:block;
                border-radius: 10px;
            
            }
            body{
            
                background: linear-gradient(rgb(212, 228, 233),rgb(243, 218, 240),rgb(250, 211, 240));
            }
           
            th {
            background-color: #ffe6fa;
            color: #0a0a0a;
            font-weight: bold;
        }

        td {
            background-color: #fdf7ff;
        }

           .day {
            font-weight: bold;
            background-color: #f8e4ff !important;
        }
        .vertical-text{
            writing-mode: vertical-rl;
            text-orientation: upright;
            letter-spacing: 10px;
            font-weight: bold;
            background-color: #f8d3f8;
           }
           
           

            
        </style>
    </head>
    <body>
        <img src="logo-1.png" alt="saveetha engineering college logo" style="border: 2px dotted bisque;">
        <caption><h1 style="text-align:center;color:rgb(15, 14, 15); "><u>TIMETABLE-NITHYA JEYSHRI(25018780)</u></h1></caption>
        <table>
            <tr>
              <th>DAY/TIME</th>
              <th>8am - 10am</th>
              <th>10am - 12am</th>
              <th rowspan="7" class="vertical-text"><span>LUNCH</span>
              </th>
              <th>1pm - 3pm</th>
              <th>3pm - 5pm</th>
            </tr>
            <tr>  
                <td class="day">MONDAY</td>
                <td colspan="2">FREE SLOT</td>
                <td colspan="2">Python</td>
            </tr>
            <tr>
                <td class="day">TUESDAY</td>
                <td rowspan="2">FREE SLOT</td>
                <td>English</td>
                <td>FWAD</td>
                <td rowspan="3">FREE SLOT</td>  
            </tr>
            <tr>
                <td class="day">WEDNESDAY</td>
        
                <td>FWAD</td>
                <td>Mentor Meet</td>
            
            
            </tr>
            <tr>
                <td class="day">THURSDAY</td>
                <td>Python</td>
                <td>English</td>
                <TD>English</TD>
                
            </tr>
            <tr>
                <td class="day">FRIDAY</td>
                <td>FREE SLOT</td>
                <td>FWAD</td>
                <td>FREE SLOT</td>
                <td>Python</td>
            </tr>
            <tr>
                <td class="day">SATURDAY</td>
                <td colspan="2">FWAD</td>       
                <td>Python</td>
                <td>English</td>
                 </tr>
            
        </table>
        <DIV ID="ONE">
        <table style="margin-top: 30px; ">
            <tr>
                <th>S.no</th>
                <th>Course Name</th>
                <th>Course Code</th>
            </tr>
            <tr>
                <td>1</td>
                <td>Python programming</td>
                <td>19AI301</td>
            </tr>
            <tr>
                <td>2</td>
                <td>Communicative English</td>
                <td>19EN101</td>

            </tr>
            <tr>
                <td>3</td>
                <td>Fundamentals of Web Application Development</td>
                <td>19AI414</td>
            </tr>
        </table>
        </DIV>
        
    </body>
</html>
```
# OUTPUT
![alt text](<Screenshot (74).png>)
# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
