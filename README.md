# Ex03 Time Table
## Date: 18-03-24

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

## PROGRAM :
```
<html>
    <head>
        <title>MY TIME TABLE</title>
    </head>
    <body>
        <center>
        <img src="logo.png" height="100" width="777">
        </center>
        <table align="center" border="2" cellspacing="12" cellpadding="12" height="25" width="50">
            <h1 align="center">Slot Time Table-P.REVANTH (212223040143)</h1>
            <tr>
                <th bgcolor="yellow">DAY/TIME</th>
                <th bgcolor="yellow">MONDAY</th>
                <th bgcolor="yellow">TUESDAY</th>
                <th bgcolor="yellow">WEDNSEDAY</th>
                <th bgcolor="yellow">THURSDAY</th>
                <th bgcolor="yellow">FRIDAY</th>
                <th bgcolor="yellow">SATURDAY</th>
            </tr>
            <tr>
                <th bgcolor="skyblue">8-10</th>
                <td bgcolor="pink">free slot</td>
                <td bgcolor="pink">free slot</td>
                <td bgcolor="pink">chemistry</td>
                <td bgcolor="pink">free slot</td>
                <td bgcolor="pink">fundamental of web</td>
                <td bgcolor="pink">maths</td>
            </tr>
            <tr>
                <th bgcolor="skyblue">10-12</th>
                <td bgcolor="pink">free slot</td>
                <td bgcolor="pink">free slot</td>
                <td bgcolor="pink">free slot</td>
                <td bgcolor="pink">maths</td>
                <td bgcolor="pink">c program</td>
                <td bgcolor="pink">che</td>
            </tr>
            <tr>
                <th bgcolor="skyblue">12-01</th>
                <th colspan="6" align="center" bgcolor="green">l u n c h</th>
                
            </tr>
            <tr>
                <th bgcolor="skyblue">01-03</th>
                <td bgcolor="pink">creative skill</td>
                <td bgcolor="pink">fundamental of web</td>
                <td bgcolor="pink">english</td>
                <td bgcolor="pink">fundamental of web</td>
                <td bgcolor="pink">computer network</td>
                <td bgcolor="pink">free slot</td>
            </tr>
            <tr>
                <th bgcolor="skyblue">03-05</th>
                <td bgcolor="pink">c program</td>
                <td bgcolor="pink">free slot</td>
                <td bgcolor="pink">computer networks</td>
                <td bgcolor="pink">free slot</td>
                <td bgcolor="pink">english</td>
                <td bgcolor="pink">free slot</td>
            </tr>
        <table align="center" border="2" cellspacing="2" cellpadding="4" >
            <tr>
                <th>S.N0</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
            <tr>
                <th>1</th>
                <th>19AI304</th>
                <th>Fundamental of C Programming</th>
            </tr>
            <tr>
                <th>2</th>
                <th>19AI414</th>
                <th>Fundamental of Web Application</th>
            </tr>
            <tr>
                <th>3</th>
                <th>19CS406</th>
                <th>Computer Networks</th>
            </tr>
            <tr>
                <th>4</th>
                <th>19CY205</th>
                <th>Principles Of Chemistry in Engineering</th>
            </tr>
            <tr>
                <th>5</th>
                <th>19EN101</th>
                <th>Communicative English</th>
            </tr>
            <tr>
                <th>6</th>
                <th>19EY702</th>
                <th>Creative Skills for Communication</th>
            </tr>
            <tr>
                <th>7</th>
                <th>19MA222</th>
                <th>Probability and Queueing Models</th>
            </tr>
        </table>
    </body>
</html>
```
## OUTPUT :
![Screenshot 2024-04-30 142741](https://github.com/Revanth-2717/slot/assets/152462274/2ea04cfd-d7d4-44f0-806d-16bfc77aa581)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
