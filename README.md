# Ex03 Time Table
## Date:01.10.2025

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
    <html >
    <head>

    <body>
    <img src="logo.png" algin="left" height="130px" width="600px">
        <h1 align="center">TIMETABLE-25018001</h1>

    <table BORDER="4" bgcolor="cyan" height="500" width="750" cellpadding="10" cellspacing="10">
        <tr> 
            <th colspan="5" align="center" bgcolor="red"> TIMETABLE</th>
             </tr>
        <tr>
                    <th> DAY</th>
            <td rowspan="1" width="25%">8-10</td>
            <td rowspan="1" width="25%">10-12</td>
            <td rowspan="1" width="25%">1-3</td>
            <td rowspan="1" width="25%">3-5</td>
            </tr>
    <tr>
        <th>Monday </th>
                <td width="25%">Free</td>
        <td width="25%">Python</td>
        <td width="25%">Free</td>
        <td width="25%">Web</td>
    </tr>
     <tr>
            <Th>Tuesday</Th>
                <td width="25%">web</td>
        <td width="25%">DS</td>
        <td width="25%">DS</td>
        <td width="25%">Web</td>
    </tr>
     <tr>
            <Th>Wednesday</Th>
        <td width="25%">Free</td>

        <td width="25%">web</td>
        <td width="25%">Mentor session</td>
        <td width="25%">Python</td>
    </tr>
     <tr>
            <Th>Thursday</Th>
        
                <td width="25%">DS</td>
        <td width="25%">Python</td>
        <td width="25%">Free</td>
        <td width="25%">Python</td>
    </tr>
     <tr>
            <Th>Friday</Th>
                <td width="25%">web</td>
        <td width="25%">DS</td>
        <td width="25%">DS</td>
        <td width="25%">Python</td>
    </tr>
    </table> 
    <br>
        <table border="3" cellspacing="3" cellpadding="10">
            <tr>
            <th>S.No</th>
            <th>Subject Code</th>
            <th>subject Name</th>
            </tr>
            <tr>
                <th>1</th>
                <th>19AI414</th>
                <th>Fundamentals of Web Application Development</th>
            </tr>
            <tr>
                <th>2</th>
                <th>19AI401</th>
                <th>Python Programming</th>
            </tr>
            <tr>
            <th>3</th>
            <th>19AI403</th>
            <th>Data Science</th>
        </table>  
     </body>
         </html>

## OUTPUT
![alt text](<Screenshot (21).png>)
## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.