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

## PROGRAM

### urls.py :
```
from django.contrib import admin
from django.urls import path

from openfile_app import views

urlpatterns = [
    path('admin/', admin.site.urls),
    path('timetable/', views.timetable, name='timetable'),
]

urls.py
```
### views.py :
```
from django.shortcuts import render

def timetable(request):
    return render(request, 'openfile_app/timetable.html')
```
### timetable.html :
```
<!DOCTYPE html>
<html>
    <head>
        <title>Time Table</title>
    </head>
    <body>
<TABLE BORDER="4" width="950" bgcolor="white" cellspacing="3" cellpadding="2"> 
    <TR> 
        <TH colspan="4" bgcolor="cyan" align="center">TIME TABLE</TH>
    </TR>
    <TR> 
        <TD BORDER="4"rowspan="2"><b>Reference Number:</b></TD>

    </TR>
    <TR>
        <TD BORDER="4"><b>23002622</b></TD>
        <TD BORDER="4">Name:</TD>
        <TD BORDER="4">P.REVANTH</TD>
    </TR>
    <TR> 
        <TD rowspan="2"><b>DAYS</b></TD>

    </TR>
    <TR>
        <TD>1</TD> 
        <TD>2</TD>
        <TD>3</TD>
        <TD>4</TD>

    </TR>
    <TR> 
        <TD rowspan="2" width="25%">Monday</TD>

    </TR>
    <TR>
        <TD width="25%">-</TD> 
        <TD width="25%">-</TD>
        <TD width="25%">19EE305/JOHN DE BRITTO.C</TD>
        <TD width="25%">19AI304/MAGITHA NIRMALA TENNYSON</TD>
    </TR>
    <TR> 
        <TD rowspan="2" width="25%">Tuesday</TD>

    </TR>
    <TR>
        <TD width="25%">-</TD>
        <TD width="25%">19CS408/DHIVYA DHARSHINI.S</TD> 
        <TD width="25%">19AI414/SEVAKUMAR.R</TD>
        <TD width="25%">-</TD>
    </TR>
    <TR> 
        <TD rowspan="2" width="25%">Wednesday</TD>

    </TR>
    <TR>
        <TD width="25%">-</TD>
        <TD width="25%">19EE305/JOHN DE BRITTO.C</TD>
        <TD width="25%">19EY702/EVANGELIN HELEN</TD>
        <TD width="25%">19CS406/NALINIPRIYA.G</TD>
    </TR>
    <TR> 
        <TD rowspan="2" width="25%">Thursday</TD>

    </TR>
    <TR>
        <TD width="25%">19CS408/DHIVYA DHARSHINI.S</TD> 
        <TD width="25%">19MA222/SRAVYA.PR</TD>
        <TD width="25%">19AI414/SEVAKUMAR.R</TD>
        <TD width="25%">-</TD>
    </TR>
    <TR> 
        <TD rowspan="2" width="25%">Friday</TD>

    </TR>
    <TR> 
        <TD width="25%">19AI414/SELVAKUMAR.R</TD>
        <TD width="25%">19AI304/MAGITHA NIRMALA TENNYSON</TD> 
        <TD width="25%">19CS406/NALINIPRIYA.G</TD>
        <TD width="25%"></TD>
    </TR>
    <TR>
        <TD width="25%">19MA222/SRAVYA.PR</TD> 
        <TD width="25%">-</TD> 
        <TD width="25%">-</TD> 
        <TD width="25%">-</TD> 
    </TR>
    </TABLE>
    </body>
</html>
```

## OUTPUT :
![WhatsApp Image 2024-03-19 at 20 11 22_288540f7](https://github.com/Revanth-2717/slot/assets/152462274/66ab8ebf-8942-4773-9ba6-e4f961575d68)
<br>
<br>
<br>
![WhatsApp Image 2024-03-19 at 20 11 20_0712f1c3](https://github.com/Revanth-2717/slot/assets/152462274/3107487d-7e46-43e0-92ba-8c0ab2a8ce55)
<br>
<br>
<br>
![WhatsApp Image 2024-03-19 at 20 11 09_7ca5ca44](https://github.com/Revanth-2717/slot/assets/152462274/2d1f10a6-fa74-4c70-94c9-8f211b8986d7)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
