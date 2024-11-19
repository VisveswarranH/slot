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
```
<HTML>
    <HEAD>
    <TITLE>Time Table</TITLE>
    </HEAD>
    <BODY>
    <center>
    <img src="/static/logo.png"height="100"width="540">    
    </center>
    <TABLE border = "1" align = "center" cellpadding = "5" bgcolor = "cyan">
    <CAPTION>SLOT TIME TABLE - VISVESWARRAN H(24006599)</CAPTION>
    <TR bgcolor = "yellow">
    <TH>DAY/TIME</TH>
    <TH>8 - 10</TH>
    <TH>10 - 12</TH>
    <TH rowspan = "7">Lunch</TH>
    <TH>1 - 3</TH>
    </TR>
    <TR>
    <TH bgcolor = "yellow">Monday</TH>
    <TD>PROBABILITY AND QUEUEING MODELS</TD>
    <TD>FREE SLOT</TD>
    <TD>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</TD>
    </TD>
    </TR>
    <TR>
    <TH bgcolor = "yellow">Tuesday</TH>
    <TD>CAREER DEVELOPMENT SKILLS</TD>
    <TD>PHYSICS AND QUANTUM COMPUTING</TD>
    <TD>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</TD>
    </TR>
    <TR>
    <TH bgcolor = "yellow">Wednesday</TH>
    <TD>FREE SLOT</TD>
    <TD>PROBABILITY AND QUEUEING MODLES</TD>
    <TD>Mentor Meet</TD>
    </TR>
    <TR>
    <TH bgcolor = "yellow">Thursday</TH>
    <TD>GUMAN VALUES AND PROFESSIONAL ETHICS</TD>
    <TD>FUNDAMENTALS OF C PROGRAMMING</TD>
    <TD>COMMUNICATIVE ENGLISH</TD>
    </TR>
    <TR>
    <TH bgcolor = "yellow">Friday</TH>
    <TD>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</TD>
    <TD>COMMUNICATIVE ENGLISH</TD>
    <TD>FUNDAMENTALS OF C PROGRAMMING</TD>
    </TR>
    <TR>
    <TH bgcolor = "yellow">Saturday</TH>
    <TD>FREE SLOT</TD>
    <TD>FREE SLOT</TD>
    <TD>PHYSICS FOR QUANTUM COMPUTING</TD>
    </TR>
    </TABLE>
    <BR>
    <TABLE border = "1" align = "center" cellpadding = "5">
    <CAPTION>Courses</CAPTION>
    <TR>
    <TH>S.No</TH>
    <TH>Course Code</TH>
    <TH>Course Name</TH>
    </TR>
    <TD>1.</TD>
    <TD>19EN101</TD>
    <TD>COMMUNICATIVE ENGLISH</TD>
    </TR>
    <TR>
    <TD>2.</TD>
    <TD>19EY708</TD>
    <TD>Career Development Skills</TD>
    </TR>
    <TR>
    <TD>3.</TD>
    <TD>SH3214</TD>
    <TD>PHYSICS FOR QUANTUM COMPUTING</TD>
    </TR>
    <TR>
    <TD>4.</TD>
    <TD>SH7801</TD>
    <TD>HUMAN VALUES AND PROFESSIONAL ETHICS</TD>
    </TR>
    <TR>
    <TD>5.</TD>
    <TD>19AI414</TD>
    <TD>Fundamentals Of Web Application</TD>
    </TR>
    <TR>                
    <TD>6.</TD>
    <TD>19MA222</TD>
    <TD>PROBABILITY AND QUEUEING MODELS</TD>
    </TR>
    </TABLE>
    </BODY>
    </HTML>
```
## OUTPUT
![alt text](<Screenshot (9).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
