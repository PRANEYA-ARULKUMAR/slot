# Ex03 Time Table
## Date:04/05/2025

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
NAME: A PRANEYA
REGISTER NO: 212224110045
```

```
<!DOCTYPE html>
<html>
    <head>
        <title>timetable</title>
        <style>
            .tt,.course{
                height:350px;
                background-color:#fdf5f1;
            }
            .t1{
                border: 1px;
                width:80%;
                margin:auto;
                border-bottom:#e2e1e1 solid;
                border-left:#e2e1e1 solid;
                border-right:#e2e1e1 solid;

            }
            .t1 th,.t1 tr,.t2 th,.t2 tr{
                padding: 15px;
                WIDTH:100PX;
                border-spacing:30PX;
                text-align: center;
            }
            .t1 th,.t2 th{
                background-color:#FAD0C4;
            }
            .t1 tr,.t2 tr{
                background-color:#FFF7F3;
            }
            .t1 tr:nth-of-type(even)
            {
                background-color:#ecefe9;
            }
            .t2{
                border: 3px;
                width:70%;
                margin:auto;
                border-bottom:#e2e1e1 solid;
                border-left:#e2e1e1 solid;
                border-right:#e2e1e1 solid;
            }
            .t2 tr:nth-of-type(even)
            {
                background-color:#ecefe9;
            }
            .logo{
                width:50%;
                margin-left: auto;
                margin-right: auto;
                display:block;

            }
            H3{
                text-align: center;
                font-weight: bold;
            }
        </style>
    </head>
    <body>
        <img src="/static/logo.png" alt="LOGO" class="logo"/>
        <br>
        <div class="tt">
            <H3><u>I YEAR 2028-PRIME BATCH WEEKLY SCHEDULE</u></H3>
            <table class="t1">
                <caption><b><u>WEB DEV AND AI BATCH</u></b></caption>
                <br>
                <thead >
                    <th>DAY</th>
                    <th>8-10</th>
                    <th>10-12</th>
                    <TH>1-3</TH>
                </thead>
                <tbody>
                <tr>
                    <td>MONDAY</td>
                    <td>WEB DEVELOPMENT</td>
                    <TD>TASK ASSIGNMENT</TD>
                    <TD>FUNDAMENTALS OF AI</TD>
                </tr>
                <tr>
                    <td>TUESDAY</td>
                    <TD>TASK COMPLETION</TD>
                    <td>WEB DEVELOPMENT</td>
                    <TD>MODULE COMPLETION</TD>
                </tr>
                <tr>
                    <td>WEDNESDAY</td>
                    <td>ASSESSMENT HOUR</td>
                    <TD>TASK PRESENTATION</TD>
                    <TD>MENTOR MEET</TD>
                </tr>
                <tr>
                    <td>THURSDAY</td>
                    <TD>TASK PRESENTATION</TD>
                    <td>MODULE COMPLETION</td>
                    <TD>FUNDAMENTALS OF AI</TD>
                </tr>
                <tr>
                    <td>FRIDAY</td>
                    <TD>TASK COMPLETION</TD>
                    <td>WEB DEVELOPMENT</td>
                    <TD>TASK COMPLETION</TD>
                </tr>
                <tr>
                    <td>SATURDAY</td>
                    <td colspan="3">MODULE ASSESSMENT COMPLETION</td>
                </tr>
                </tbody>
            </table>
        </div>
        <div class="course">
            <table class="t2">
                <caption><b><u>COURSE DETAILS</u></b></caption>
                <thead >
                    <th>COURSE CODE</th>
                    <th>COURSE NAME</th>
                    <th>FACULTY</th>
                </thead>
                <tbody>
                <tr>
                    <td>19AI414</td>
                    <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
                    <TD>DR SELVA KUMAR</TD>
                </tr>
                <tr>
                    <td>19CS301</td>
                    <TD>FUNDAMENTALS OF ARTIFICIAL INTELLIGENCE</TD>
                    <td>MS SWEDHA</td>
                </tr>
                </tbody>
            </table>
        </div>
    </body>
</html>
```

## OUTPUT

![alt text](<Screenshot (2).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
